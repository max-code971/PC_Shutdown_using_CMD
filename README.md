# In this repository, I will tell you how to turn off the PC using the CMD console, or create a shortcut to turn off the PC.

To shut down a computer using the Command Prompt (CMD), you can use the "shutdown" command with the appropriate parameters. Here's an example of the command:

```sh
shutdown /s /t 0
```

- This command will initiate an immediate shutdown ( "/t" 0 sets the time to zero seconds ) with the "/s" flag indicating a shutdown operation.
Here are the steps to perform a shutdown using the CMD console:

1. Press the Windows key on your keyboard.
2. Type "cmd" (without quotes) in the search bar and press Enter. This will open the Command Prompt.
3. In the Command Prompt window, type the shutdown command:

```sh
shutdown /s /t 0
```

4. Press Enter to execute the command.

- After executing the command, the computer will begin the shutdown process immediately. Make sure you save your work and close any open programs before running this command, as it will initiate an immediate shutdown without any further prompts.

<hr>

## Now we will create a shortcut to turn off the PC:

1. Right-click on an empty area of your desktop and select "New" from the context menu.
2. Choose "Shortcut" from the sub-menu. This will open the "Create Shortcut" wizard.
3. In the "Type the location of the item" field, enter the following command:

```sh
shutdown /s /t 0
```

- This command will initiate the shutdown process immediately ( "/t" 0 sets the time to zero seconds) with the "/s" flag indicating a shutdown operation.

4. Click "Next" to proceed.
5. Give your shortcut a name, such as "Shutdown" or any other descriptive name you prefer.
6. Click "Finish" to create the shortcut.

- Now, whenever you double-click on this shortcut, it will execute the shutdown command, initiating a normal shutdown process.
Remember to use this shortcut responsibly and ensure that you save your work before initiating a shutdown.
