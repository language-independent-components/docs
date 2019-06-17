# Developers tend to solve questions they face raising abscration

## ASM
Assembler seemed to be a good idea of moving from machine codes to predefined instrustions. 
Developes gain some unification and simplification but it was still difficult to write big apps.

## C
C lang introduced new abscrations called procedures and functions. Developers can wrap code to procedures and functions. 
It leads to better readability and composing app from piece of blocks.
But it was still difficult to write big apps due to global variables, etc.

## C++/Java
New abscraction called OOP. 
Wrapping code to object. 
Method/variable access modificators.
Code is composition of objects that interact with each other via calling methods. 
No global state, objects contain variables. 

## Package management (maven, gradle, sbt, pip, npm, composer, etc) && github
Don't implement the wheel. Reusing most common libraries

## DI
Using interfaces and bind some implementations. Solves tight binding issue.

## Microservices (doker, ansible)
Splitting app to multiple independent smaller components

## RestFull services (stripe, shopify, sendgrid, ect)
Don't implement the wheel. Reusing most common functionaliy via REST/HTTP/JSON API

# Rasing abscraction 
Every new abstraction adds extra difficulty to write program but the profit is more valuable therefore we have to accept it.

# What should come next?
What about writing appilcation by combining language independent components a la microservises with public interface binding using platform as DI framework? 

More about  [language independent components](https://github.com/language-independent-components/docs)
