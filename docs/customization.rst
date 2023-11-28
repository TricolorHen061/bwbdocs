Customization
*************

You can customize how the bot behaves when it blocks a message.

Using ``/custom_embed``
=====================

When you run ``/customize_embed``, you'll be prompted with a popup that has 4 things on it:

Title (PREMIUM ONLY)
    What the title of the embed will be
Embed Description
    What the bot will send when it blocks a message. Sometimes, you'll want the bot to change the embed text depending on the situation. For this, we use "placeholders".

    You can use the following placeholders:
        
        ``{username}`` - The author's username

        ``{tag}`` - The author's tag (the 4 numbers after their #)

        ``{mention}`` - The author's @mention

        ``{content}`` - The contents of the deleted message. If you put a word in parathesis after the word ``content``, then every usage of a blacklisted item will be replaced with that word. For example, if you put ``{content(redacted)}``, then every blacklisted item will be replaced with the word "redacted".

        ``{strikes}`` - The new amount of strikes they have

        ``{strikes_remaining}`` - If you have a limit set up, how many strikes are left until they reach the next limit. 
        
        ``{date}`` - Date of when the message was deleted
        
        ``{blacklisted_items}`` - The blacklisted items found that caused the deletion of the message
        
        ``{next_limit_action}`` - If you have a limit set up, the action of the next limit
        
        ``{next_limit_minutes}`` - If you have a limit set up, the minutes of the next limit
        
        ``{next_limit_strikes}`` - If you have a limit set up, the strikes of the next limit.

Embed Color (PREMIUM ONLY)
    Int value of the color of the embed. Use this webpage to get the int value of the color you want: https://gist.github.com/thomasbnt/b6f455e2c7d743b796917fa3c205f812
Delete Embed After Seconds
    How long the bot should wait (in seconds) before it deletes it's own message. Set to 0 to not delete at all. Set to -1 to not send in the first place.


Example
=======

Example configuration:

.. image:: images/custom_embed_example.png

Resulting embed:

.. image:: images/result_embed_example.png