PJS.ThemeStarter
================

Orchard CMS Empty Theme for Customization

This is a completely unstyled Orchard CMS theme that contains copies of all the shapes that I typically override when creating a theme based on a purchased template. Most of the shapes are provided in their default form, some have been stripped down to the minimum code required, and others have been modified with changes that I typically make.

In order to use this theme as a starter for converting a template to an Orchard CMS theme, download the source and modify the following files at a minimum:

* Rename the theme folder from PJS.ThemeStarter to the name of your theme
* Rename the Visual Studio project file and any references within from PJS.ThemeStarter to the name of your theme
* Change the Name property of the theme in Theme.txt from PJS.ThemeStarter to the name of your theme
* In the Gravatar folder, change the namespace in every file from PJS.ThemeStarter to the name of your theme

Add the downloaded and renamed theme folder to the Themes folder of your Orchard installation. You can then Add an Existing Project to the Themes folder within Visual Studio. DO NOT add it to the Themes project which is under the Themes folder.
