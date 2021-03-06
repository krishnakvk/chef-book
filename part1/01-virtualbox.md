VirtualBox
----------

So, you've decided to take the plunge. Great!

First we need to get your environment set up. I chose VirtualBox and Vagrant as my playground and I'll start walking you through it here. Virtualbox is a desktop virtual machine environment, and Vagrant is a command line interface that allows you to easily spin up new VMs in Virtualbox (or with other providers).

Go [here](https://www.virtualbox.org/wiki/Downloads) and download the relevant Virtualbox binary for your localsystem (or use your native package manager).  It should be a straight forward install. The last time I installed on my OSX system, it was basically Next-next-next-install. Entered my root password and there we go.

When VirtualBox starts for the first time, it may open a wizard for creating a new virtual machine.  You can dismiss the wizard since we will download a base box in the next step.

Next, I strongly suggest downloading something called iTerm2 if you are on OSX.  Click [here](http://www.iterm2.com/#/section/downloads) and grab the latest stable version.  iTerm2 is a greatly improved terminal emulator that you can use instead of the built-in Terminal on OSX.

_NOTE_: You don't have to use this, on OSX, you can use Terminal but iTerm2 is just better in general, trust me.

Wow, that was...easy, right? Continue on to the next section and things will start heating up.

Move on to [Vagrant](02-vagrant.md)
