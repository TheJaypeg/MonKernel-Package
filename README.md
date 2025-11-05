# MonKernel-Package
A comprehensive set of functions I created that work in tandem to form a shell environment for myself, it is able to automatically detect/wrap/organize peripherals by type. It has a network stack that allows for domain controlled systems with their Mainframe counterpart, it has system-wide non-blocking DFPWM that automatically maps itself to one or multiple speaker sources when detected.

- Geometrically Aware Special Print Functionality
  This Kernel creates windows to render everything you see on the screen after the very initial bootup sequence, the terminal window itself and any monitors have window objects created and stored in memory for use later.
  sPrint(Special Print) replaces write AND print in and all-in-one geometrically aware text wrapper.

It has it's own RC 1-on-1 chat system for communication even if the minecraft chatbox is disabled.
It is able to display information from an environment detector across an infinte amount of monitors.
There is a music player. It does not read floppies instead it appends from an internal folder where I placed .dfpwm's already. You are free to add/remove your own as you wish. The program simply lists all .dfpwm's in the directory.
I tried to make it immersive.

When you run 'start xserver' the system automatically creates the needed subdirectory and allows you to create your own users/passes.conf files on the fly during initialization. Any machine running the kernel with a modem attached (wired only) can use the mainframe (through xLogin) to open doors or open a multishelled CraftOS environment.

All machines running this kernel have the ability to become dedicated redstone locks, press L for the lockmenu to setup.

WHEN RUNNING FOR THE FIRST TIME
- Have all your peripherals connected (it doesn't have to be before the machine turns on, just before you run 'devInitAll' from xCommand (C Key)
- When you run devInitAll, it saves everything it detected in multiple .conf files that upon reboot - reappends the peripherals and makes them immediately available again.
- After this step, you never have to run devInitAll again unless you change the peripheral configuration.

THERE IS A LIMIT OF 8 SPEAKERS PER COMPUTER.
(I cannot change this, it seems to be a CC Tweaked limitation when running multiple speakers in parallel)
  
KEY LEGEND
- V for changing the Audio Subsystem volume on the fly
- S for ShellEmu (running shell programs as normal from within the kernel
- L for LockMenu (setting up dedicated Redstone Door Locks)
- C for xCommand (the main menu)
- X for xServer commands (remote panicing of machines)
- M for MultiMonitor config menu
- T enables/disables ScreenCopyMode
- D enabled/disables DisplayHost on the fly

Control Key Mode LEGEND
- leftCtrl or rightCtrl + L = Locks the System immediately if a password was set in Lock Menu
- leftCtrl or rightCtrl + G = Resets GPS Navigation Coordinates to blank
