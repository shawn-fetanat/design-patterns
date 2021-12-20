                                                      Design Patterns


| Design Pattern          |    Type    |                         Description                          |
| :---------------------- | :--------: | :----------------------------------------------------------: |
| Abstract Factory        | Creational | Provides an interface for creating families of related or dependent objects without specifying their concrete classes. |
| Adapter                 | Structural | Allows objects with incompatible interfaces to collaborate.  |
| Bridge                  | Structural | Lets you split a large class or a set of closely related classes into two separate hierarchies—abstraction and implementation—which can be developed independently of each other. |
| Builder                 | Creational | Lets you construct complex objects step by step. The pattern allows you to produce different types and representations of an object using the same construction code. |
| Chain Of Responsibility | Behavioral | Lets you pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain. |
| Command                 | Behavioral | Turns a request into a stand-alone object that contains all information about the request. This transformation lets you parameterize methods with different requests, delay or queue a request’s execution, and support undoable operations. |
| Composite               | Structural | Lets you compose objects into tree structures and then work with these structures as if they were individual objects. Treat individual objects and compositions of objects uniformly. |
| Decorato                | Structural | Lets you attach new behaviors to objects by placing these objects inside special wrapper objects that contain the behaviors. Extend or alter the functionality of objects at runtime. |
| Facade                  | Structural | Provides a simplified interface to a library, a framework, or any other complex set of classes. This makes a complex body of code simpler to use and consume. |
| Factory Method          | Creational | Provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created. |
| Flyweight               | Structural | Lets you fit more objects into the available amount of RAM by sharing common parts of state between multiple objects instead of keeping all of the data in each object. It reduces storage costs for a large number of objects. |
| Iterator                | Behavioral | Lets you traverse elements of a collection without exposing its underlying representation (list, stack, tree, etc.) |
| Mediator                | Behavioral | Lets you reduce chaotic dependencies between objects. The pattern restricts direct communications between the objects and forces them to collaborate only via a mediator object. |
| Memento                 | Behavioral | Lets you save and restore the previous state of an object without revealing the details of its implementation. |
| Observer                | Behavioral | Lets you define a subscription mechanism to notify multiple objects about any events that happen to the object they are observing. |
| Prototype               | Creational | Lets you copy existing objects without making your code dependent on their classes. |
| Proxy                   | Structural | Lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object. |
| Singleton               | Creational | Ensures that a class has only one instance, while providing a global access point to this instance. |
| State                   | Behavioral | Lets an object alter its behavior when its internal state changes. It appears as if the object changed its class. This pattern is close to the concept of finite-state machines. |
| Strategy                | Behavioral | Lets you define a family of algorithms, put each of them into a separate class, and make their objects interchangeable. Enables selecting an algorithm at runtime. Instead of implementing a single algorithm directly, code receives run-time instructions as to which in a family of algorithms to use. |
| Template Method         | Behavioral | Defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps of the algorithm without changing its structure. |
| Visitor                 | Behavioral | A way of separating an algorithm from an object structure on which it operates. A practical result of this separation is the ability to add new operations to existing object structures without modifying the structures. |
