# Operators
* Comparison operators: Evaluating Conditions
    * Situations can be evaluted by comparing one value in the script to what you expect it might be.  The result will be a **Boolean**: **true** or **false**
    * Is equal to
        * = =
        * compares two values to see if they're the same
        * preferable to the strict method
            * ===
            * compares two values to check that the data type and value are not the same
    * Is not equal to
        * !=
        * compares two values to see they are *not* the same
        * preferable to the strict method
            * !==
            * compares two values to check that data type and value are the same
    * **Evaluating** = testing or checking a condition
    * greater than
        * '>' (without apostrophe)
        * checks to see if number on the left is greater than number on the right
            * '>='
            * operator checks if number on the left is greater than or equal to number on the right
    * less than
        * '<'
        * operator checks if number on the left is less than number on the right
            * '<='
            * operator checks if number on the left is less than or equal to number on the right

# Logical Operators
* Logical operators allow you to compare the results of more than one comparison operator
* && Logical and
    * operator tests more than one condition
    * if both expressions evalute to true then expression returns true.
    * if one expression returns false, then the expression will return false
* || Logical or
    * operator tests at least one condition
    * if either expression evaluates true ten the expression is true.
    * if both are false then the expression will return false
* ! Logical not
    * inverts a single boolean value
    * reverse the state of an expression
    * falses become trues and vice versa
* Short-circuit evaluation
    * logical expressions are evaluated left to right
    * if the first condition can provide enough info to get the answer, then the second condition will not be evaluated

# Decisions and Loops
* Loops
    * check a condition
    * if returns true, a code block will run
    * condition is checked again, if true keeps going, until it reaches a false
* Three types of loops
    1. For
        * if you need to run code a specific number of times
    2. While
        * if you do not need to know how many times the code should run
    3. Do While
        * similar to while, but it always run the statements inside the curly braces at least once, even if condition evaluates to false
* Loop Counters
    * p. 171

