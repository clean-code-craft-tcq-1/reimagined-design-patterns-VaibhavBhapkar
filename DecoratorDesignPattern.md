
## Decorator design pattern

Decorator design pattern allows us to add the new functionalities to an existing object without altering or modifying its structure
and design pattern acts as a wrapper to an existing class

This design pattern dynamically changes the functionality of an object at runtime without impacting the existing functionality 
of the objects. 
In short, this decorator design pattern adds additional functionalities to the object by wrapping it.

Decorator pattern we can use it in legacy code if we want to extend some feature or when class is sealed.

## Advantage

Add functionality to an existing object dynamically
Flexible design
Support open-closed principle

## Disadvantages 
Dependent on existing functionality

## Example
Consider we have existing employee management which is responsible for returning salary of an employee based on the type of employee i.e permanent or contract. Now requirement came to change salaries based on performance(Basic, Medium, Advanced) in that we can use the decorator pattern to meet this requirement.

https://github.com/VaibhavBhapkar/EmployeeManagement_DecoratorDesignPattern
