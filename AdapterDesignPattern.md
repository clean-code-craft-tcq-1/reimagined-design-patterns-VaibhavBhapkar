## Adapter Design Pattern ##

The adapter design pattern allows incompatible classes to interact with each other by converting The interface of one class into an interface expected by the clients

The adapter pattern helps us to reuse older functionality to build new features in the software. In a nutshell adapter pattern works as a bridge between two incompatible interfaces.

We can choose an adapter design pattern when the class needs to be reused which doesn’t have interface that the client expects.

Adapter pattern and decorator pattern looks similar but the difference here is adapater pattern uses different interface while decorator pattern enhances the existing inteface.

# Advantage 

More flexibility in design(Extension of feature is possible by reusing the existing logics)
Wrapping a new interface around that of an existing class to meet client needs without disturbing the current logic

# Disadvantages 

code size increase for adding the adapter logic

# Example 

Consider Employee Management application there I am having a function for return all employees in JSON format.
Now if the requirement is of getting data of all employees in XML format in that case your existing class is adaptee and you need to build an adapter class that meets client requirement

https://github.com/VaibhavBhapkar/EmployeeManagement_AdapterDesignPattern
