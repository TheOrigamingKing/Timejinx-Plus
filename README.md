# Timejinx-Plus
Introducing Timejinx+! This is a mod for Timejinx from The Jackbox Party Pack 10. After a few rounds of playing the base game of Timejinx, I started to notice repeating questions. And so, I made this mod! This mod adds  over 25 unique games, with 120% more content for base year questions. Overall, it adds about more than 80% more content! Have fun!

**DISCLAIMER:**
This mod is only available in the English translation. There is no translation for the plus questions. Sorry :(

**Instructions:**
Hello! If you're reading this that means you're downloading Timejinx+. These instructions will teach you how to safely add all the files without breaking your game. First off, let's figure out how to even find where to put files by first locating where files are

**How to locate local files**

-Go to Pack 10 in your Steam Library

-Click the gear button

-After clicking on the gear button, hover over "manage"

-After hovering over manage, Click on "browse local files"

Great! Now you're in. You're going to see a lot of stuff here. Don't change any of it. What you're going to want to do is **click on the folder "games"**

Is it open? Good! First we're going to change a little bit of the picker, just to change the picker menu to "Timejinx+" instead of Timejinx and add a custom description.

**Changing your picker**

-Go to the JPP10 file named "Picker"

-You should see a file that says "Localization.json". **Backup this file by renaming it.** Maybe to something like "LocalizationOriginal.json".

-Then (now this is important) go to the "Picker Files" of the Timejinx+ build you just downloaded. **There will be a Localization file there**. Without renaming it, put it into the "Picker" folder of JPP10. 

And that's it! If you want to, open the game and test it out. You should see "Timejinx+" where "Timejinx" used to be and a brand new description. 

Now, here's the MEAT of the mod. And... the actual mod. That was just cosmetic! **Go back to the "games"** folder in the Jackbox Party Pack 10 files. Then, go to the **TimeTrivia** folder. This is where most of the work will be done.

**Modding TimeJinx+ Successfully**

Now that you're in the TimeTrivia file, Here's what you're going to want to do.

**Backup the files named Credits.html, Localization.json, settings.json, and TimeTrivia.swf. Do the same process as what you did for the backing up of the Localization of the Picker file**

Yes I know the folder is called TimeTrivia, but if you scroll to the bottom there will be a file called TimeTrivia.swf. Back that up.

Now, in the "TimeTrivia Files" of the download, add the "Credits.html, Localization.json, settings.json, TimeTrivia.swf". Don't change their names and just add them to the TimeTrivia folder.

Now that that's done, here's what you need to do. Go to the "content" folder of the release build. **Before clicking "en", take the manifest and add it to TimeTrivia folder of the JPP10. Remember to backup the original manifest as well, in the same way you backed up your credits and Localization etc.** 

After adding the manifest, click on "en" in the release build folder. Do the same in your "content" folder of the JPP10. When you open the "en" in the release build folder, you should see a bunch of JET files that all have "Plus" at the end of them. **Add these to the "en" folder of your "content" folder in the JPP10. Additionally, replace the JET files of "TimeTriviaGeoImages" and "TimeTriviaImpostorImages" in the "en" folder of the JPP10 with the "TimeTriviaGeoImages" and "TimeTriviaImpostorImages" from the release build folder. And that's all the JET folders moved!**

Also, *in the "en" folder of the release build*, you should see three folders named "TimeTriviaImpostorImages", "TimeTriviaHop"  & "TimeTriviaGeoImages". **Take the content of these folders and add them their respective folders in the JPP10 version of the "en" folder.** 

Now for the last step. *Go to the release build "TimeTrivia Files". You should see a "swf" folder there with 4 flash movies in it.* These have the mod-related images that are not content based. Go to the swf of the TimeTrivia in JPP10 (you do this by opening up "TimeTrivia" and going to "swf". **Replace the "timetrivia_postgame, timetrivia_menu, timetrivia_lobby & timetrivia_intro" files with the respective "timetrivia_postgame, timetrivia_menu, timetrivia_lobby & timetrivia_intro" from the Timejinx+ Release Build folder. Make sure to back up the JPP10 swfs by renaming them as well.** And that's all the folders added!

And NOW you're done! Thanks for downloading and happy installing!
