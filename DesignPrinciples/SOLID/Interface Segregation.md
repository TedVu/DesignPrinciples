# **Interface Segregation**

## Ideas

"Clients should not be forced to depend on methods that they do not use" - R.Martin -

If we bundle functions for different clients into one interface, we create unnecessary coupling among the clients. If one client causes the interface to change, all other clients are forced to recompiled.

## Solution

Keep interface small and cohesive.

## What's the difference between Single Responsibility and Interface Segregation ? 

Those two are similar principles, they both emphasize the cohesion principle in Object-Oriented Software Design, the difference is that Single Responsibility applies cohesion at the class level while Interface Segregation applies cohesion at the interface level, also Interface Segregation focuses on the granularity of the behaviour, Java  has many interface that has a single method.



