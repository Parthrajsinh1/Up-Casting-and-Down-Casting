# Up-Casting and Down-Casting

A simple demonstration of upcasting and downcasting in Java.  
This repository contains example code illustrating how casting works in object-oriented programming.

---

## Overview

This project shows basic examples of:

- **Upcasting** — treating a subclass instance as an instance of its parent class.  
- **Downcasting** — casting a parent class reference back to a subclass type (with safety considerations).  

It’s a learning/demo codebase rather than a production library.

---

## What Is Upcasting & Downcasting?

- **Upcasting**: Converting a subclass type into a superclass type. This is safe and usually implicit.  
- **Downcasting**: Converting from a superclass reference back to a subclass type. This must be explicit (using a cast) and can fail at runtime (`ClassCastException` in Java) if the object isn’t really of that subclass.

---

## Repository Structure
~~~
Up-Casting-and-Down-Casting/
├── upcasting/ ← code examples for upcasting
├── downcasting/ ← code examples for downcasting
└── README.md ← this file

~~~

## Contributing

You can contribute by:

- Adding more examples (interfaces, safe casting with instanceof)

- Documenting more use cases

- Adding test cases

- Improving code organization
