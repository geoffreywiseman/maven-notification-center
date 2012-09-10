# maven-notification-center

This is a tiny project intended to integrate *Maven* with *Notification Center* under *OS X 10.8: Mountain Lion* by generating build success and failure messages. It is roughly the same as my [maven growl](http://geoffreywiseman.github.com/maven-growl/) project, which does the same thing using *Growl*. They each have minor unique features because Growl and Notification Center expose unique features.

## terminal-notifier

This project builds on [terminal-notifier](https://github.com/alloy/terminal-notifier), a tool for sending *notification center* notifications from the command-line and/or from Ruby. You can install it as a ruby gem, or as a Mac application bundle, and the means of invoking it changes somewhat based on how you've set it up. I'm using the gem-installed version, but if you've installed it as a Mac application, you'll need to modify the way the script invokes terminal-notifier slightly. If you're having trouble configuring that, get in touch.

## (un)license

This software is unlicensed. See [unlicense.org](http://unlicense.org).

## warranty

There is none. Use it at your own risk. I hope it doesn't burn down your hose.

## support

This is not a commercial supported project. If you're having issues, get in touch (e.g. [twitter](http://twitter.com/geoffreywiseman)). If I have the time and inclination to help, I will. If I can't, it's simple bash scripting, and someone else probably can.
