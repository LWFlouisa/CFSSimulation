# CFSSimulation
Just some example scripts.

# Definition Expression Bareness
A standard lisp expression requires the parentheses to be present in a function call.

A bare lisp expression allows for the parenthesis to be present or not present.

## Practical Examples
These are bare function calls that are almost byte code but not quite.

~~~
arc red folded large
arc green folded large
arc blue folded large
~~~

## Clothed Functions
Clothed functions are primarily for transpiling to standard clisp or clojure, making it closer to lisp than horseshoe crabs are to actual crabs:

~~~
(arc "red" "folded" "large")
(arc "green" "folded" "large")
(arc "blue" "folded" "large")
~~~
