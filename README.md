## AirBnB_clone

#Last Updated: 17/05/2024;
#Contributor(s): MyAtlas0, Harbiehorla;



This is the first step towards building a full web application - The AirBnB clone. This first step is very important because we will use the command interpreter with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help to:

> put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
> create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
> create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel.
> create the first abstracted storage engine of the project: File storage.
> create all unittests to validate all our classes and storage engine.



### Description
> The goal of the AirBnB clone project is to deploy on a server a simple copy of the AirBnB website.
> This is the first phase of the AirBnB clone project - the console.
> This repository contains several class files and the command interpreter file.
> The command interpreter acts like a shell. It is used to perform tasks and manipulate object instances. 
> The command interpreter was coded to work in both interactive and non-interactive modes.
> The code functionality was unit-tested with the python unittest module


### Installation
```
git clone https://github.com/vicano-code/AirBnB_clone.git
cd AirBnB_clone
```


### Using the command interpreter
Interactive mode
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```
Non-interactive mode
```
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
```

### Environment
* Language: Python3 (version 3.8.5)
* OS: Ubuntu 20.04 LTS

### Authors
* Olawale Abdullahi
* Peter Aroso
