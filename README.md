# Linux-Commands
This project, "Working with Linux Commands", aims to simplify using the Linux shell by minimizing mouse usage. It follows the book "The Linux Command Line" by William Shotts, guiding users through essential commands. The goal is to improve proficiency in command-line navigation and system management.


# What is the SHELL?
When we talk about command we are not usually refer to the shell consept. The Shell is the program in our PC/Laptop that takes keyboard commands and carry out these to our Operating System and returns the answer. Shell also might be called "Terminal".


### How to open a Shell on Linux OS?
Well to open a Terminal we can use mouse and go to menue and find Terminal or As I said we will try to less use our mouse and open a terminal for this reason we need to press <span style="color: red">** ALT + Ctl + T **</span>. Welcome to the Terminal Prompt ":)". If we enter "lfjsdjfasjf" we can see the response from Shell: "command not found" which means it doesn't really exist and if we just press up arrow we can see the command that had entered "lfjsdjfasjf" so this means the TERMINAL has its own memory and it is called - Command History.


## A FEW WORDS ABOUT MICE AND FOCUS
While the shell is all about the keyboard, you can also use a mouse with your
terminal emulator. A mechanism built into the X Window System (the underly-
ing engine that makes the GUI go) supports a quick copy-and-paste technique.
If you highlight some text by holding down the left mouse button and dragging the mouse over it (or double-clicking a word), it is copied into a buffer maintained by X. Pressing the middle mouse button will cause the text to be pasted at the cursor location. Try it. Don't be tempted to use CTRL-C and CTRL-V to perform copy and paste inside a terminal window. They don't work. These control codes have different meanings to the shell and were assigned many years before the release of Microsoft Windows.
Your graphical desktop environment (most likely KDE or GNOME), in an effort to behave like Windows, probably has its focus policy set to "click to focus." This means for a window to get focus (become active), you need to click on it. This is contrary to the traditional X behavior of "focus follows mouse," which means that a window gets focus just by passing the mouse over it. The window will not come to the foreground until you click on it, but it will be able to receive input. Setting the focus policy to "focus follows mouse" will make the copy-and-paste technique even more useful. Give it a try if you can (some desktop environments such as Ubuntu's Unity no longer support it). I think if you give it a chance, you will prefer it. You will find this setting in the configuration program for your window manager.
