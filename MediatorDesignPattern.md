## Mediator Design Pattern

Mediator design pattern is behavioral design pattern.

Mediator design pattern defines an object that encapsulates how a set of objects interact. It allows multiple objects to communicate with each without knowing each other's structure.

This pattern is used to reduce communication complexity between multiple objects.This design pattern provides a mediator object and that mediator object normally handles all the communication complexities between different objects.

The Mediator object acts as the communication center for all objects. That means when an object needs to communicate to another object, then it does not call the other object directly, instead, it calls the mediator object and it is the responsibility of the mediator object to route the message to the destination object.

Without a mediator object if communication is happening between different objects then architecture is tightly coupled by adding mediator pattern architecture will be loosely coupled.

## Advantages

Loose coupling
Easier Reuse due to fewer dependencies
Single Responsibility Principle: The services don’t have any logic to call other services, therefore they only do one thing.
Open/closed principle: Adding new mediators can be done without changing the existing code.


## Disadvantages

Centralized control to mediator object


## Example

Consider employee communication portal where employees needs to communicate with other employees this problem is solved using mediator design pattern
In an example if employee is sending some message with the help of mediator we can this to other employees.

https://github.com/VaibhavBhapkar/EmployeeCommunicationPortal_MediatorDesignPattern


