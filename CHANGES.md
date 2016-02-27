
# Changelog

## Version 0.0.4

- Adding the class `HashTable` which uses linear probing and resizes. This is a very simply class (which nonetheless can still contain some bugs, even if some tests have started to being done, and the class passed them)

- Added first tests to the class `HashTable`.

## Version 0.0.3


- Added new "utility" functions to the class `Heap`, useful mostly for the `MinMaxHeap` class.

- Added new tests to `MinHeap`, `MaxHeap`, `Heap`. In general, tests have been slightly changed.

- Moved the "is-bst", "is-rbt", "is-min-heap" and "is-max-heap" to files where their respective classes are defined.

- Added class `MinMaxHeap`.

- Starting the tests for the `MinMaxHeap` class.

- Fixed some bugs around.

- When an index is not found `None` is **no** more returned, but instead -1 is returned (in all methods of the class `Heap`).


## Version 0.0.2

- Added `RBT` and `RBTNode` classes. 

- Moved randomness insertion of `BST` to another class called `BSTImproved`.

- Added `MaxHeap` class, which is basically a mirror-class of the `MinHeap`.

- Starting adding and moving tests to the folder [tests](tests).

- Created script to automise the run of tests.

## Version 0.0.1


- Adding first algorithms and data structures.

- Available documentation (produced using `pdoc`) in HTML format.