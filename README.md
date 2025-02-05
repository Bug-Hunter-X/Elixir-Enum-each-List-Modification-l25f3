# Elixir Enum.each List Modification Bug

This repository demonstrates a common misconception when using `Enum.each` in Elixir to modify a list.  Modifying the list within the `each` function does not update the original list in place.  Instead, a new list is created.

The `bug.ex` file shows the erroneous attempt to remove an element from a list during iteration.  The `bugSolution.ex` file provides a correct solution, illustrating how to achieve the desired outcome.

## How to run

1. Ensure you have Elixir installed.
2. Clone this repository.
3. Navigate to the directory.
4. Run `elixir bug.ex` and `elixir bugSolution.ex` to see the different outputs.