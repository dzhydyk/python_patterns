# Factories
## The motivation
* Logic of the initializer is not descriptive
* You can not overload with the same sets of args with different names
* Can turn into "optional parameter hell"
* You need wholesale object creation can be outsourced to:
    * A separate method (Factory Method)
    * A separate class (Factory)
    * Hierarchy of factories with Abstract Factory

## Definition

> A component responsible solely for the wholesale creation of objects
