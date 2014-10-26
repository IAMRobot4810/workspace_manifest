IAMRobot FRC team 4810
=======================
Our OpenSource code manifest, for both our team and anyone who wants to pitch in.

Install Cygwin
-------------------
Just Google it and make sure you install everything.

Create the Directories
----------------------

You will need to set up a directory in your build environment.

To create them, open Cygwin and run:

    mkdir bin
    
Now you need to add the folder to your path, that way commands in bin will work. To do that, run:

   echo "export PATH=bin:$PATH" >> .bashrc && export PATH=bin:$PATH


Install The "repo" Command
----------------------

Run the following to download the "repo" binary and make it executable:

    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > bin/repo && chmod a+x bin/repo

You may need to reboot for these changes to take effect. 
Now enter the following to initialize the repository:

    cd C:/WindRiver/workspace


Initialize and Sync The Repositories:
---------------

Run the following command to get the source code:

    repo init -u https://github.com/IAMSeals4810/workspace_manifest.git && repo sync -j8



