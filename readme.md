# Zotero standalone installer for Linux

Copyright 2011-2015 Sebastiaan Mathôt

- <http://www.cogsci.nl/smathot>
- <http://www.cogsci.nl/qnotero>

## About

This is an automated installer that will install Zotero standalone on a Linux system. An Ubuntu package based on the installer is also provided (see below).

## Using the installer

Download zotero_installer.sh and run it. This will download Zotero standalone, extract it into /opt/zotero or /home/[user]/zotero, and create a Zotero menu entry.

	wget https://raw.github.com/smathot/zotero_installer/master/zotero_installer.sh -O /tmp/zotero_installer.sh
	chmod +x /tmp/zotero_installer.sh
	/tmp/zotero_installer.sh

## Using the Ubuntu PPA

Ubuntu users can install Zotero standalone from the Cogsci.nl PPA <https://launchpad.net/~smathot/+archive/cogscinl>. The debian package is simply a wrapper around the automated installer, but may be more convenient with respect to updates etc.

To install Zotero standalone from the PPA, please run the following commands in a terminal:

	sudo add-apt-repository ppa:smathot/cogscinl
	sudo apt-get update
	sudo apt-get install zotero-standalone

## License

This installer falls under the General Public License v3. For more information, see the file `COPYING` or visit <http://www.gnu.org/licenses/gpl.html>.
