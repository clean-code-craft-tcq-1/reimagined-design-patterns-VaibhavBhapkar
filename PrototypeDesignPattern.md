
# Prototype Design Pattern

The prototype design pattern is a creational design pattern.

This pattern gives us a way to create a new object from the existing object that means it clone the existing object into a new object with its data in it. It avoids the expensive operation of the creation of a new object. This pattern mostly used when object creation is an expensive operation.

Prototype or cloning can be achieved using two ways shallow copy & deep copy.

Shallow Copy- In this type, all the non-static fields and value types are copied to the new object and for reference type, the only reference will be copied i.e. both original and cloned object will point to the same reference so change in any one of them will reflect in both objects.

Deep Copy- In deep copying all and everything from the source object is copied to the cloned object, thus any changes made in either of them do not affect any of these objects.

If you are using an assignment operator for object creation then the reference is copied and change in any of the objects will reflect in both.

# Advantage

Eliminates the potential expensive overhead of initializing an object.

Optimizing the code where multiple objects are having similar data.

# Disadvantages

Difficult to implement in already existing projects as a class must have an implementation of clone() methods.Chances of using different objects internally.

# Example

For this pattern, let’s consider we need to build a salary structure in the organization according to education degree and from college tier so we have different parameters to define salary structure.
Creating separate objects for the individual degree will lead to a lot of object creation which we can avoid using this pattern.

https://github.com/VaibhavBhapkar/EmployeeClone_PrototypeDesignPattern
