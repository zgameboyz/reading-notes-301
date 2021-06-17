# Reading notes 8

## Functional Programming

Functional programming is programming that is immutable and unchanged if given different parameters into a function. This is done by not allowing variables to be changed. Also removing any random effects. The functional programming also cannot have any way to take in data that is changeable so it cannot read files or take in global variables that are changable. Any sort of counter function will not allow it to be a pure function either. The nice thing about a pure function is that it will always have the same result when tested.

Immutability is the inability for the function or code to be changed. Pure functions with Immutability creates referential transparensy. Referential transparency refers to when a function yields the same result with the same input.

## Modules

Modules allow designated functions to be exported and used in other javascript files. When you require() a module it will let you use it in other files. To make a module available you have to module.exports = then the thing you want to make available. 