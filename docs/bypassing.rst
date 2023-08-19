*********
Bypassing
*********

Sometimes, you'll want certain roles or channels to bypass the bot's filter.

=================
Using ``/bypass``
=================

You can allow roles and channels to bypass the bot. The ``/bypass`` command has corrosponding subcommands for them:

- ``/bypass role``- Allow everyone with a certain role to be exempt from the filter. Note that if you allow the `@everyone` role to bypass, then the bot will NOT delete messages, and only send a message when a blacklisted item is found. 
- ``/bypass channel``- Allow a channel to exempt from the bot's filter.  


If you want to remove a role or channel from bypassing, use `/bypass manage`.