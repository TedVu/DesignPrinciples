# **Dependency Inversion Principle**

## Ideas

- High level modules should not depend on low level modules, both should depend on abstractions.
- Abstractions should not depend on details, details should depend upon abstractions.
- High level modules should not be forced to change because of a change in low level / technology layers.

## Solution

We must avoid client to invoke a concrete type, instead we provide constructor that accepts a generalized type and allows client to pass in the concrete type. This techniques is also known as Dependency Injection, Dependency Injection is a way to inject  some data into your code at runtime usually through some tools with annotation.

