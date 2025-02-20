# Uninformative Error Message in Julia Function

This repository contains a simple Julia function that throws an error when a negative number is passed as an argument. The error message is not very informative, making it difficult to debug the issue.  The solution demonstrates how to improve the error message to provide more context.

## Bug
The `myfunction` function in `bug.jl` throws a generic `ErrorException` when a negative number is provided as input.  This makes it difficult for users to understand why the error occurred.

## Solution
The `bugSolution.jl` file provides an improved version of the function that throws a more informative error message, including the offending value.