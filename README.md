Load the plugin to your server to generate the default data file.

Copy the "Skins": [ ] section from your Skins.json and place it in data/ImportSkins/import.json

Assign the importskins.admin permission to the group or player allowed to import

Use the command /importskins to start the import process

The import process imitates the players saying /addskin [skinid] by substituting a skin id from the data file for each message

Your server console should see a response from the SkinController plugin that a skin is being imported

Once the plugin has imported all skins a message is sent to the player.

*It is untested if a player can continue normal play while plugin is importing.
