Some ideas for questions to ask on langdev.stackexchange.com:

- How does "abstraction" relate to type checking? There *are* features in some dynamically typed languages that provide abstraction, but it is also clear that type checking can help enforce abstraction boundaries, etc. A quote from John Reynolds: "*Type structure is a syntactic discipline for enforcing levels of abstraction.*"
- How is the meaning of a program like a board game (*"What is game semantics?"*)?
- How can I track consumable resources at a type-level (*"What are linear types?"*)?
- How can I describe communication protocols at a type-level (*"What are session types?"*)?
- What is "full abstraction" and why is it tricky for the PCF language (*this could motivate the game semantics questions*)?
- How can I implement an interpreter where undefined variables are treated as "uninterpreted symbols"? (*"What is normalization-by-evaluation, aka NbE?"*)?
- How can I determine the possible implementations of a function when I'm just given its type? (*"What is relational parametricity?"*)
- What are logical relations? They seem to be both a proof technique as well as a mathematical object studied in their own right. And both of those aspects are applied to programming language semantics.
- Let's say I have a PL with multiple stages, maybe macro expansion and runtime. How do I ensure at compile-time that programs are "well-staged?" (*A specific instance of "What are modal types?"*)
- What is "type soundness?" How do I know if my type system is sound? (*focus on syntactic type soundness, briefly describe semantic type soundness at the end*)
- How can I build "abstractions" using only functions (*"How do I use the expressiveness of the untyped lambda calculus?"*)?
- What are intersection types?
- How can intersection types be used to give a *semantics* for *untyped* lambda calculus?
- What is a bisimulation and how can it be used to relate two different operational semantics?

The linear types, session types and game semantics questions might all relate to each other.

If the phrasing of any of these is useful to anyone, I would appreciate a brief note saying that my list was helpful!

