# Implementing Cast Calculus for Label Dependent Lambda Calculus

[The final thesis in PDF format is located in the root folder.](https://github.com/leyhline/mastersthesis/blob/master/Implementing%20Cast%20Calculus%20for%20Label%20Dependent%20Lambda%20Calculus.pdf)

## Abstract

Dependent typing is a double-edged sword: One the one hand, it allows for more precise types, hence more guarantees of the program's correctness at compile time while also giving more hints about the program's structure and properties when reading the code. On the other hand, the programmer needs to provide these types in the first place, thus more work is required, especially in volatile code bases.

A combination of label dependent types with gradual typing---allowing dynamic typing in an otherwise statically typed language---is proposed by [Fu et al. [2021]](https://dl.acm.org/doi/10.1145/3485485). Building upon the proposal, this thesis provides an implementation of the *Cast Calculus Label Dependent Lambda Calculus* (CCLDLC) in the Haskell programming language. The *Cast Calculus* introduces dynamic type ★ as well as an explicit type cast notation (M : A ⇒ B). By applying various rules for casts between arbitrary types and the dynamic type these additional constructs integrate into the basic *Label Dependent Lambda Calculus* (LDLC). Extending an existing interpreter, this builds the foundation for full gradual typting.
