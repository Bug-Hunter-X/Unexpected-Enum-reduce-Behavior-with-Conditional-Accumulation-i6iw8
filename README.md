# Elixir Enum.reduce Unexpected Behavior

This repository demonstrates a potential issue with the `Enum.reduce` function in Elixir when dealing with conditional accumulation.  The provided example showcases a scenario where values are only added to the accumulator if they satisfy a specific condition, potentially leading to unexpected or incorrect results if not handled properly.

## Bug Description

The `bug.ex` file contains Elixir code that uses `Enum.reduce` to sum values greater than 3 in a list. However, the function omits values not meeting the condition, resulting in an incorrect sum.

## Solution

The `bugSolution.ex` file provides a corrected implementation using a more robust approach to ensure all values are handled correctly during the reduction process, even if no values satisfy the condition. 

This example highlights the importance of careful handling of the accumulator in `Enum.reduce` to avoid unexpected behavior and ensures accurate results.