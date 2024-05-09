# SpaceDroneEmbedded
Embedded firmware for the Space Building Drone project.

### Project Overview

This repository serves as a the main codebase for the modular toolchanger v2 and its attachments which use ESP-IDF.

The current ESP-IDF projects are:

- `./ModularToolchanger` for the Modular Toolchanger V2 PCB and attachment system

## Developing

### Installation

Follow the steps [here](https://docs.espressif.com/projects/esp-idf/en/stable/esp32s3/get-started/index.html#installation) to install the ESP-IDF toolchain to begin developing.

### Commands

`idf.py menuconfig # change project settings`  
`idf.py fullclean # wipe current build artifacts`
`idf.py build # build your code`  


### Deploying

`idf.py flash monitor`

To debug code using gdb:

`idf.py gdb # can also use gdbtui or gdbgui`



### Contributing

Clone the repository, and begin coding!  

There should be a 1:1:1 relationship between tickets (issues), branches, and PRs, which means please follow these steps before developing:

1. Get a ticket, either by assigning yourself or getting assigned one 
2. On the ticket, click the "create a branch" button, ensure the ticket number is first (no hashtag), and possibly edit the branch name for brevity.
3. Checkout the branch locally
4. Make any changes the ticket describes, splitting it into multiple commits (with a message describing a change per commit) is OK
5. When you are ready for review, open a PR with your branch, set to merge into the main branch
6. Send the PR link in discord `#firmware` for review, optionally request people as well
7. When your PR has been approved, squash and merge the PR, then delete the branch once you are comfortable the changes are correct and operational


