# Gorilla Tag Mod Template (Updated for Newtilla)

## Template Information

The template creates the following files of note:
* [Plugin.cs](src/Content/GorillaTagModTemplateProject/Plugin.cs): The main class of your mod. Most of your code should go here.
* [PluginInfo.cs](src/Content/GorillaTagModTemplateProject/PluginInfo.cs): This holds information about your plugin in a central location. This is where the plugin name, id, and version are stored.
* [HarmonyPatches.cs](src/Content/GorillaTagModTemplateProject/HarmonyPatches.cs): This handles the application of harmony patches (such as ExamplePatch). You shouldn't need to modify this class.
* [Patches/ExamplePatch.cs](src/Content/GorillaTagModTemplateProject/Patches/ExamplePatch.cs): This demonstrates how patches are created, you should remove or modify it as you see fit.
* [MakeRelease.ps1](src/Content/GorillaTagModTemplateProject/MakeRelease.ps1): This script generates a [MonkeModManager](https://github.com/BzzzThe18th/MonkeModManager) compatible release (named ModName-v.zip). You should use this to create builds that you share with others.
* [Directory.Build.props](src\Content\GorillaTagModTemplateProject\Directory.Build.props): This file contains information about where dependencies are located. If you are getting CS024 (type could not be found) errors, GamePath is probably wrong. 

## Steps

1. Download the [Latest Release](https://github.com/Toastconcern/GorillaTagModTemplate/releases/latest)

2. Open the GorillaTagModTemplateProject, then open GorillaTagModTemplateProject.csproj in Visual Studio

3. To build, click Build, then Build Solution
![image](https://github.com/user-attachments/assets/2857aeb7-ca63-48a9-be62-1e9273a9b3b7)

4. Mod sould be in C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag\BepInEx\plugins

