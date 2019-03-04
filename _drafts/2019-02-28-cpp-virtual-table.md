---
date: 2019-02-28
title: Virtual Table
categories:
  - object-oriented
description: What's all the fuss about vtable & vptr
type: Document
technology: cpp
---




This blog post tries to answer the following questions:

## Next steps
Building a Jekyll site with the default theme is just the first step. The real magic happens when you start creating blog posts, using the front matter to control templates and layouts, and taking advantage of all the awesome configuration options Jekyll makes available.

  
## What is a vtable ? What is a vptr?
## What is runtime polymorphism? define late binding?
## Size of classes - what happens when there are virtual functions in the class  or in it's base class?
## Pure virtual functions, abstract base classes, and interface classes
## Why only virtual destructors ? Why not virtual construction
## Use case of virtual functions
## Examples to show - the order of calling, vtables, object creation
## Multiple inheritance 
## Diamond problem




#### Things To remember
* Every class that uses virtual functions is given its own virtual table. 
* A virtual table ti static array of function pointers 
* vptr is a instance variable not a class variable.

