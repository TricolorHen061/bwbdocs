Limits
======

What are limits?
----------------

Limits put a "cap" on the amount of strikes a person can get before something happens.

Creating a New Limit
--------------------

Use the ``/limit add`` command to add a new limit.

A limit takes two things at a bare minimum: an `amount` and an `action`. After the amount of strikes has been reached, then the action will be done.

You can currently choose from the following ``action``s:

- ``ban``- Ban member from the server

- ``kick``- Kick member from the server

- ``timeout``- Timeout a member

- ``Mute Role``- Give the member a certain mute role

Additionally, you can set a time limit, or a ``duration``, that will tell the bot when to remove the punishment.

Managing Limits
---------------

You can view/delete limits by running the ``/limits manage`` command.
