README - ESP Package Manager (EPM) 5.0
--------------------------------------

WHAT IS EPM?

    EPM is the software packaging tool that we use at Easy Software
    Products.  It is a simple tool that generates software and patch
    distributions in various formats, including:

	- AIX software packages ("installp")
	- AT&T software packages ("pkgadd"), used by Solaris and others
	- BSD packages ("pkg_create")
	- Compaq Tru64 UNIX ("setld")
	- Debian Package Manager ("dpkg")
	- HP-UX software packages ("swinstall")
	- IRIX software manager ("inst", "swmgr", or "tardist")
	- MacOS X software packages ("name.pkg")
	- Portable (installation and removal scripts with tar files)
        - Red Hat Package Manager ("rpm")
	- Slackware software packages ("name.tgz")

    EPM also includes graphical "setup" and "uninstall" programs
    that can be provided with your distributions to make
    installation and removal of more than one package a snap.


WHY ANOTHER SOFTWARE PACKAGING TOOL?

    We developed EPM because we are tired of developing and
    testing N different software distributions, each with their
    own input files and setup requirements.

    Also, when we looked at software distribution on Linux we
    saw that there are at least four different "standard"
    distribution formats, and none of them are compatible with
    the other.  Clearly we needed something that could be used
    for all platforms *without* requiring special software
    packages on the customer's system!


HOW DO I COMPILE EPM?

    See the file "INSTALL" for more info on that.


HOW DO I USE EPM?

    Please look at the EPM manual; preformatted copies are
    included in the "doc/epm-manual.html" and
    "doc/epm-manual.pdf" files.

    An example EPM software list file is provided with this
    distribution in the file "epm.list".


DO I HAVE TO PAY TO DISTRIBUTE SOFTWARE USING EPM?

    No!  EPM is free software and any installations you create are unencumbered
    by licensing of any kind, not even the GPL.


WHAT'S NEW IN EPM?

    See the file "CHANGES" for change information.


REPORTING PROBLEMS

    Report all problems and submit all patches using the bug reporting form at:

        http://www.epmhome.org/str.php


OTHER RESOURCES

    The official home page for EPM is here:

        http://www.epmhome.org/

    Easy Software Products also maintains a news server for the discussion of
    ESP and ESP-sponsored software.  The news server is:

        news.easysw.com

    If you don't have NNTP access from your systems, point your web browser at
    the following URL:

        http://www.epmhome.org/forums.php


COPYRIGHT AND LICENSE INFO

    EPM is copyright 1999-2010 by Easy Software Products. All rights reserved.

    This program is free software; you can redistribute it and/or modify it
    under the terms of the GNU General Public License as published by the Free
    Software Foundation; either version 2, or (at your option) any later
    version.

    This program is distributed in the hope that it will be useful, but WITHOUT
    ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
    FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for
    more details.
