Heroku Buildpack: Installer
===========================

Usage
----

Define the build process in a file named ``.Buildfile`` in your project root::

    relative/path/to/your/installer.sh

or::

    python relative/path/to/your/installer.py

This script will be sourced in a bash environment, you can do some logic in here, but it is not advised.
Use it to start a custom build command in your environment.
