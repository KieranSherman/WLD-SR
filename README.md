## StreamSAK v2.2

As a streamer, I've always looked for an elegant tool that I could use to adjust my wins/losses/draws count on the fly, or various text tidbits, without having to tab out or edit a file manually.  I never found anything, so I decided to make it myself.

Note: The program creates files to hold the data in the program location.  For example, if the .jar file is on my Desktop, it will create its files on the Desktop.  I recommend placing it in a folder by itself somewhere.  Then, just set up OBS to read in text from a file, and your counter/text adjuster is all set up to go!

Want to see it in action?
https://www.youtube.com/watch?v=drnV5E5TTUM

Since the video (the **original release**), very few changes have been made, check the release notes below to get a better idea of what's been changed.



## Releases:

**v2.2 (04/06/18) - Revised creation/deletion options, added self-check updater, adjusted counter naming convention to show if it calls an adjuster.**
  - Deleting counters and adjusters isn't quite as picky.  You used to have to type the exact name of the counter/adjuster, which you may not have realized since it could have been hidden (e.g. the counter "wins--sr" would display as "wins").  Now, the program automatically finds the best match to delete (e.g. "wins--sr" would be deleted if you just typed "wins").
  - If counters automatically called an adjuster after use, you had no indication.  Now, if it calls an adjuster, it is displayed in its name (e.g the counter "wins--sr" would be displayed as "wins [+1]--sr").
  - If StreamSAK is out of date, it will let you know with an option to update it.
  - Automatic Adjuster Calls (the thing that will automatically allow you to modify your adjuster after you click a counter) was shortened to AAC, and changed into a toggle button rather than a checkbox. 
  - Supporting the developer (me) has been moved from the title to directly above the log, and isn't as "in your face".  Now it just says "*Support the dev*", instead of a direct link to my Twitch channel.
  - When to provide input is more obvious (textbox changes color, and cursor always flashes).

**v2.1 (04/06/18) - Added creation/deletion options of counters/adjusters.**
  - You can now create and delete counters and adjusters directly from the program.

**v2.0 (04/05/18) - Original release.**
