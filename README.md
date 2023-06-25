# QLab - A simple QEMU snapshot manager
Do you have multiple qemu instances you run on the terminal? Have many shell scripts for every command? QLab solves this problem with a short and simple bash script that neatly organizes your VM's for you. Temporary boot ups, Permenant storage boots, creating snapshots of an instance to branch off all in one. 
Stick to the terminal!

*Mainly done to practice my bash and awk scripting, but actually useful for managing my messy virtual machines on the terminal*

Make sure to have:
1. Qemu packages, especially `qemu-img`
2. awk
___
## Install & Run
1. Start by cloning the repository:
```
git clone https://github.com/sivabalansm/qlab
```

2. Run the following to start the program:
```
cd ./qlab
chmod +x qlab
./qlab
```

## To Do
- ~~temporary snapshots starting~~
- ~~writing instances to a file~~
- ~~deleting snapshot instances~~
- ~~start as not temporary~~
- creating snapshot files based on instances
- deleting snapshot files
- editing configs


