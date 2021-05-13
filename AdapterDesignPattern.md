## Adapter Design Pattern ##

The adapter design pattern allows incompatible classes to interact with each other by converting The interface of one class into an interface expected by the clients

The adapter pattern helps us to reuse older functionality to build new features in the software. In a nutshell adapter pattern works as a bridge between two incompatible interfaces.

We can choose an adapter design pattern when the class needs to be reused which doesn’t have interface that the client expects.

# Advantage 

More flexibility in design(Extension of feature is possible by reusing the existing logics)
Wrapping a new interface around that of an existing class to meet client needs without disturbing the current logic

# Disadvantages 

code size increase for adding the adaption logic

# Example 

Consider Employee Management application there I am having a function for return employees in JSON format.
Now if the requirement is of getting data in XML format in that case your existing class is adaptee and you need to build an adapter class that meets client requirement

https://github.com/VaibhavBhapkar/EmployeeManagement_AdapterDesignPattern
