# Ultimate Kubuntu 16.10

We start our journey with a clean install. 

Do all the updates the system already asks you to do.
Kernel at 4.8.022.

![Screenshots](http://i.imgur.com/qEluksx.png)

Take a look at the various scripts and run the ones you like. Change content if need be.

![Screenshots](http://i.imgur.com/dK4UQUZ.jpg)

Some icons I use in the screenshots.


Using Sardi icons from  http://sourceforge.net/projects/sardi/

![Screenshots](http://i.imgur.com/qYyxDzE.png)

or 

using Surfn icons from https://github.com/erikdubois/Surfn.


![Screenshots](http://i.imgur.com/9UJNvPp.png)



# First steps

Getting these scripts on my just installed system.

	sudo apt-get install git
	git clone https://github.com/erikdubois/Ultimate-Kubuntu-16.10

Go inside the folder and start to install all you need or want.


Do the regular updates first. Start the software-updater.




# Kernel

As described at http://erikdubois.be/ I try to get the latest of everything but on a testpc first mind you! This attitude tends to break things. You have been warned. But the best way to learn about linux.

Go inside the folder and right-click <b>in a blank space</b> to go to the terminal. Now your terminal is opened in this extracted folder.


Type in the terminal


	./update-to-the-last-stable-4.x-kernel-vx.sh 


http://erikdubois.be/change-kernel-easy-way-script/


# Software installation

We start the installation script of all the needed software in the same way as above. First one should be the same on any deb distro. Second one is specific on this distro.

	./bundle-installation-vx.sh


Do not forget to type "./" in front of the name.

The best of them 

	Spotify
	Sublime Text
	Variety
	Inkscape
	Plank
	Screenfetch
	Google Chrome
	...

Or you choose to install the ones you want one by one.


# Aureola conky

Great way to combine beauty and technical information together.

http://erikdubois.be/category/linux/aureola/


# Plank

I tend to use Plank in all my distro's. A nice dock you can theme to pin your most important applications to.

http://erikdubois.be/category/linux/plank/


# Variety 

Variety spices things up. Every minute a new wallpaper. Each time a surprise.

http://erikdubois.be/category/linux/variety/





#What can you do if the script does not execute?

Since I sometimes forget to make the script executable, I include here what you can do to solve that.

A script can only run when it is marked as an executable.

	ls -al 

Above code will reveal if a script has an "x". X meaning executable.
Google "chmod" and "execute" and you will find more info.

For now if this happens, you should apply this code in the terminal and add the file name.

	chmod +x typeyourfilename

Then you can execute it by typing

	./typeyourfilename



------------------------------------
#But that is the fun in Linux.

You can do whatever <b>Y O U</b> want.

Share the knowledge.
------------------------------------



