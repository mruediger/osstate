# OSState

The goal is to provide a tool that can list all the changes made to a default installation. This in turn can then be used to implement a configuration management system on top of it. The current plan is to check all installed packages for the files they provide. Any file that is not in that list or has been modified or even removed thus is a change. Folders like `/home/`, `/var`, `/run` and the like have to be ignored.
