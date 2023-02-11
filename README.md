The AirBnB Clone Project


0x00. AirBnB clone - The console

Project Description

This is the first part of the AirBnB clone project where we worked on the backend of the project whiles interfacing it with a console application with the help of the cmd module in python.

Description of the command interpreter:


The interface of the application is just like the Bash shell except that this has a limited number of accepted commands that were solely defined for the purposes of the usage of the AirBnB website.

This command line interpreter serves as the frontend of the web app where users can interact with the backend which was developed with python OOP programming.

Some of the commands available are:
<<<<<<< HEAD
how

create

update

destroy

count

How to start it

To start the command interpreter, follow these steps:

1. Clone the repository to your local machine using the following command:
git clone https://github.com/koolpedro/AirBnb_clone.git

2. Navigate to the project directory:
cd AirBnB_clone

3. create executable files and folders of the project, 
/console.py : The main executable of the project, the command interpreter.
models/engine/file_storage.py: Class that serializes instances to a JSON file and deserializes JSON file to instances

models/__ init __.py: A unique FileStorage instance for the application

models/base_model.py: Class that defines all common attributes/methods for other classes.

models/user.py: User class that inherits from BaseModel

models/state.py: State class that inherits from BaseModel

models/city.py: City class that inherits from BaseModel


HOW TO USE IT

it works in two ways:
1. interactive 
2. non-interactive

INTERACTIVE MODE: 
the console will display a prompt (hbnb) indicating that the user can write and execute a command. After the command is run, the prompt will appear again a wait for a new command. This can go indefinitely as long as the user does not exit the program.

NON-INTERACTIVE MODE:
the shell will need to be run with a command input piped into its execution so that the command is run as soon as the Shell starts. In this mode no prompt will appear, and no further input will be expected from the user.

EXAMPLES:

$ command1 argument1 argument2
output of command1 with given arguments


$ command2 argument1
output of command2 with given argument

...
=======
>>>>>>> 15e2f6458e0cb33b1eb43676d6918acb78dd084f
