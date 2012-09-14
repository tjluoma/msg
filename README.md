# msg README

This is a zsh function that I use a lot in other shell scripts. The purpose is to alert me to things using
[growlnotify][] in addition to 'echo'.

It also sends a message to 'echo' including a timestamp, and logs that output as well.

You can see an example of the output here:

<img style="border: outset 1px grey" alt='[screenshot of msg in action]' src="https://raw.github.com/tjluoma/msg/master/msg.jpg" width="586" height="171" border="0" />

*(note that '@air' refers to the hostname of my computer.)*

I have included this on github because a lot of my other scripts use it, and I didn't want to have to keep explaining what it was.

If you *don't* want to use `msg` you can just replace all instances of it with `echo`.

[growlnotify]: http://growl.info/extras.php#growlnotify


