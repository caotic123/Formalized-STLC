# Formalized-STLC

The project is just a formalization of Simply Typed Lambda Calculus using a dependent type theory to proof some structurals properties and properties of the STLC itself.

# Rules of STLC
```
x : σ E T,            x is a constant type of T',             T, x:σ |- e:t                       T |- n : σ -> t T |- k : σ 
T |- x : σ            T |- c:T'                               T |- (λx:σ. e):(σ -> t)             T |- (n k):t
```

# Sources
I am using Type Systems for Programming Languages (Pierce) and Certified Programming with Dependent Types for dependent typed proofs.

#Problems?
Feels free to contact me through camposferreiratiago@gmail.com
... or any plataform you find me out
