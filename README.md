# AirBnB Clone ― The ALX-Holberton BnB
![Optional Text](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230309%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230309T150400Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5e991c92ebcf686ab5cd541348becb521be5a21b567c7f767985bb7711c05d91 "Banner")
![Page Banner-2](hbnb.png "Banner-2")
## Description of the project
The goal of the project is to create a clone of [Airbnb Website](https://www.airbnb.com/) on my assigned server.

![A picture of Bigsheun](https://avatars.githubusercontent.com/u/112175337?s=64&v=4 "Bigsehun")
![A picture of Chukwuemeka](https://avatars.githubusercontent.com/u/88635898?s=120&v=4 "Chukwuemeka")
___

- The first task is to create a console to manage object
- A website/template using HTM/CSS
- A database retrieval system....
- An API that communicates between the frontend and backend

## Description of the command interpreter
| Commands  | Description |
| ------------- | ------------- |
| ```quit```  | Quits the console  |
| ```Ctrl+D```  | Quits the console  |
| ```help``` or ```help <command>```  | Displays all commands or Displays instructions for a specific command
| ```create <class>```  | Creates an object of type , saves it to a JSON file, and prints the objects ID
| ```show <class> <ID>```  | Shows string representation of an object
| ```destroy <class> <ID>```  | Deletes an objects
| ```all or all <class>```  | Prints all string representations of all objects or Prints all string representations of all objects of a specific class
| ```update <class> <id> <attribute name> "<attribute value>"```  | Updates an object with a certain attribute (new or existing)
| ```<class>.all()```  | Same as all ```<class>```
| ```<class>.count()```  | Retrieves the number of objects of a certain class
| ```<class>.show(<ID>)```  | Same as show ```<class> <ID>```
| ```<class>.destroy(<ID>)```  | Same as destroy ```<class> <ID>```
| ```<class>.update(<ID>, <attribute name>, <attribute value>```  | Same as update ```<class> <ID> <attribute name> <attribute value>```
| ```<class>.update(<ID>, <dictionary representation>)```  | Updates an objects based on a dictionary representation of attribute names and values

## General Execution
The shell works like this in interactive mode:
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

Non-interactive mode:

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
