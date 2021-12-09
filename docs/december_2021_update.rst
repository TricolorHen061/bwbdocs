December 2021 Update
====================
**This short article outlines the December 2021 update. If you just want to learn how to use the bot now, a good place to start is** :doc:`blacklisting`.

This is probably the biggest update this bot has ever had, not because of it's size, but because of how it fixes the bots greatest weakness: 

- How easy it was to circumvent by mispelling words
- Lack of documentation

Below is a list of what this update includes.

All list commands combined
    All commands that were used to modify lists- ``/badwordlist``, ``/links``, ``/badphraselist``- into one new command: ``/blacklist``. This was done to lessen the amount of commands people have to remember, and because it's less messy.

Filtering system reworked
    As mentioned above, all filtering commands can now be done with ``/blacklist``. Along with this update, the names of the lists were changed:

    - "badwordlist" -> "exact-match word list"
    - "bad link list" -> "link list"
    - "bad phrase list" -> "phrase list"

    and the newest addition:

    - "in-word-match word list"

    You can read about how this works :doc:`blacklisting`.

New documentation
    There is new documentation for the bot. It's the website you're on right now! This long-overdue update was made because there was an increasing amount of people getting confused about how to use the bot. You can simply use the bar on the left to navigate the documentation.

There was a lot of other small things fixed, like how anyone could run the ``/unmute`` command without permissions.