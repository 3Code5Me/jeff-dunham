# jeff-dunham

1. Install GitHub for Mac then fork and clone our repository. To use Git from the Terminal, see the Setting up Git and Fork a Repo articles. If you'd rather not use Git, use the 'Download ZIP' button on the right to get the source directly.

2. Install the latest version of Xcode.

3. Open your source folder in Finder and double-click on Setup.command to download binary content for the engine. You can close the Terminal window afterwards. If you downloaded the source as a .zip file, you may see a warning about it being from an unidentified developer (because .zip files on GitHub aren't digitally signed). To work around it, right-click on Setup.command, select Open, then click the Open button.

4. In the same folder, double-click GenerateProjectFiles.command. It should take less than a minute to complete.

6. Load the project into Xcode by double-clicking on the UE4.xcworkspace file. Select the ShaderCompileWorker for My Mac target in the title bar, then select the 'Product > Build' menu item. When Xcode finishes building, do the same for the UE4 for My Mac target. Compiling may take anywhere between 15 and 40 minutes, depending on your system specs.

7. After compiling finishes, select the 'Product > Run' menu item to load the editor.
