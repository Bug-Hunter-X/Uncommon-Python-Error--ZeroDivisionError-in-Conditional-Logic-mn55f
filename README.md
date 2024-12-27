# Uncommon Python Error: ZeroDivisionError in Conditional Logic

This repository demonstrates a simple Python function that can lead to a `ZeroDivisionError`. This is a common error but the way it occurs in the provided function may be less obvious.

## The Bug

The `function_with_uncommon_error` function attempts to divide `b` by `a` only if `a` is 0.  This leads to a runtime error because division by zero is undefined. A more robust error handling mechanism is required.