# isPrototypeOf
Implementation of  Object.prototype.isPrototypeOf(). 

* Description: 
  - This function is an implementation of Object.prototype.isPrototypeOf(). 
  - It checks if an object exists in another object's prototype chain.

* Syntax: 
  - isPrototypeOf(objectPrototype, objectTest)

* Parameters:
  - objectPrototype - the object whose prototype chain will be searched
  - objectTest - the object, which we try to find in the chain  of objectPrototype

* Return value 
  -  A Boolean indicating whether the objectTest lies in the prototype chain
  - of the objectPrototype.
  
* Tests 
  - Automated unit-testing done with simpletest.js library 
