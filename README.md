# AirBnB_clone
AirBnB_clone
HBNB header
https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230211%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230211T081228Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a4d4a79e1ba7af0af58e7b8aeca6f4ade1d4ab469526d019df658f53f1fd8b1f

0x00. AirBnB clone - The console
Status
![image](https://user-images.githubusercontent.com/111267510/218254045-7b8dc96f-1bba-4c3d-af88-217dcbc5dffc.png)


0x00.Table of contents
0x01 Introduction
0x02 Environment
0x03 Installation
0x04 Testing
0x05 Usage
0x06 Authors
0x01 Introduction
Team project to build a clone of AirBnB.

The console is a command interpreter to manage objects abstraction between objects and how they are stored.

To see the fundamental background of the project visit the Wiki.

The console will perform the following tasks:

create a new object
retrive an object from a file
do operations on objects
destroy an object
Storage
All the classes are handled by the Storage engine in the FileStorage Class.

0x02 Environment
Suite CRM terminal python Suite CRM Suite CRM git distributed version control system Github

Style guidelines:
pycodestyle (version 2.7.*)
PEP8
All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0 . Control version using Git 2.25.1.

0x03 Installation
git clone https://github.com/JackTravisKyeyune/AirBnB_clone.git
change to the AirBnb directory and run the command:

 ./console.py
Execution
In interactive mode

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
in Non-interactive mode

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
0x04 Testing
All the test are defined in the tests folder.

Documentation
Modules:
python3 -c 'print(__import__("my_module").__doc__)'
Classes:
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
Functions (inside and outside a class):
python3 -c 'print(__import__("my_module").my_function.__doc__)'
and

python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
Python Unit Tests
unittest module
File extension .py
Files and folders star with test_
Organization:for models/base.py, unit tests in: tests/test_models/test_base.py
Execution command: python3 -m unittest discover tests
or: python3 -m unittest tests/test_models/test_base.py
run test in interactive mode
echo "python3 -m unittest discover tests" | bash
run test in non-interactive mode
To run the tests in non-interactive mode, and discover all the test, you can use the command:

python3 -m unittest discover tests
0x05 Usage
Start the console in interactive mode:
$ ./console.py
(hbnb)
Use help to see the available commands:
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb)
Quit the console:
(hbnb) quit
$
Commands
The commands are displayed in the following format Command / usage / example with output


Authors
Jack Travis Kyeyune
Maureen Thuo
