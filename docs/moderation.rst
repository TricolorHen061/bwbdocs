Moderation
==========
While Bad Word Blocker is meant for filtering messages, it has some moderation commands.

Moderation Command List
-----------------------

``ban``
    Bans a member. Has one required parameter, and two optional parameters: ``member``, ``reason``, and ``minutes``. ``member`` should be the member you want to ban. ``reason`` is why you are banning them. ``minutes`` is how many minutes before the bot should unban them.

``unban``
    Unbans a member (if they are banned). Has two required parameters, and one optional parameter: ``username``, ``tag``, and ``reason``. ``username`` is the exact username of the member you want to unban. ``tag`` is their tag. ``reason`` is why you're unbanning them.

``clear``
    Clears a specified amount of messages from a channel. Note that it can only remove messages that are two weeks are newer, and you can only clear up to ``99`` at one time. Has one required parameter: ``amount``. ``amount`` is the amount of messages it should delete.

``kick``
    Kicks a member. Has one required parameter, and two optional parameter: ``member`` and ``reason``. ``member`` is the member you want to kick, and ``reason`` is why you are kicking them.

``timeout add``
    Puts a member in timeout. Has two required parameters, and one optional parameter: ``member``, ``minutes``, and ``reason``. ``member`` is the member you want to put into timeout, ``minutes`` is how many minutes you want the bot to wait before removing their timeout, and ``reason`` is the reason why you're putting them in timeout.

``timeout undo``
    Removes a member from timeout. Has one required parameter, and one optional parameter: ``member``, and ``reason``. ``member`` is the member you want to remove from timeout, and ``reason`` is the reason why you're removing them from timeout.
