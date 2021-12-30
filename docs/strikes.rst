Strikes
=======

This page will teach you how strikes work, and how to use them.

What are strikes?
----------------

When a message gets blocked, the author of the message gets a "strike". Essentially, strikes are just a way of keeping track how many times users got their messages blocked. The bot uses this number to punish a user if they get their messages blocked too many times (see "limits" section) below. Moderators can change this number if they wish.

Managing strikes
----------------

To manage a user's strikes, use the ``strikes`` command:

``strikes view``
    View the number of strikes a user has. Has 1 optional parameter: ``user``. ``user`` must be the user whose strikes you want to see.

``strikes change``
    Change the number of strikes a user has. Has 2 required parameters: ``user`` and ``amount``. ``user`` must be the user whose strikes you want to change, and ``amount`` must be the number of strikes to set it to.

Limits
------
You can tell Bad Word Blocker to perform an action to a user- such as banning, kicking, or timeout- when they reach an amount of strikes. These are called ``limits``.

Managing limits
^^^^^^^^^^^^^^^

Limits can be managed with the ``limits`` command:


``limits view``
    View the limits of the server

``limits add``
    Add a limit. Has two required parameters, and one optional parameter: ``amount``, ``action``, and ``hours``. The bot will do the selected ``action`` when the selected ``amount`` is reached. ``minutes`` is how many minutes before it should wait before undoing the ``action`` (only works with ``ban`` and ``timeout```).

``limits remove``
    Remove a limit. Has one required parameter: ``amount``. ``amount`` is the amount of strikes needed to trigger the limit you want to remove.

When a user reaches the ``amount``, the ``action`` will be done on them. The user's strikes will be reset to 0 when they reach the last limit. 