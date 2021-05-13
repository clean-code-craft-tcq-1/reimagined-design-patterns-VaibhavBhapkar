## Builder Design pattern ##

Builder Design pattern separates the construction of a complex object from its representation so sam construction process can be used
to create different representations.

Builder design pattern builds complex object using many simple object and using step by step approach the process of constructing complex object should be generic so we can use the same construction process to create different representations.

If we consider laptop as complex object then it builts using many small objects like RAM, Display, USB Port, Keyboard, Battery, Memory, etc. all these small objects assembled together to build a laptop

# Advantages

Clear separation between representation and construction of an object
Better control over the construction process


# Example

If We consider the same employee management application where I want to get the report in excel and pdf so we have two different representations to it. A lot of steps are generating the report so we can generalize that to get the report in different representations.

https://github.com/VaibhavBhapkar/EmployeeReport_BuilderDesignPattern
