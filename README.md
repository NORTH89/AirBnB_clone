# AirBnB Clone - The Console

![Image Description](https://cdn.shopify.com/s/files/1/0558/6413/1764/files/Airbnb_Logo_Design_History_Evolution_0_1024x1024.jpg?v=1692808408)

## Introduction

Welcome to the AirBnB clone project! This project aims to build a command-line interface (CLI) for managing AirBnB objects. It is the first step towards building a full web application.


## Project Objectives


The main objectives of this project are:

- Implement a parent class called `BaseModel` for initializing, serializing, and deserializing instances.
- Establish a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> File.
- Create classes for AirBnB objects (User, State, City, Place, etc.) that inherit from `BaseModel`.
- Develop a file storage engine as the first abstracted storage engine for the project.
- Write unit tests to validate all classes and the storage engine.

## Command Interpreter

The command interpreter is similar to a shell, but it is limited to managing the objects of the AirBnB project. It allows you to perform various operations such as creating new objects, retrieving objects from files or databases, updating object attributes, and destroying objects.

## Resources

To successfully complete this project, you may find the following resources helpful:

- [cmd module](https://docs.python.org/3/library/cmd.html)
- [uuid module](https://docs.python.org/3/library/uuid.html)
- [datetime module](https://docs.python.org/3/library/datetime.html)
- [unittest module](https://docs.python.org/3/library/unittest.html)

## Learning Objectives

By the end of this project, you should be able to:

- Create a Python package
- Implement a command interpreter in Python using the `cmd` module
- Understand and implement unit testing in a large project
- Serialize and deserialize a class
- Read and write JSON files
- Manage datetime in Python
- Work with UUIDs
- Use `*args` and `**kwargs` in function definitions
- Handle named arguments in functions

## License

This project is licensed under the MIT License.
