Settings and Customization
===============================
This page will teach you how to customize some aspects of the bot.

Customizing the "Message Blocked" embed
---------------------------------------
There are a few commands you can use to customize the behavior of the bot sends when it blocks a message:

``cleanup set``
    Tells the bot to "cleanup", or delete it's message after a specified amount of seconds. Has one parameter: ``seconds``. ``Seconds`` is the amount of time it should wait before deleting the message.

``cleanup remove``
    Removes the cleanup time (if already set), and tells the bot not to delete the embed.

``custom set``
    Allows you to customize the message. You can choose between a plain text or embed form, and change the color of the embed (if you choose embed form). Has one required parameter, and two optional parameters: ``content``, ``is_embed``, and ``color``. ``content`` is what the message will say. ``is_embed`` determines whether or not it will be an embed. ``color`` is the color of the embed, if you chose embed form.

``custom remove``
    Removes the custom message (if set) and switches back to default.

General Settings
----------------
Instead of making commands for all of the small settings, they have been combined into one command, ``settings``:

``settings``
    General command for changing small settings. Has two required parameters: ``setting`` and ``enabled``. ``setting`` is the setting to change (a list will popup when it's run), and ``enabled`` is whether or not the setting should be enabled (turned on)
