Automod vs Bad Word Blocker
***************************

Discord has an automod built into Discord itself. This page will break down the differences between it and Bad Word Blocker, and will (hopefully) help you deicde which one is better for you.

**Disclaimer:** I am the creator of Bad Word Blocker, so naturally, I will have bias towards my own bot. Nonetheless, I will try to be as objective as possible, and only focus on the facts.

Features
========
This is how things currently stand:

========================= ====================================== ==================================================
Feature                   Bad Word Blocker                       Automod
========================= ====================================== ==================================================
Blocking                  Block words, phrases, links            Block words, links               
Blocking behavior         Blocks after message is sent           Blocks before message is sent
Strikes                   Supported                              Unsupported
Limits                    Supproted; ban, kick, timeout          Partial support. Can timeout after 1 message block
Blacklist limits          4,000 characters per section           1,000 characters
Can block custom items    Supported; Blocks custom items         Supported; Blocks custom items
Logs                      Supported                              Supported
Preset blacklist          Yes, comes with default items          Yes, comes with default items
Bypassing                 Supported; Channels and roles          Supported; Channels and roles
Admin bypass              Admins don't bypass filter by default  Admins always bypass filter, cannot turn off
Customizable messages     Supported; Can customize messages      Unsupported
Retrive blocked messages  Supported                              Unsupported (unless log channel is setup)
Extra moderation features Supported                              N/A
Support                   Discord support server, this website   Discord support article 
Language support          Mainly English, can block others       Mainly English, can block others
Settings location         Slash Commands                         Server settings
Private servers           Can use Bad Word Blocker               Do not have access to automod
========================= ====================================== ==================================================

Bad Word Blocker generally has more features than automod does. It's important to note that the bot has been around for 3 years, while automod has been around for only 1 month (as of writing this). The Discord team has said they intend to improve automod. It will probably gain more features over time.

In Practice
===========
This is where Bad Word Blocker probably shines the most. In reality, users of your Discord server will try to bypass the filter. Let's say you try to block the word "tree". Members of your server will try to bypass it by messing up the word in many ways, like:
    - t ree
    - tr reee
    - treeeeeeeee
    - t r e e 
    - ttttrrrrrrrrreeeeeeee
    - ttttt rrrrrr eeeee

If you were to add "tree" to Bad Word Blocker's blacklist, it would catch all of those attempted bypasses automatically. With Discord's automod, it's possible to block all of those, but it will take lots of work. You almost certainly run into the `Scunthorpe problem <https://en.wikipedia.org/wiki/Scunthorpe_problem>`_ (false positives) too.

However, Discord's automod has the advantage of being built into Discord. Because of this, automod is able to block a message before it even gets sent- meaning other other people will never see it. Discord bots only get to see messages after they are sent, meaning Bad Word Blocker can only block a message **after** a message is sent. Unfortunately, this means people will probably see the message in the short amount of time it takes for the bot to delete it.

Summary
=======
(in progress)