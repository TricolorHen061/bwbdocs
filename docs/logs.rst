Logs
====
This page will teach you how to set up logs.

What are logs?
--------------
Logs are simply a way for moderators to see when someone got a messaged blocked. When setup, the bot will send an embed to the desired channel when a message is blocked, containing the deleted message, time of deletion, channel, and the author of the message.

Managing log a channel
----------------------
Logs can be managed with the ``log`` command:

``log set``
    Sets a log channel. Has one parameter: ``channel``. ``channel`` is the channel you want the bot to send logs to.

``log remove``
    Removes a log channel (that's already been set). Has one parameter: ``channel``. ``channel`` is the channel you want the bot to stop sending logs to.