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

# What are benefits for developer?
1. Reuse existing solutions whatever language they are written in
2. Generalize your app's functionality to reusable components && reuse && earn money by customizing your component

# What are business benefits?
1. Spend less time implementing functinality you can adopt from existing components
2. Hire component developers to customize their solutions for your needs && save your money && accelerate development
3. Partition functionality to microservices && user whatever language you like

# How does the process look like?
1. Clone && set up LIC platform
2. Search, install, bind, configure components via UI
3. Create your own public/private components and drop to your app
See intoduction video (once it is available)

More about  [language independent components](https://github.com/language-independent-components/docs)
