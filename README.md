Open Ephys for OS X Yosemite
=================

This repository contains OS X Yosemite (10.10) binary files for the Open Ephys GUI. For the source code, see http://github.com/open-ephys/GUI.

This software is still being developed, so we can't guarantee that anything will work as expected. Don't use it for mission-critical data acquisition unless you've thoroughly tested all the features you'll need.

Installation instructions
-------------------------------

1. Download the files from http://open-ephys.org/gui. Or, if you have Git installed on your machine, you can open a Terminal and clone from GitHub: `git clone https://github.com/com/open-ephys-GUI-binaries/osx-yosemite`. The advantage of cloning is that you'll be able to easily keep track of any updates by periodically running `git pull origin master` from the application directory. Otherwise, you'll have to manually download the software (or build it from source) whenever something changes.

2. Drag the "osx-yosemite-master" (downloaded version) or "osx-yosemite” (cloned version) folder to the location of your choice and rename it "Open Ephys"

3. Double-click the "open-ephys" application file to run the software.

Optional: If you plan on using the GUI with the RHA2000 (analog chip) evaluation board from Intan, you'll need to open a Terminal and run `sudo rm -rf /System/Extensions/FTDIUSBSerialDriver.kext` to properly communicate with the board. This is not necessary if you're using the newer RHD2000 eval board or the Open Ephys acquisition board.


If you run into problems
-------------------------------

1. READ THE [GUI WIKI](https://open-ephys.atlassian.net/wiki/display/OEW/Open+Ephys+GUI). There's a lot of useful information on the "Tutorial" and "User documentation" pages.

2. If you can consistently replicate the problem, [submit an issue](https://github.com/open-ephys/GUI/issues). You'll need a GitHub account for this, but it's worth signing up for one anyway.

3. As a last resort, [get in touch with us directly](http://open-ephys.org/contact)

