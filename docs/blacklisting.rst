************
Blacklisting
************

This page will teach you how to make the bot block words, phrases, and links of your choosing.


.. note::
    If you invited the bot before December 10th, 2021, you may want to populate your server's lists with ``blacklist reset``, since the update changed things.

What is the Blacklist?
======================
The \"blacklist\" is a list of items you want Bad Word Blocker to block. Bad Word Blocker can block 3 things: words, phrases, and links. Each have their own "section" in the blacklist:

- word section
 - exact-match
 - in-word-match
- phrase section
- link section
 
word section
    A section for individual words. `exact-match` refers to words you want the bot to block only if an exact match is found (e.g **test**, not **test**ing, since "ing" is on the end). `In-word-match` is the opposite: it will block words if a word is found, regardless if there is an prefix, suffix, or any other letters on it (e.g **test**, **test**ing, **test**ed) would all work. You'll be able to pick which `match` you want when you add words to the blacklist. 

phrase section
    A section for phrases, a set of 2 or more words. 

link section
    A section for website links.

Using the Blacklist
======================

To add, remove, view, and more with the blacklist, use the ``blacklist`` command:

``blacklist clear``
    Clears all items from a section. Has one required parameter: ``section``. ``section`` must to be the section you want to clear.

``blacklist reset``
    Resets a section to it's defaults. Has 2 required parameters: ``section`` and ``langauge``. ``section`` must be the section you want to reset, and ``language`` must be the verbal language you want the section to be in. English is currently only supported, but more are coming soon.

``blacklist add``
    Adds items to the blacklist. Has two required parameters: ``type`` and ``items``. ``type`` must to be the type  of item (word, phrase, or link) you want to add to the blacklist. The bot will put them in their respective section automatically. ``items`` must to be items you want to add, seperated by commas.

``blacklist remove``
    Removes items from the blacklist. Has two required parameters: ``type`` and ``items``. ``type`` must the type of item (word, phrase, or link) you want to remove. They will be removed automatically from their section. ``items`` must to be items you want to remove, seperated by commas.

``blacklist view``
    Allows you to view the full blacklist via website or downloadable file.

