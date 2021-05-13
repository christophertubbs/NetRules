# NetRules
A general purpose object oriented business rule engine for .Net

## Why?

Companies like to offer configuration software to allow external customers to configure their products for production time behavior.  Purpose built systems have been constructed using various technologies, but there isn't a strong contender for a general purpose, reusable engine.

## Goals

- [ ] Allow generic object binding - use of NetRules should allow integrators to annotate classes, functions, and properties of preexisting software and libraries with the ultimate aim of allowing NetRules to load and manipulate them at runtime
- [ ] Wrap the library in C# - C# will be the primary language to make it easier to integrate with
- [ ] Define and run the rules via F# - actual rules should be able to be drawn up and run without compilation

A web server and client for drag and drop configuration will eventually need to be created, aimed at the Microsoft stac
