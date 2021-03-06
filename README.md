# NoJoy_DI

[![Join the chat at https://gitter.im/joyider/NoJoy_DI](https://badges.gitter.im/joyider/NoJoy_DI.svg)](https://gitter.im/joyider/NoJoy_DI?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/joyider/NoJoy_DI.svg?branch=master)](https://travis-ci.org/joyider/NoJoy_DI)[![Code Climate](https://codeclimate.com/github/joyider/NoJoy_DI/badges/gpa.svg)](https://codeclimate.com/github/joyider/NoJoy_DI)
![DI Logo](https://www.protractus.com/wp-content/uploads/2016/05/injection-300x213.jpg)

A simple to use and feature rich Dependency Injector designed to help managing python classes and variables

The main goal of the DI was to create a simple to use DI that can be used in a pytionic way:

* No xml configuration carp
* No compiling of the DI

Current Status is **Testing/Working*. Please fork and add feature or fix any issues you might run into :)

## Why Dependency injection in python
There are many threads and people on the web stating that you don't need dedicated injection libraries for dynamic languages,
since they offer so many ways to manage the issue. But this is only partially true. Tools are only as good as they are used for.

If you can manage a problem without using DI in an **EASY** way you should stick with using native methods. But sooner or later
 you will find your self in dependency hell never the less. 

## What is Dependency Injection (DI)
Dependency inversion principle is a software design principle which provides us the guidelines to write loosely coupled classes. According to the definition of Dependency inversion principle:

1. High-level modules should not depend on low-level modules. Both should depend on abstractions.
2. Abstractions should not depend upon details. Details should depend upon abstractions.

That is basically it, or even more simple: *Dependency injection means giving an object its instance variables.* Really. That's it.

## Features

Function | Descriotion
-------- | -----------
set_factory | create a factory callable
input | Add constructor arguments for the service
call | add method call with args on a service
set | set attribute the service
injector | 