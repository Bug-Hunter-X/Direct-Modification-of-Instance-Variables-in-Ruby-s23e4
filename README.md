# Direct Modification of Instance Variables in Ruby

This repository demonstrates a potential bug in Ruby related to directly modifying instance variables using `instance_variable_set`.  While this approach might seem convenient in some cases, it can lead to several problems including:

* **Violation of Encapsulation:** Directly accessing instance variables breaks the principle of encapsulation, making the class less robust and harder to maintain.
* **Debugging Challenges:**  Tracking changes to instance variables becomes more difficult if modifications happen outside the defined methods.
* **Unexpected Behavior:** It can lead to unexpected behavior if other parts of the code rely on the instance variable being accessed through the defined getter and setter methods.

The provided code illustrates the problem and a potential solution to address this.
