## State Design Pattern

State design pattern is a behavioural design pattern.

State design pattern allows an object to alter its behaviour when its internal state is changing so in a nutshell it allows an object to change its complete behaviour depending on its internal state.

So if you consider some object and maybe there are 2 states called state A & state B now which operation object is going to perform is completely decided based on the states over here.

## Advantages 

This pattern minimizes the conditional complexity i.e. eliminates the need of if/else or switch cases for objects that have different behaviour requirements.

## Disadvantages

Lot of code is required depending on how many states a possible object can be and how many state transitions are required.

## Example 

Consider an employee portal where you have different services like Employee Services Site, HR Service Site, Alumni Portal & Separation Request Site.
This visibility of sites are managed via state of employee i.e(Active & InActive). Active employees having access to Employee Service,HR Service and Separation request and InActive Employees are having access to only alumni portal.
All these changes are handled on state change when an active user raises a separation request.

https://github.com/VaibhavBhapkar/EmployeePortal_StateDesignPattern
