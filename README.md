xconfig
===========

configuration files for Xcode projects

This repository hosts the configuration files we use for building our iOS apps at DIY. Projects are built in two separate modes, Debug or Release. Each mode specifies it's own set of criteria. Shared criteria is defined in Base.xconfig and inherited. This allows one to specify build configurations without using the Xcode interface but also to easily share configuration settings across projects.

As of Xcode 4.6.1, xconfig files are specified within a project's 'Info' tab, under 'Configurations'.

References

http://developer.apple.com/library/ios/#recipes/xcode_help-project_editor/Articles/BasingBuildConfigurationsonConfigurationFiles.html
