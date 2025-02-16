# Haskell Lazy Evaluation Bug

This repository demonstrates a subtle bug in Haskell code that arises from the interaction of lazy evaluation and infinite lists. The function `containsElement` uses `Data.List.intersect` to check if an element exists in a list. While it works correctly with finite lists, it leads to an infinite loop when the input list is infinite.  The solution demonstrates a more efficient approach to handling this situation.