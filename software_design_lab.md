1) What do we mean by coupling and cohesion when discussing structured design?

In modular programming independent and interchangeable modules are created to separate the functionality of the program. In terms of structured design coupling is the interdependencies between different modules and cohesion details the relations between functions in a module.

2) What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

Function oriented design is the method in which
the deign is broken down into interacting modules where each modules function is clearly defined. This best describes the bottom-up approach as top-down deals with the overall design as a whole first and gradually breaks it down into smaller components.

3) In which design methodology would a class diagram be most useful?

Class diagrams would be most useful in a bottom-up approach as the structure of the program and the interactions between modules and their functions can be easily mapped out.

4) What are the four pillars of object oriented programming? Give a single-sentence description of each.

Abstraction - The complexity of the code needs to be reduced so only the necessary details of the program are to be shown to the user. 

Encapsulation - A single class should only contain the relevant methods and data it needs.

Inheritance - The properties of the parent class are passed on to the child class that inherits from the parent.

Polymorphism - While child classes inherit behaviours from their parents they can also have unique behaviours defined to them.

5) What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

A strategy design pattern encapsulates the behaviour of an object into distinct strategies that can be used when the behaviour of an object needs to change rather than having the behaviour be fixed.

The main way the implementation would differ between a functional and an object oriented system is that in a functional system multiple implementations of an interface are used whereas, an object oriented system can rely on higher order functions to return a value.

6) Imagine you are creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

I would use object-oriented design to create my new payment system as separate classes can be created to handle each function that is required. The different methods that are needed by the different sectors can then be called upon and used as a single method is not linked or tightly coupled to a particular sector.

The methods that are needed for multiple sectors can be introduced to a particular sector using interfaces. The unique methods that can be created for that particular sector also do not need to be adopted by all sectors.