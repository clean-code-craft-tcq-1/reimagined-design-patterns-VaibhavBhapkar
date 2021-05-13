## Memento Design Pattern

A memento design pattern is a behavioral design pattern.

Without violating encapsulation, capture and externalize an object's internal state so that the object can be restored to this state later.

In simple terms memento design pattern used for restoring an object into its previous state. That means if you want to perform some kind of undo or rollback operation in your application you need to use a memento design pattern for that. 

It uses a Memento object to store its state. The state information in the memento object is not accessible from outside of the object and thus honors encapsulation. This protects the integrity of the saved state data.

## Advantage

It stores the objects state without compromising encapsulation.
Provides a recovery mechanism in case of failures.
It provides a way to maintain history of an object's life cycle.

## Disadvantage

If Originator object is very huge then Memento object size will also be huge and use a lot of memory


## Example

Consider employee state management application where employee designation is going to change and I want to keep track of old designation so in some case I need to revert back employee designation to old this we can achieve through memento design pattern.

https://github.com/VaibhavBhapkar/EmployeeState_MementoDesignPattern
