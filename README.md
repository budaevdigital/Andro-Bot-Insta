# Andro-Bot-Insta

Simply put this instagram bot works with a Raspberry Pi or any computer connected to an android phone. Basically, I send a
series of adb commands to the phone. These command can like pictures from a specific hashtag (in the "Recent" page
of the hashtag). Since all images are different in size, and adb commands can only simulate simple clicks on the phone, in
order to locate the like button (the little heart) I take a screenshot of the current page on the phone and then I use
image recognition (package skimage) to find the coordinates of the like button. 

Indeed, its a very simple mechanism but very efficient and I think that it might have a lot of potential.

I am not a programmer or developer so probably the file I have made its messy and not efficient at all, I hope someone will
be interested in contributing.

This bot works with telegram as you can send commands and notifications of your phone of how the bot is behaving.

If you need more explanation feel free to ask me questions!!
