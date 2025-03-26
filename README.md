# Ember OS
A some day to exist hopefully good DS flashcart kernel replacement.
The plan is for this to be good enough to replace YSmenu as the default alteernative kernel that people will use, purley because YSmenu is not open source which I'm not a fan of and because it doesn't have much in terms of cutomisability.

------------------------------------------------------------------------------------------------------
Planned Features:

A mostly databse driven kernel, so adding AP patches, changing cheats, RTS patches if that ever becomes a thing for this kernel, everything is database driven that can be. Databases should also be capable of being edited with any text editor, such as notepad for windows.
* This will hopefully mean people will be able to add their own AP patches and what not easily so that can be done quickly.
* It will allow people to make significant changes to compatibility and so on without re-compiling the entire project.

Compatibility with 'standards' that already exist as well as having it's own alternatives that can be easily edited with any text editor, such as notepad for windows.
* For AP patches, this is things like YSmenu's AP database, of NDS-Bootstraps's IPS AP files, maybe also compatibility with using cheat databases for their AP abilities as an auto AP option.
* For cheat databases, this is just supporting all the file tyes for various cheat databases so if one cheat database has better compatibility or more options for some games than another, you can have options.
* The ability to switch between databases for either the entire kernel or just on a per-game basis, either is possible.

An installer.
* I want this kernel to have a lot of features and extras, but this will come at the cost of making the projects base files a lot larger and making the project more 'bloated'. This is my solution to this, I want to have it so by default, on the first bootup, the kernel will let you pick how heavy or light you want the install to be, probably with four main options, 'Essential', 'Medium', 'Everything' and 'Custom'.
* Essential is just the simplest the kernel can be without any extras, no included extra files, no default theme (just the system theme which is very simple, bare minimum text based GUI), no included programs, just enough to boot and run homebrew (AP patches will have to be added manually).
* Medium is including some basic stuff such as all the AP patches, the cheat database, and a few themes. It just doesn't include stuff such as included emulators and extra programs, it's just the kernel plus all the files and themes, and maybe a few fun things.
* Everything includes everything, lot's of emulators, lot's of extra software, all the themes I make for the kernel, and maybe some other peoples themes too if that ever becomes a thing. Also include a lot of nice extra stuff and fun things, such as maybe some images of replacement labels that sort of match the Ember OS theme that people could print out, or box art, I havent't though this aspect through much but I like the idea never the less, especially for the 'Everything' install.
* Custom will just let you pick and choose what you want, maybe this could also give the option too launch an install script if support for something like that ever get's implemented.
* The installer will also be in charge of detecting what flashcart you have and installing the correct files for it, and then deleting the left over files that are not related to the flashcart it's being installed on.

Customisability.
* I want the UI to be very customisable, where using a different theme could change the way everything is interacted with, for example one theme could make the kernel UI function like Wood RPG, and another could make the UI function like Evolution OS, the possibilities should be endless when it comes to UI customisability.
* The ability to change other internal parts of the kernel should also be customisable, such as databases that are used, settings and so on.
* The ability for the DS settings to be changed from the kernel, such as the wifi settings, user settings and so on.

Advanced file manipulation.
* Basic things such as copying files, pasting files, moving files, deleting files and cutting files.
* Uncommon things on flashcarts such as renaming files, changing the files extensions, and file previews for more than just DS games.
* Things that as far as I know are not really possible on any flashcart kernel.
  * The ability to open such and such program with such and such app, for example, edit a photo with a DS paint/editor program, open a word document, edit a cheat file and so on in a text editor, or even edit DS rom/DS save files in specific editing program designed for that game.
  * The ability create new documents, such as text documents, images, .sav save files, anything that could be useful to create.
  * The ability to do things about DS roms specifically, such as enabling or disabling RTS features, changing which database to use for AP patches, RTS patches and cheat databases, although cheat databases might have the option to use cheats form several different databases.
  * The ability to do things about .sav or .nds.sav files specifically, such as edit the save file or attach it to a different DS rom, for example let's say you originally were playing it with one copy of the rom you have on your SD card, but then that rom becomes corrupt, you can attach it to a different DS rom of the same game.

Real time features.
* Real time save. Yes, this will be software based as I can't really go about addind hardware based save states to existing flashcarts through software, however, I do have an idea on how to get around a lot of the limitations that other software based implementations of real time save on flashcarts have. First one being RTS patches so games can be real time saved and loaded without any issues because things that would have caused issues have either been patched out or had a work around put in place that would allow a game to start up as if nothing had ever happened. These RTS patches would have to have the ability to change the way the game state is loaded into storage, the way these real time saves are put back onto the DS and the way the game runs so problematic code for RTS can be changed.
* Real time guide. This simply shows a text document with a guide related to the game. Some additional functionality to this could be that it supports standard text documents with images, and supports editing these while playing the game.
* Real time cheat. This let's you apply cheats as you play any game in real time.
* Real time game save editor. This let's you change your game save file while running the game.
* Real time AP patch writer. Let's you write the built in AP patch format while you are playing the game, so if you are developing your own AP patches, this could make it easier.
* Real time save editor. This let's you write real time save patches in the middle of running a game in the built in RTS patch format.
* Real time cheat editor. Let's you write game cheats in real time using the built in or other standardised cheat format.
* Real time game menu. This is how you can change some system settings that can be changed during gameplay, use any of the real time features and return to the kernels main menu. More functionality may be added to this in the future.

------------------------------------------------------------------------------------------------------
Further ideas for this kernel?

If you have any further suggestions, feel free to contact me with them. I don't know if everything I have covered here is everything the best possible flashcart kernel should have, so please do let me know if you have anything that would be good to have in the kernel.
