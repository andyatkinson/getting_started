## Haskell

<https://github.com/pchiusano/fpinscala/wiki/A-brief-introduction-to-Haskell,-and-why-it-matters>

Download for OS X

<http://www.haskell.org/platform/mac.html>

`ghci` launches the interactive mode.
`:?` for help and `:quit` to quit.

`.hs` files

`if` is an *expression* not a statement, that must return a value.

functions can't begin with a capital letter.

An apostrophe at the end of a function name is used usually to indicate a strict version of a function (i.e. one that isn't lazy), or a slightly modified version of one with the same name.

If a function doesn't take any parameters, it is a "definition" or "name".

lists are homogenous data structures

concatenation of lists ++
`:` cons operator (prepend)

accessing list elements, use the `!!` operator (list indexes are zero based)

lexicographical order - for two lists, compares heads first, if equal compares second elements etc. Until the two pairs are not equal.

`head` function returns the first element of a list

`tail` function returns all elements except head, e.g. [3,2,1] returns [2,1]

`last` function returns last element

`init` is inverse of `tail`, returns head up to the last element

4 `elem` [3,4,5] would be true, infix function usage example, checks if 4 is in the list

[1..20] is a range from 1 to 20

[2,4..20] every even number from 2 to 20
[20,19..1] negative range, step is still specified, from 20 down to 1

take 24 [13,26..]
[13,26,39,52,65,78,91,104,117,130,143,156,169,182,195,208,221,234,247,260,273,286,299,312]
Didn't set an ending value on the range, and also specified a function of the number of items, because the infinite list is not immediately evaluated

`cycle` and `repeat` list functions
`replicate 3 10` => [10,10,10]

list comprehension
*predicate* goes at the end of a list comprehension.

ghci> [ x | x <- [50..100], x `mod` 7 == 3]
[52,59,66,73,80,87,94]

for x from 50 to 100, if x divided by 7 has a remainder of 3, include it

weeding out parts with a predicate is also called filtering

can include multiple predicates, separated by commas

#### Tuples

tuples are used to store several heterogenous elements as a single value
fixed size

pair: tuple of size two
triple: tuple of size three
list can only contain elements of the same size, and each element has to be of the same type
can have a single element list, but not a single element tuple

fst (8,11) `fst` takes a pair and returns its first component

snd (8,11) `snd` returns the second component

zip function, same as ruby
shorter list determines the output size of the zip, can use inifinitely size lists
