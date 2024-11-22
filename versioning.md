# Optimality Versioning for G2 Components

The mathematics of G2 is specified as the optimal decision-making process for the well-being of human animals, meaning that all engineering implementations of G2 components  

G2 Channels and all of its major components are specified to approximate particular mathematical optima. This differs from standard engineering practice, where the reference standard is an implementation specification, and it calls for a modification of the semantics of [semantic versioning](https://semver.org/).

The first value, which would be MAJOR VERSION in semantic versioning, takes on only the two values 0 and 1. A value of 1 indicates that the component is complete and optimal and should normally require no further work. Changing from 0.x to 1.0 will only happen once a very high degree of stabilty has been demonstrated.

The second value, which would be MINOR VERSION in semantic versioning, encodes a rough and flexible estimate of how nearly complete and optimal the component is. This value will always be 4 decimal digits, and the value of the first digit will represent the main semantic significance as follows: 
* 9000-9999 indicates that the controlling design specification is complete and the component implementation is both complete and optimal. Components with this version range are on track to attain the major version of 1 once their stability is adequate.
* 8000-8999 indicates that the controlling design specification is complete, while the implementation is complete but suboptimal. 
* 7000-7999 indicates that the controlling design specification is incomplete, but the implementation is as complete as possible. Suboptimalities of implementation may exist. 
* 6000-6999 indicates that the controlling design specification is incomplete, and the implementation is only partially complete. Suboptimalities of implementation may exist. 
* 2000-5999 are very loosely reserved in case they seem useful for something.
* 1000-1999 indicates a strawman design under development.
* 0000-9999 indicates a throwaway experiment that still somehow needs versioning.

