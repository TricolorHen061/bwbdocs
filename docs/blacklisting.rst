************
Blacklisting
************

This article will show you how to manage the blacklist for your server.

================================
Using the ``/blacklist`` command
================================

When you run `/blacklist`, you'll be prompted with a popup that has 4 slots.


.. note::
    When you run it for the first time, you'll see that it's already filled with the defaults. Feel free to change it to however you want.

It's seperated into 4 parts:

Exact-match words
    Words that will be blocked only if they are found *exactly* as they are written in the blacklist. So for example, if you add the word "suck" here, it will *only* block "suck". Not "sucked", "sucking", "sucker", or any other forms.

Inexact-match words
    Opposite to the above section. Words that will be blocked if they found *exactly* or *inexactly*. So for example, if you add the word "screw" here, it will block "screw", "screwed", "screwing", and all other forms. It will also try to detect attempted bypasses by purposely mispelling words, adding symbols, and/or others.

Phrases
    This section is for when you want to block a *group* of 2 or more words, instead of individual ones. You can add phrases like "screw you" here, for example.

Links
    For website links. Note that they have to start with either ``http`` or ``https``, or the bot won't count it as a valid link.

====================
Editing the sections 
====================

Editing the sections are very straitfoward. Just type in the items you want and hit the ``Submit`` button when you're done. Make sure the items are seperated by a comma ``,``. While it doesn't matter, it's recommended that you seperate them with a comma *and* a space ``, ``, for readability.


======================
Adding non-swear items
======================

While the bot is meant for blocking *bad* words, links, and phrases, it can also block normal ones if you add them.

.. warning::
    If you are adding normal words to the ``Inexact-match`` section, you have to put an underscore ``_`` in front of the word.