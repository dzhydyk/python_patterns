# The motivation
* Some objects are simple and can be created in a single initializer call
* Other objects require lot of ceremony to create
* Having an object with 10 initializer arguments is not productive
* Instead, opt for piecewise construction
* Here comes the "Builder" which is sort of API for constructing an object step-by-step


## Definition 
> When piecewise object construction is complicated provide an API for doing it succinctly
