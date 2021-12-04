Blacklisting
====
The \"blacklist\" is a list of items you want Bad Word Blocker to block. For organization, the blacklist has been broken down into 4 sublists:

* "exact-match" word sublist
* "in-word-match" word sublist
* phrase sublist
* link sublist

"exact-match" word sublist
    A list for words. The bot will only block words in this list if it finds, as the name suggests, an **exact** match of the word in the message. For exmaple, if you add the word "test" to this sublist, it will only block "test", not "testing, "tested", or any other variation.

"in-word-match" word sublist
    A list for words. This does the exact opposite of the above list; it blocks if it finds a word **anywhere** in the message. For example, if you add "test" to this list, it'll block "test", "**test**ed", "**test**ing", or even a non-existant word, like "dc44m1l**test**smdlv".

phrase sublist
    A list for phrases. A phrase is defined as a set of 2 or more words. 

link sublist
    A list for website links.