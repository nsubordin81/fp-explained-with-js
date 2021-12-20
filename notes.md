# Notes From Blog Series 'Things I Wish Someone Had Explained About Functional Programming' by James Sinclair

# Faulty Assumptions 

## Learning Functional Programming is like learning a new language

bottom line, functional programming is a paradigm shift from imperative or Object Oriented Programming. The article describes well how learning a language vs. a paradigm are different, main point being that learning another language in the same paradigm doesn't challenge what you've learned about the 'right' way to do things as often. Learning a new paradigm means accepting contradictory approaches between paradigms which is more mind stretching and truly new. It can feel like going backwards. 

Sinclair mentions that they prefer to lay out concrete examples and learn from the bottom up, but that big picture understanding is a vital thing to eventually grasp. So that is how the blog series is more or less laid out, to provide simple examples and then tie it to the bigger picture, and to get terminology straight. 

## The Article Focus

This post series focuses on 3 related concepts in functional programming that the post author found to be related enough that they were often confused in the broader discussions they had used to try and make sense of functional programming. these three are: 
 
1. Algebraic structures;
2. Type classes; and
3. Algebraic data types.

So we will go through each of these in the notebook, following along with summaries of the post. 

### Algebraic Structures

Fancy definition distilled (with some help from wikipedia's universal algebra page): 

``` 
Algebraic structures are a thing. They can also be called algebras.
They are a thing that contains some set, let's give it a name, A.
They also contain collections of operations on that set, on A.
Another useful term to mention here is rank or arity of an algebra. If you take all of the operations that are part of that algebra, the maximum number of arguments that can be taken by any of its operations is that algebra's arity or rank. 
```
Sinclair makes the point next that even though talking about algebraic structures when talking in the broader community about functional programming would be useful because that is core to the theory behind it, most people only talk about specific algebraic structures like 'monad', 'moniod', 'functor', etc. 

#### Nuts and Bolts

There is a javascript spec for algebraic structures called Fantasy Land that will be used in this series. This assumes class and object based algebraic structure, this is not how all languages do algebraic structures. 

There are Type signature requirements
There are laws for different structures





