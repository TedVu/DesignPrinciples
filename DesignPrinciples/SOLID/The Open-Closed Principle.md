# The Open-Closed Principle

## Ideas

- Software entities (classes, modules, functions, etc,) should be open for extension, but closed for modification.
- Modification can be understood as modification that affects client's code.
- We try to design a class such that it can extended later on.

## Polymorphic behaviour

- Suppose we have a hierarchy D extends C, C extends B, B extends A if we call an overidden method in A from a D object we will get an error as the constructor is called up the chain while the methods is called at the most specific client declaration type (D in this case).

