Moderation
==========
While Bad Word Blocker is meant for filtering messages, it has some moderation commands.

Moderation Command List
-----------------------

``/ban``
    Bans a member. Has 1 required parameter, and 2 optional parameters: ``member``, ``reason``, and ``hours``. ``member`` should be the member you want to ban. ``reason`` is why you are banning them. ``hours`` is how many hours before the bot should unban them.

``kick``
    Kicks a member. Has 1 required parameter, and 1 optional parameter: ``member`` and ``reason``. ``member`` is the member you want to kick, and ``reason`` is why you are kicking them.

``muterole set``
    Tells the bot what role it should use when muting people. Has 1 parameter: ``role``. ``role`` is the role you want the bot to use when it mutes people. 

``muterole remove``
    Removes the mute role (if it already has been set with the above command).

``mute``
    Mutes a member. Has 1 required parameter, and 2 optional parameters: ``member``, ``reason``, and ``hours``. ``member`` is the member you want to mute, ``reason`` is the reason why you're muting them, and ``hours`` is how many hours you want the bot to wait before unmuting them.