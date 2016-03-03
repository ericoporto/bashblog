How to configure keyboard on Crunchbang

So this blog is written from my Old EEEPC 701 with 4G SSD. 
I used to run a exotic Gentoo until I've been away from it for 4 months and 
forget how to use it. So I've tried some distros and all and really like Crunchbang!

But it ended, so now I'm using whatever I can use until everything require or too much maintenance
or too much everything. I like this netbook, it was donated to me and I like to keep using it.

Enough, let's get to the keyboard part. Basically you need to edit the keyboard file:

    sudo nano /etc/default/keyboard

And if your keyboard is us intl, modify the file like this:

    # KEYBOARD CONFIGURATION FILE
    
    # Consult the keyboard(5) manual page.
    
    XKBMODEL="pc105"
    XKBLAYOUT="us"
    XKBVARIANT="intl"
    XKBOPTIONS=""
    
    BACKSPACE="guess"

Then restart and everything should work! 
This assumes you have the package `keyboard-configuration` installed.

Tags: troubleshooting
