# Day 9
## Goals 
### goal 
work on OOD
### achieve 
work through the OOD concepts on Airtable
### evidence 
be able to go back and refactor my airport challenge with the new principles I've learnt

## How today went
I got to grips with some OOD concepts:
#### Cohesion
- classes should only have 1 responsibility
- everything inside a class should relate to the purpose of it
- e.g. a bank program would have classes for printing a statement, this should not deal with money coming in and out of the account but it should be able to read these
#### Delegation
- one class telling another class to do somethign and the other class encapsulates how to do it
#### Dependency Injection
- a tehnique to help test classes in isolation
- allows a class to use it's real dependency or a double
- you can also inject and double classes
- e.g. 
``` car_double = double :car ```
  ``` car_class_double = double :car_class, new: card_double
  ``
#### Forwarding & Polymorphism
- methods can be forwarded on to other classes when a new class object is made  

