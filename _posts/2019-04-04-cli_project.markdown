---
layout: post
title:      "CLI project"
date:       2019-04-04 23:42:28 +0000
permalink:  cli_project
---


Wow, this was an interesting, fun, frustrating, and whole lot of other emotions project.  Lets start from the beginning.

First challenge was finding an original idea that I had a connection or had a invested interest.  I tossed multiple ideas around from combining two news feeds to finding the worlds best beaches to one stop shop for men's bespoke appearl.  After making a final decision regarding an idea, next was finding the appropriate website to scrape. 

Second challenge, pinpointing a good website to scrape.  To much of my surprise this was a bigger issue than I originally thought.  I wrongfully assumed that the majority of websites follow a good website structure that allows easy navigation. The lack of conformity caused a substantial amount of hours looking for a good website.  I probably estimate 20-50 websites I filtered through per idea.  The struggle offered a great learning experience on the good vs. not so great structured websites.

Third challenge was when I started creating the cli project, I hit a road block scraping thus causing me to pivot to the next idea due to the website structure.  In total, I restarted the project three times.  The issue was mainly due to an attribute not located under the same reference tag to allow the scraping the attribute at the same time as other attributes.  Lets just say practice only makes for improvement.  

Finally, the coding aspect the project.  The main goal was to learn object oriented programming (OOP).  Some of the key concepts are class, object, inheritance, encapsulation, and polymorphism.  

* Class = collections of methods/functions and variables; "blueprint" that defines/stores the data and behavior 

* Object = entity that encapsulates the data and behavior where behavior is the set of methods/functions that operate on the data; 
      -> data that an object encapsulates is hidden from the external world/user
      -> you ask an object to do something for you by sending it a message and it responds
      -> object can inherit data and behavior from another object

* Inheritance = feature in OOP that allows code reusability when class includes a property of another class or  the power of leveraging attributes/behaviours from more senior classes/modules

* Encapsulation = the idea of wrapping data and the methods that work on the data within one unit; used to hide the values or state of a structured data object inside a class, preventing unauthorized parties' direct access to them

* Polymorphism = is the ability of an object to take on many forms and can be accessed through the same interface

That hardest part for me was understanding the relationships.  The main relationships are belongs to, has many, has many of each other, and has many through.  So below are my cliff notes regarding relationships.

First, if a class "has many" of another, it will have an array of the second class in its initialize method.  Second, if one class "belongs to" another, it will have the name of the class that it belongs to listed under attr_accessor. Then set the writer method to equal an instance of the class it belongs to.  Third for "has many of each other" relationships, both of the previous programatic language (belongs to and has many) has to be built into both classes.  Finally, the “has many through” relationship in includes there are at least three classes involved.  A way to recognize a "has many" relationship is it will have an array of the second class in the initialize method.

I only used "has many" and "belongs to" in this project and to be honest I still get confused sometimes.  I wrote this post after completing my project thus it was good vocabulary and concept refresher.  

On to the next project.
