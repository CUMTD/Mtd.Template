# Mtd.Template

Template repository for standard class library commonly used by MTD.

## Template Installation

1. Download `Mtd.Template.zip` from the [latest release][latest].
2. Copy the zip file to `%USERPROFILE%\Documents\Visual Studio 2022\Templates\ProjectTemplates`. More information on template management available [from Microsoft][ms]. 

[latest]: https://github.com/CUMTD/Mtd.Template/releases/latest
[ms]: https://learn.microsoft.com/en-us/visualstudio/ide/how-to-locate-and-organize-project-and-item-templates?view=vs-2022

## Creating an new Release

1. Make after making changes to the files in `.\Mtd.Template` check the changes in as normal.
2. Once your changes are ready for release, create a new release tag. For example to release version 1.2.3 you would run the following commands:

```bash
git tag v1.2.3
git push --tags
```