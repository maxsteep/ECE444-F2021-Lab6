# Maxim Stepanov
## This repo is a replay of the instructions at the https://github.com/mjhea0/flaskr-tdd repository

# Test cases
Academic attestation:
Please note that the flask-oauth implementation was made by closely following a tutorial found online.
https://github.com/ECE444-2021Fall/project1-education-pathways-group-5-sojourner/commit/f8495e75fa82c27799b44c32b925f7ad0032aa96,
as stated on the github comment.

The above is the only meaningful addition that I have contributed thus far.
The decision to implement a tutorial guide was undertaken due to the fact authentication
is an external module and relies on Google services and a multitude of additional services, packages, and components.

No other native self developed methods was added to the functionality as of yet, due to the fact
that the React frontend has only been very recently completed, and I am still learning how
to do anything meaningful with flask and back end.

I will most definitely add more self-reliant functionality in the upcoming weeks.

# What are the pros and cons of TDD?
Pros:
Test driven development (TDD) approach forces the developer to think functionality through first,
prior the implementation. This naturally results in a better thought out architecture, and functionality.
Furthermore, most of the tests force the code to have a granular, modular quality that 
results in a modular software development style.
In addition to that, since refactoring code is an explicit step in the TDD, the developers
get in the habit of refactoring their code that is fresh in their minds.
Owing to the nature of the approach application is well tested and there exists no reliance
on outside, third party testing suites.
It can be theorized that interfaces and interconnects between classes and modules is 
more thought out due to the modular, well-tested nature of the application that arises
from the TDD.

Cons:
Speed and ease of development. TDD slows down development and adds an entirely new 
difficulty curve for the less experienced developers. Time-consuming and painstaking nature
of the development can potentially hard morale at certain steps of the development.
It can be theorized that applying this concept to an existing codebase in the goal of 
refactoring it would be daunting.
The entirety of the development team has to adapt and be familiar with the TDD approach.
Upon change of functionality and/or objectives of the application the test suite will
likely require a rewrite.
