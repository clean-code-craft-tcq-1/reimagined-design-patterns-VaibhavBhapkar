
## Observer Design Pattern

Observer design Pattern should “Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically”

In the Observer design pattern, the subject maintains the list of its dependents i.e observers and notifies them automatically whenever the state changes by calling any of the methods.

Subject- They are the publishers. When a change occurs to a subject it should notify all of its subscribers.
Observers- They are the subscribers. They simply listen to the changes in the subjects.

## Advantages

quite flexible as we can setup relation between subject & observer
support open/closed principle by allowing to add subscribers
Sending data effectively between object without changing subject or observer

## Disadvantages

Notification will go in random order
If not implemented correctly can cause complexity in code


## Example
Consider the Employee portal example where the company is providing a discount to its employees for its own manufactured products. Here observers(employees) need to get notifications whenever a discounted product is available. This problem we can solve using an observer design pattern.

https://github.com/VaibhavBhapkar/EmployeePortal_ObserverDesignPattern
