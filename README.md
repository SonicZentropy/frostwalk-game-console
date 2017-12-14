# Frostwalk Game Console

Frostwalk Game Console is a Unity package by Frostwalk Studio for creating in-game and developer consoles. The framework has been developed to allow for flexible and easy command additions, and it is very easy to make extensions to the framework.

The framework comes with the following features:
* Create individual consoles to allow for multiple different consoles in one project.
* Automatically detects commands. Just subclass the Command class and the GameConsole class will add it to the list. You can, of course, override this behavior.
* Flexible commands. Parse the arguments however you want and control the behavior of the commands however you wish.
* Utility methods to make creating new commands a cleaner and less painful.

The package also comes with an example developer console, which has the following:
* echo and spawn commands.
* Text log display with a scrolling view.
* Keeps previous commands in memory for quick access (with the up arrow on the keyboard).

# To-do
* Command help using ```command ?``` and ```help command```.
* The ```clear``` command.
* Automatic text log clearing.
* Documentation.
* Repository README.

