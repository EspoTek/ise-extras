**What is it?**

ise-extras is a little add-on package to Xilinx's ISE software for Linux.
I've updated it to work well with modern Linux, specifically Ubuntu 16.04.  It should work with other Linux versions too.
Please note that only ISE version 14.7 on a 64-bit machine t is supported at the moment.  If you want 32-bit, ask.  :)

**Features**
 - Adds shortcuts to the applications menu (with icons!) for the ISE main software, and iMPACT.
 - Adds a "Xilinx Terminal" with Xilinx environment variables activated, for example to run ise_flow.sh.
 - Associates .xise files with the ISE Design Suite.
 - Installs Michael Gernoth's Xilinx USB Platform Cable driver, with modified udev rules so that it's compatible with modern Linux.
 - Modifies your .

**Installation instructions:**
1) First, install ISE 14.7 from Xilinx's website to **/opt/Xilinx**.  You must install ISE to this exact directory, otherwise ise-extras won't work.
2) Download and run ise-extras.deb.
3) Count to 10.
4) You're done.  Type "Xilinx" into your search bar and see the pretty icons.  The Platform Cable (DLC9LP) should also connect and iMPACT should no longer complain about windrvr6 missing!

If you need any changes, you can download the whole repo and alter the source directories.
Please resubmit any changes made so that the community can benefit!
