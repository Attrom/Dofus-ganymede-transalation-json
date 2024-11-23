# Dofus-ganymede-transalation-json

## Setup

Dowload the rules.json (or the npcs.json)

Use find and replace extension https://chromewebstore.google.com/detail/find-and-replace/bhmpidliobdjgkohacnkgfagkdmckcia

Open the extension,
-> click on settings
-> Import & Export
-> Import
-> pick the .json file you just dowloaded from here

## Run

Open the guide in edit mode
-> Show 100 steps per page
-> Unfold ALL
-> open the extension
Do NOT click on run all
-> Click on Run for each collection starting from the first to the last: 02. name -> 04. -> 05. -> 06. -> 08. -> etc.
-> Give it like 5 seconds each time to finish running, before going to the next collection (watch as it will tell you how many words it replaced)

After this it is advisable to read the guide, and look for any improvements


## If you want to write your own rules

It is advisable to look in each collection to understand what kind of rules fit where, but in general the more words in the expression, the higher up the rule, except for "02. names" 

If you want to match some short words like "et" (meaning "and"), you MUST ADD \b before and after the "et" (look in 20. small words for an example). You can and maybe should do this with longer words too, but there is not much reason to do this when looking for 2 or more words (example: "sous les")

If you find something that is part-fr and part-en you can add a rule for it in collections 32 or 36



## If you want to contribute

You can export your own rules, then create a branch from this repo, and add your own rules.json, and create a pull request to the main branch, then notify me (Discord: attrom)

