Moderation
==========
While Bad Word Blocker is meant for filtering messages, it has some moderation commands.

Moderation Command List
-----------------------

``/ban``
    Bans a member. Has one required parameter, and two optional parameters: ``member``, ``reason``, and ``hours``. ``member`` should be the member you want to ban. ``reason`` is why you are banning them. ``hours`` is how many hours before the bot should unban them.

``/unban``
    Unbans a member (if they are banned). Has two required parameters, and one optional parameter: ``username``, ``tag``, and ``reason``. ``username`` is the exact username of the member you want to unban. ``tag`` is their tag. ``reason`` is why you're unbanning them.

``clear``
    Clears a specified amount of messages from a channel. Note that it can only remove messages that are two weeks are newer, and you can only clear up to ``99`` at one time. Has one required parameter: ``amount``. ``amount`` is the amount of messages it should delete.

``kick``
    Kicks a member. Has one required parameter, and two optional parameter: ``member`` and ``reason``. ``member`` is the member you want to kick, and ``reason`` is why you are kicking them.

``muterole set``
    Tells the bot what role it should use when muting people. Has two parameter: ``role``. ``role`` is the role you want the bot to use when it mutes people. 

``muterole remove``
    Removes the mute role (if it already has been set with the above command).

``mute``
    Mutes a member. Has one required parameter, and two optional parameters: ``member``, ``reason``, and ``hours``. ``member`` is the member you want to mute, ``reason`` is the reason why you're muting them, and ``hours`` is how many hours you want the bot to wait before unmuting them.

``unmute``
    Unmutes a member (if they have been muted). Has one required parameter, and one optional: ``member`` and ``reason``. ``member`` is the member you want to unmute, and ``reason`` is why you're unmuting them.

