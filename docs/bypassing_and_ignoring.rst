Bypassing and Ignoring
======================
This page will teach you how to allow channels and people with and certain roles to bypass the bot filter.

What are Bypasses and Ignores?
------------------------------
When a role allows people to bypass the filter, it's called `bypassing`. When a channel bypasses the filter, it's called `ignoring`.

Managing Bypasses
-----------------
Bypasses can be managed with the ``/bypass`` command:

``bypass add``
    Allows a role to bypass the bot. Has 1 required parameter: ``role``. ``role`` is the role you want to allow to bypass. Anyone with the role will be able to bypass the bot's filter.

``bypass remove``
    Stops a role (that's already allowed to bypass) from being able to bypass the filter. Has one parameter: ``role``. ``role`` is the role you want to stop being able to bypass the filter.

``bypass view``
    Allows you to view what role are bypassing.

Managing Ignores
-----------------
The process is basically idential to ``bypasses``; ignores can be managed with the ``/ignore`` command:

``ignore add``
    Allows a channel to bypass the bot. Has 1 required parameter: ``channel``. ``channel`` is the channel you want to bypass the bot's filter. 

``ignore remove``
    Stops a channel (that's already allowed to ignore) from being able to bypass the filter. Has one parameter: ``channel``. ``channel`` is the channel you want to stop being able to bypass.

``ignore view``
    Allows you to view which channels bypassing.

