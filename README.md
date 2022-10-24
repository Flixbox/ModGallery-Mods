# ModGallery-Mods

[![](https://img.shields.io/static/v1?label=Discuss&message=on%20Discord&color=7289DA&style=flat&logo=discord)](https://discord.gg/vnZMK2kyY5)

Mod & Map collection for [ModGallery](https://github.com/Flixbox/ModGallery).

All content belongs to the people who made it. Feel free to post an issue here or DM Flixbox on [Discord](https://discord.gg/vnZMK2kyY5).

## The `mod.json` file

Mods (not maps) require a `mod.json` file in their folder. The path is `/modFolders/<your mod>/mod.json`. It looks like this:

```json
{
  "publishedfileid": "2873117363",
  "version": 10,
  "versionText": "1.0"
}
```

`publishedfileid` refers to your mod's ID on the Steam Workshop. **This is optional, but without it your mod won't have any images.**

> You can find this ID at the end of the URL of your mod on the Steam Workshop. Example:
>
> `https://steamcommunity.com/sharedfiles/filedetails/?id=2780996118`
>
> The `id` part at the end refers to the mod ID. Make sure to use your own ID.

`version` needs to be incremental. This means that a new version must have a higher number than the previos versions of that mod.

`versionText` can be whatever you like. It will be shown to the users in the application. Maybe increase it together with `version` to make it look nice.

## How to add a mod or map

Guide for non-contributors (no repo write permissions, the default):

- Fork the repo
- Clone your fork
- Add your content
- Add a `mod.json` file to your mod, as described above.
- Commit and push your changes.
- Refresh your fork on GitHub. You should see a button above your files that allows you to create a pull request. Click it and follow the instructions on GitHub.
- Wait for the pull request to be accepted or ping Contributors (For example Flixbox) on Discord until they accept it.

Guide for contributors:

- Clone the repo
- Add your content
- Add a `mod.json` file to your mod, as described above.
- Commit and push your changes.

Finally, restart ModGallery and check if your content appears in the list.

## Detailed guide for non-dev contributors

- Install [GitHub Desktop](https://desktop.github.com)
- Log in to your GitHub Account in GitHub Desktop
- Click `Clone a repository from the Internet...`
- Click `URL`
- Copy & Paste the URL to this repo - `https://github.com/Flixbox/ModGallery-Mods`
- You can now make changes to the mods and maps. Click `Show in Explorer` to open the folder.
- Once you'd like to finalize your progress, put in a summary of your changes in the `Summary` field. Example: `Added the Cataclysm mod`
- Click `Commit to main`
- Click `Push origin`
- Close and reopen the `ModGallery` program. Check if everything is in order and your changes appear.
