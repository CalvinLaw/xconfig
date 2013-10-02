## xconfig

This repository hosts configuration files for iOS Xcode projects.

### Instructions

Projects may be built with separate schemes: Debug, Release, and Test.

Each scheme specifies it's own set of criteria. Shared criteria is defined in Base.xconfig and inherited by the files. These files allows one to specify build configurations without having to place information into the Xcode Project Editor but also to easily share configuration settings across multiple projects.

### Usage

As of Xcode 5.0, xconfig files can be specified for a project by going to the Project Editor's 'Info' tab, then 'Configurations'.

### References

https://developer.apple.com/library/ios/recipes/xcode_help-project_editor/Articles/BasingBuildConfigurationsonConfigurationFiles.html
