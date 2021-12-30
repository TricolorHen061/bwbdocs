Janurary 2022 Update
====================
This update basically simplifies the last :doc:`December 2021 update`, and added support for Discord's new feature "Timeout"

**Sublist name change**
In the last update, "sublists" of the "blacklist" was released. It was a bit confusing, so it's been renamed to "sections". `exact-match` and `in-word-match` have been merged into the "word section". When you add words, you'll be asked if you want the words to be blocked if an exact match is found, or an in-word-match. Asking *after* the user adds the words makes it a whole lot easier to understand.

**Blacklist command updated**
`/blacklist add`
    Instead of having to choose between the 4 sublists like before, you only have 3 options, "word", "phrase", and "link". The bot will put them in their respective sections. Like mentoned above, when you choose "words", it will ask how you want the bot to block the words.

`/blacklist view`
    When you run the command, you do not have to choose a section to view. The website now shows all sections on one page to make viewing the blacklist less tedious.

**Timeout**
    The bot now uses Discord's new "timeout" feature instead of the old fashioned "mute" role people would have to use. Everything, including the commands, have been changed to use the new feature.

**Sensitivity fix**
The last update fixed the bot being easy to bypass, but also made the bot super sensitive. It would block messages that were not bad. This has been fixed.

**Permission Errors**
    The bot will tell you what permission it lacks or why it cannot moderate a user when a permission error occours.
