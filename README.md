# bridge
Explicit and implicit mapping across distinct layers of abstraction

For a variety of reasons, bridging as we know it in the Executable UML / Shlaer-Mellor community, seems to be better handled in its own distinct domain.

### Reason 1

The semantics required to define implicit and explicit bridging as they are used with Shlaer-Mellor models is not necessarily unique to those types of models.

### Reason 2

The various kinds of elements that can be bridged, Bridgeable Elements, are, well, various. One of the best signs that you have hit a domain boundary is a generalization relationship with an unfixed and varied number of subclasses.

### Reason 3

The Shlaer-Mellor metamodel is greatly simplified by factoring out a system of bridge specification

### Reason 4

One can imagine a variety of approaches to bridge specification, so why compromize an otherwise solid metamodel by wrapping it around a single, and possibly bad, bridge specification system?      
