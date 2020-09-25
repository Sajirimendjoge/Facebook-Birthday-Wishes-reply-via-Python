Facebook Birthday Response
=========================
Python script that automatically thanks all users and like their birthday wishes on your timeline


How to use
------------
Configure parameters and run the script:
- bday: your birthday as in the following datetime(year, month, day[, hour[, minute[, second[, microsecond[, tzinfo]]]]])
- access_token: Generate one at https://developers.facebook.com/tools/explorer
- like: set true to like posts on your wall
- comment: set true to comment thank you
- message_set: the list of messages from which you want a random message to be selected
- use_filter: if false, replies to every message. Make it false if you are sure every wish posted on your wall is a birthday message
- bdaywords: keywords to respond to. Comment only on posts containing at least one of these words
- proxy settings: proxy settings if you are behind a proxy server


Support
-------
If you are having issues, contact me directly.

License
-------
This project is licensed under the terms of the MIT license. See LICENCE.txt for details


-------
Idea inspired from a post on 
https://github.com/rishirdua/facebook-birthday-response
The code in that post uses FQL which is deprecated after v2.1. This implementation uses Facebook Graph API.
