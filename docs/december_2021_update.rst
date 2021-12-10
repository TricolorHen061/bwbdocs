December 2021 Update
====================
**This short article outlines the December 2021 update. If you just want to learn how to use the bot now, a good place to start is** :doc:`blacklisting`.

Bot Updates
-----------
This is probably the biggest update this bot has ever had, not because of it's size, but because of how it fixes the bots greatest weakness: 

- How easy it was to circumvent by mispelling words
- Lack of documentation


All list commands combined
    All commands that were used to modify lists- ``/badwordlist``, ``/links``, ``/badphraselist``- into one new command: ``/blacklist``. This was done to lessen the amount of commands people have to remember, and because it's less messy.

Filtering system reworked
    As mentioned above, all filtering commands can now be done with ``/blacklist``. Along with this update, the names of the lists were changed:

    - "badwordlist" -> "exact-match word list"
    - "bad link list" -> "link list"
    - "bad phrase list" -> "phrase list"

    and the newest addition:

    - "in-word-match word list"

    which will make it a lot harder to circumvent by mispelling words. You can read all about how these lists work in :doc:`blacklisting`.

New documentation
    There is new documentation for the bot. It's the website you're on right now! This long-overdue update was made because there was an increasing amount of people getting confused about how to use the bot. You can simply use the bar on the left to navigate the documentation.

Multi-language support
    Historically, Bad Word Blocker only supported English. This was very limiting to the bot, since, obviously, there are Discord servers that are not based on English. Read more about how this works in the "Server Updates" section.

Other features and fixes
    There was a lot of other small things fixed, like how anyone could run the ``/unmute`` command without permissions. There were new features added to existing commands too.

Server Updates
--------------
We have a couple of new updates to the `community server <https://discord.com/invite/hzrauvY>`_

Multi-language contributing
    As you may have read in the above section, support for multiple languages is coming to the bot. Anybody can contribute language translations. Do you know a language besides English? Join the server and send a message in the #language-contributions channel. You can contribute anything, like a translated list of default bad words. You'll also get a new role: Language Contributor

Bug Hunters
    There is a new role you can get-Bug Hunter- when you find a bug (issue) in the bot. When you do, send it in the #bugs channel. If it's confirmed, you'll get the role!

That pretty much sums up this update. I hope it improves your experience with this bot. Stay tuned for more! 