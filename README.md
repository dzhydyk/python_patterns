# General Information
Snippets for the SOLID principe's and design patterns implementation in Python

## Structure 
Each of the design pattern would have his on directory with separate readme of "motivation" when and why to use them.
All general information will be in this readme.

## SOLID principe's
- SRP (single responsibility principle) or SOC (separation of concerns):
     > class should have only one general/primary responsibility. You don't want to overload yours objects with to many responsibility. It's hart to manage in future.
- OCP (open-closed principle)
    > Open for extension, closed for modification. When you add new functionality you should add it only via extension but not modification. It's helps not to break stuff.
    To be able to get rid of not scalable extension [Specification pattern](https://en.wikipedia.org/wiki/Specification_pattern) could be used.
-  LSP (Liskov substitution principle)
    > In case if you have some interface that that takes base class you should be able to extend it with a [Derived Class](https://www.techopedia.com/definition/3780/derived-class). Simply write yours classes acknowledging that someone could inherit from it.
- ISP (interface segregation principle)
    >Do not overload your interface with methods because it may end up with definition of unused/unsupported methods for derived classes. 
- DIP (dependency inversion principle)
    > High level classes/modules should not depend directly on low level classes/modules instead they should depend on the abstraction. It's make your code more sustainable.

## The Gamma Categorization 
* Creation Patterns
    >Deal with creation of objects.

    >Explicit (Constructor) vs Implicit (DI, etc.).

    >Wholesale (single statement) vs piecewise (step-by-steep).
* Structural Patterns 
    > Concerned with the structure.

    > Many patterns are wrappers that mimic the underlying class' interface.
    
    > Stress the importance of good API design.

*  Behavioral Patterns

    > They are all different, no central theme.
