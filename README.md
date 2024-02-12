## AirBnB_clone
===============
HBNB logo
https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240211%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240211T221935Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7f42bb4076b0dac1019fcbb5d1a85dff7a95db1d40d4fad06af60d517f07c632

## HBNB Project Overview
======================

The goal of the project is to deploy on your server a simple copy of the AirBnB website. You won’t implement all the features, only some of them to cover all fundamental concepts of the ALX Software Engineering higher level programming track.

On completion the web application will be composed of:

A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
A website (the front-end) that shows the final product to everybody: static and dynamic
A database or files that store data (data = objects)
An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)
Final Product
Airbnb clone final product

Steps
=======
The application won't be built all at once, but step by step. Each step will link to a concept

## The console(command interpreter)

The command interpreter will be used to manage the objects of our project like a frontend:

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Update attributes of an object
Destroy an object
the app framework

Files and Directories
=====================
models directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.
tests directory will contain all unit tests.
console.py file is the entry point of our command interpreter.
models/base_model.py file is the base class of all our models. It contains common elements:
attributes: id, created_at and updated_at
methods: save() and to_json()
models/engine directory will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py.

## OOP
============

Create a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel

By Jesse Jackson Sefa Manu
