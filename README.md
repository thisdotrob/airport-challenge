Airport Challenge
=================
This was the first Makers Academy weekend challenge, designed to solidify
our understanding of the concepts we learned and used during the first
week in the Boris Bikes exercise (TDD & OOP).

Approach
--------
My first attempt at a solution was too heavily influenced by the solution
to our previous challenge (Boris Bikes). The user stories for the airport
challenge specify that it must be possible to tell a specific plane to land or
take-off, but I missed this and instead defined those methods in the airport
class only. I realised my mistake and started again, re-drafting my
[domain model](https://github.com/thisdotrob/airport_challenge/blob/second-attempt/domain-model.md)
and going from there, this time starting with just the `Plane` class.

My second attempt is much more closely aligned to the user stories, as I did
my best to avoid scope creep and keep my code to the minimum required to meet
their requirements.

I decided to use a separate class to implement the weather behaviour, with this
class containing a single class method #stormy? which returned true with a
probability of 1 in 10.

Setup
-----
1. Clone this repo
2. run `bundle` (assuming Bundler is installed)

Running tests
-------------
Run `rspec` after setup.

Usage
-----
Open IRB and use as follows:
![IRB usage example](http://i.imgur.com/2h9il34.png)
