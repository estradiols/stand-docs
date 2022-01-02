---
hide:
  - navigation
---

# How to install themes
I've decided to write this document to make it easier for everyone to understand how installing a theme works.  
This is a dumbed down version of what should work in most theme cases. I try to cover every detail.  

### Download a theme.
Maybe you already done this step and that is how you ended up here,  
or maybe you are more like me and first read this before even downloading something.  
If you still have to find a theme, you might wanna check out the [#theme] section in the Stand discord.  
You can also check out my [Awesome Stand] list with resources for Stand.

### Install additional software.
Some themes are packaged using WinRar and use the extension `.rar`,  
If this is the case, you wanna make sure to download and install [WinRar] or [7Zip].  
An optional step for the more advanced users can also be a good code/text editor.

### Make a backup.
Mistakes and f\*ckups are in small corners, even I make them occasionally.  
When installing a theme in Stand its really adviced to make a backup of certain things.  
So I really hope you're not skipping this part of the entire document.

In case of installing a theme it's good to make a backup of the following items.  
These items can be found in the Stand folder located at `%AppData%/Stand`.

- **Theme** - folder  
This folder contains icons used by themes, themes can have custom icons so always backup this folder.  
This folder can be found in the root of the Stand folder.

- **Custom Header** - folder  
This folder contains custom headers, themes can have custom headers so always backup this folder.  
This folder can be found inside the `Headers` folder inside the root of the Stand folder.

- **Your current active Profile** - Profile(s)  
With the new system Stand has included Profiles that have replaced `State.txt`.  
This makes making a backup of your current settings/options very easy.  
    
  You can easily make a backup by going to `Stand > Profiles` and select/create a backup profile.  
  Once you have done this you can `save` your current settings in this profile and you are good to go.

  *You do not have to save this on another location, unless you really do not trust yourself* 😂

## Installation
- [Copy the files.](#copy-the-files)
- [Loading the Profile.](#loading-the-profile)

### Copy the files.
First we are going to take inventory of the files and folders inside the theme package.  
Most themes consist out of a `.txt` file (the Profile) and a couple folders.  
Mostly the folders are named after the folders you already have inside the Stand folder.

So once you made your backup we are going to copy/overwrite the files from the theme.  

- Copy the `.txt` file (Profile) to the Stand `Profiles` folder.  
- If the theme has `.lua` scripts, you can copy those into `Lua Scripts` folder.  
- Then you copy the `Theme` folder into the Stand root folder and overwrite what it wants to overwrite.  
- If it has a header, you can copy this into the `Headers/Custom Header` folder.  
  *The Custom Header folder should be emptied before you going to use a new header*

If you have done all the above, you're almost done!  
All you need to do now is [loading the profile](#loading-the-profile).

### Loading the Profile.
- Open Stand Menu and navigate to `Stand > Profiles` and select the profile we just copied over.
- Then you have a couple options first we check `Active` so it will always be active upon startup.
- Then you click the option `Load` so it will load it directly for you now.
- (Optional) If you wish to have all your changes to be saved automaticly, check `Automaticly Save`.

## References
- **Stand/root folder**  
This is the main folder from where Stand loads themes/scripts and other files.  
This folder can be found at `C:\Users\<USERNAME>\AppData\Roaming\Stand` or `%AppData%/Stand`.

[#theme]: https://discord.com/channels/906313557623336991/906313558537682954
[Awesome Stand]: https://git.gaycookie.dev/GayCookie/awesome-stand
[WinRar]: https://www.win-rar.com
[7Zip]: https://www.7-zip.org/
