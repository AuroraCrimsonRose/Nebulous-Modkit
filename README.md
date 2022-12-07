# Nebulous-Modkit
## A collection of files to get started with nebulous modding.

##### This is a Tutorial / Basic File structure to get started with nebulous modding.

#### Getting Started.

Install Unity 2019.3f.19

Open Unity and create a project, it has to be HDRP.

Once your project is open we need to delete the defalt files.

##### Clearing your Project.

Delete all of these.

![Clear your Scene](https://dl.dropbox.com/s/3a1mvzi1kwbwuc2/scene.JPG)

Delete all of these.

![Clear your Scene](https://dl.dropbox.com/s/27kv8bto11jksn0/asset%20bundle.JPG)

##### Setting up your project.

Now that you have your scene clear we need to set your project up for Mono and [.NET 4.0].

First your going to click "Edit" in the top left of your unity editor.
now click on "Project Settings".
Now that we have the "Project Settings" window open we are going to click player.
Once it opens player settings wee are going to scroll down to "Other Settings" and click the drop down.

In "Other Settings" we are going to set Scripting Backend to "Mono" and Api Compatibility Level to ".NET 4.0".

![Settings](https://dl.dropbox.com/s/53sgxokn6pernxu/api.JPG)

Once you've done this save the project and reopen it.

Once you have your project open go ahead and download these project files and extract them.
Once you've extracted the files drag and drop the Folders, "Editor", "Lib", and "Scripts" into your Assets folder in the unity editor.
Now you have all of the folders setup and the AGM Toolkit.

##### Grabbing files from Nebulous.

First off we are going to grab the Dll's to Nebulous.
This will let us add our scripts in game.

Go to your Nebulous Installation Root Directory and find "Nebulous_Data"and then "Managed"

This will Usually be located at "C:\Program Files (x86)\Steam\steamapps\common\Nebulous\Nebulous_Data\Managed"
You will grab the following from that folder and copy them to the "Lib" folder in your unity project.
![Dlls](https://cdn.discordapp.com/attachments/1050059231572807731/1050061239734243358/dlls.JPG)

Now we need to grab the stock assets from the game as well.

This will Usually be located at "C:\Program Files (x86)\Steam\steamapps\common\Nebulous\Assets\AssetBundles"
Grab the following highlighted files and put them in your project in "Editor/AssetBundles"
![Stock Assets](https://cdn.discordapp.com/attachments/1050059231572807731/1050062135763410944/asset_bundle.JPG)

Now that we have done this we have succesfully created a Modding Enviroment for us to work with.

Very important quick note, everytime the game updates you will have to re-import both your stock files I.E. [Stock, Stock.Manifest] and your libraries files.

##### Creating Components.

[WIP]
