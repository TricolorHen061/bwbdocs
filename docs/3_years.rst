3 Years
=======

3 years ago today- on December 20th, 2019- I created what was going to become one of the largest bots on Discord. Since it's inception, Bad Word Blocker has amassed over 6,500 servers and millions of users. This is just going to be about my experiences growing a bot of this size and how this project has changed my life.

In Retrospect
-------------

The Bot
~~~~~~~
I don't exactly remember why I created it. I think it was because I had a problem with swearing in my server, but I'm not sure.

Year 1
~~~~~~
I didn't know what I was doing.

I had jumped into creating this bot with an extremely minimal foundation of programming. I was constantly making errors in the code. For example, I remember one night I unknowingly added a bug that blocked all messages with an emoji in it. 

I didn't know how to use a proper database, so I was storing all information in a plain ``.json`` file (don't worry, absoltely no sensitive information was being saved. Just IDs and blacklists).

At the time, slash commands didn't exist, so all bots were still using prefixes. Bad Word Blocker's prefix was ``badwordblocker-``. Yes, every time you wanted to run a command, you had to type out that. Oh, and the only way modify the blacklist was with the ``add_bad_word``/``remove_bad_word`` commands. So, for example, if you wanted to add ``word1`` to the blacklist, you'd have to type out:

``badwordblocker-add_bad_word word1``

You could only add one word at a time, and you couldn't even view the blacklist. 

Finally, the the filter was just... horrible. Let's say ``word1`` was in the blacklist. Anyone could bypass it by using a capital W. They could also bypass by making it bold, or italics, or literally any other way. I genuinely don't know why people actually used the bot. It was so bad.


Year 2
------
The bot's code was a trainwreck at this point, and I just couldn't continue anymore. In June of 2021, I decided to completely start over from scratch, this time using the TypeScript programming language.


