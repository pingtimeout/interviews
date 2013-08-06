Codebreaker
-----------

Code breaking is all about finding the secret code.

Your mission is no different!

The test
--------

You have to implement a simple program that implements the core logic of a Code Breaker:

 - A game starts with a secret code of 4 digits
 - It is declared "finished" when the secret code has been found
 - When submitting a guess, the game will return a + sign for an exact match
 - When submitting a guess, the game will return a - sign for a digit match
 - An exact match is a digit that matches a digit of the secret code both in value and in position
 - A digit match is a digit that matches a digit of the secret code in value but does not have the correct position

Some examples
-------------

This table summarizes some test cases.

    Secret | Guess | Result
    -------+-------+-------
    1234   | 5678  |       
    1234   | 1245  | ++-   
    1234   | 2002  | -     
    1234   | 2200  | +     
    1234   | 1234  | ++++  


