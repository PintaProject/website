# Installing Pinta

Pinta can be installed on Linux, Mac or Windows. Due to this, there are multiple ways to install Pinta based on what you are using as your operating system.

This document will show you the multiple ways to install Pinta.

## Linux

### Pinta Repository

Pinta is available in a software repository, or PPA. In an Ubuntu-based Linux distribution it is very easy to add a new PPA to your software repository lists to install new software or provide system updates.

*For more information on PPA's [click here][1].*

After installing a repository one of the easiest ways to install almost any application is to use the Ubuntu Software Center. If you already have this in your repository list continue to Installing Pinta via the Ubuntu Software Center.

Copy, one line at a time, to install the following PPA to get the latest stable release and paste them in a terminal and press ENTER:

*Is the Ubuntu terminal something new to you? [Click here to learn more on how to use the Ubuntu terminal][2].*

**Ubuntu Maverick, Natty & Oneiric**

` sudo add-apt-repository ppa:pinta-maintainers/pinta-stable/ubuntu `

Once you've installed the above PPA, then you must update you system with their package lists. Run the following command:

`sudo apt-get update`

Once you have a PPA setup with Pinta on it and have updated your package list, you are now ready to install Pinta.

**Ubuntu Precise**

`sudo add-apt-repository ppa:pinta-maintainers/pinta-stable`

Once you've installed the above PPA, then you must update you system with their package lists. Run the following command:

`sudo apt-get update`

Once you have a PPA setup with Pinta on it and have updated your package list, you are now ready to install Pinta.

### Installing Pinta via the Terminal

After the PPA has been setup (see above), you can install Pinta.

You can easily install Pinta from the terminal with this command:

`sudo apt-get install pinta`

### Installing Pinta via the Ubuntu Software Center

Once you have the PPA's setup and your system updated with their package list, now we can install Pinta via the Ubuntu Software Center:

* Launch the Ubuntu Software Center
* Search for "pinta"
* Click the 'Install' button to install Pinta.
* Once it is installed you can now use Pinta. Navigate to: Menu > Graphics > Pinta (This is the default location in most menu systems. Your results may vary.)

## Using the Tarball

A tarball is like a ZIP file. It is a single file with many files inside it. Like a ZIP file, it has to be extracted before you can use the files in them.

First, you must download the tarball. Head on over to the [Download][3] page and click on the Download link under Tarball. Download the file where ever you'd like, just be sure you remember where.

Second, we need to extract it. You can either use your mouse to right-click on the Tarball file and select 'Extract here' or you can use the terminal if you are more comfortable with that.

Here is the command to extract the files via the terminal, be sure you are in the same folder as the tarball:

`tar -zxf pinta-VERSION.tar.gz`

[1]: http://help.launchpad.net/Packaging/PPA
[2]: http://beginlinux.com/twitter/1094-the-beginners-guide-to-the-ubuntu-terminal
[3]: http://pinta-project.com/releases
