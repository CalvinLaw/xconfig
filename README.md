## xconfig

A pretty good project starts with a pretty good configuration. These files define iOS build configurations for Xcode without having to go into the Xcode interface to make changes. Also, they can be easily shared across projects.

### Instructions

Projects may be built with separate schemes: Debug, Release, and Test.

Each scheme (Debug/Release/Test) specifies it's own set of criteria. Criteria defined in Base.xconfig is shared and inherited by the other files.

Check out a few of my other projects for an [example](https://github.com/piemonte/PBJVision/).

### Usage

As of Xcode 5.0, these xconfig files can be setup for a project by going to the Project Editor's 'Info' tab, then 'Configurations'.

If you can adopt these early on, your project stability and quality will greatly benefit. If you would like to adopt these for an existing project, I recommend commenting out each line and slowly enabling them as you fix code.

### References

[Project Editor Help: Add a Build Configuration](https://developer.apple.com/library/ios/recipes/xcode_help-project_editor/Articles/BasingBuildConfigurationsonConfigurationFiles.html)
