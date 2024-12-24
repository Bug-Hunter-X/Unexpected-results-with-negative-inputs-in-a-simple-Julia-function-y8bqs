# Unexpected Results with Negative Inputs in a Simple Julia Function

This repository demonstrates an uncommon bug in Julia related to unexpected behavior when handling negative numbers in a seemingly straightforward function. The function intends to square the input, but produces unexpected outcomes for negative inputs.

## Bug Description

The `myfunction` function is designed to square its input. However, it exhibits unexpected behavior when a negative number is supplied.  The issue is subtly hidden in how the negative sign interacts with the squaring operation.

## Bug Solution

The solution involves clarifying the squaring operation to explicitly handle the negative sign correctly, ensuring that the square of a negative number produces a positive result.