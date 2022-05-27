************
Blacklisting
************

This article will show you how to manage the blacklist for your server.

================================
Using the ``/blacklist`` command
================================

When you run `/blacklist`, you'll be prompted with a popup like this:

.. image:: images/blacklist_popup.png


.. note::
    When you run it for the first time, you'll see that it'll be filled with defaults. Change it however you want.

As you can see in the image, it's seperated into 4 sections:

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

Just type in the items you want and hit the ``Submit`` button when you're done. Make sure the items are seperated by a comma ``,``. While it doesn't matter, it's recommended that you seperate them with a comma *and* a space, for readability.

======================
Adding non-swear items
======================

While the bot is meant for blocking bad words, links, and phrases, it can also block normal ones if you add them. **Note:** If you are adding non-swear words to the **inexact** match, you HAVE to put an underscore (a ``_``) in front of the good words, in th blacklist.

=============
Blacklist FAQ
=============

**Question**: What does an underscore in front of a blacklisted word mean???

**Answer**: When the English language was being created, I guess the creators thought it'd be funny to put bad words in normal words and phrases. Some of these words, for example, are "mASS", "clASS", "That's a BIT CHeap!", and even "I uSE Xbox" (Look at the uppercase letters). These types of words are everywhere. If the bot based it's filter off of only checking if a bad word is in a message, it'd see all these bad words in innocent messages- meaning a lot of perfectly fine message would get blocked. To accommodate for this, the bot will go through a proccess of determining if the intent of the message is bad. Putting an underscore in front of a word in the blacklist will tell the bot that, if that word is found ANYWHERE in the message, to just block it without going through that whole proccess.


**Question**: Why is nothing getting blocked?

**Answer**: Make sure:

- The bot can see the channel's messages, and has the Manage Message permission. You can just give it Administrator to get rid of this problem entirely

- Make sure your blacklist is not empty. If you're trying to block good words in the inexact-match section, put an underscore in front of the good words in the blacklist

- Click on the bot's profile, and check if there's a green dot by it's logo (meaning it's online). If you see a grey, empty circle, it mean's the bot is offline. If this is the case, please join the support server and tell.


**Question**: If I remove the bot from my server, will the blacklist be deleted?

**Answer**: Yes. Everything, including strikes, limits and bypasses will be deleted. 