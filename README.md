# Grand Rapids Python Users Group Jupyterfest

https://www.meetup.com/grpython/events/hbbjglyxmbwb/


## Setup

[Tested on Ubuntu 18.04]

    git clone --recurse-submodules --jobs=8 https://github.com/jed-frey/GRPUG_jupyterfest.git
    cd GRPUG_jupyterfest
    sudo make env.host # Needs done once per machine if Python3 and Python3-venv aren't installed.
    make env