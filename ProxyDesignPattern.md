# Proxy Design Pattern

The proxy design pattern is a structural design pattern.

The proxy pattern provides a surrogate or placeholder for another object to control access to it.

The proxy design pattern provides a way to represent the different object and allow to access its functionality through it. Here object representing the functionality is called a proxy object and the object whose functionality is being implemented is called a real subject.

We can also say that the Proxy is the object which is being called by the client to access the real object behind the scene.

The proxy pattern can be used in scenarios like when data can be cached to improve responsiveness. The real subject is in a remote location requires wrapping & unwrapping of requests and making remote calls. These real subjects we can protect by creating proxy objects.

# Advantages

Remote proxy helps to do all heavy lifting of wrapping, unwrapping & making calls to the real objects.

Cache proxy helps in improving application performance.

Protection proxy allows an additional layer of security.

# Disadvantages

Proxy design pattern introduces an additional layer between the client and the real subject.

Additional request forwarding is introduced in this pattern.

# Example

Let’s take an example of cache proxy where we have a remote database to store employees so we need to provide a proxy implementation for it so that roundtrip to the database can be reduced and the performance of the application is going to be improved.

https://github.com/VaibhavBhapkar/EmployeeStore_ProxyDesignPattern
