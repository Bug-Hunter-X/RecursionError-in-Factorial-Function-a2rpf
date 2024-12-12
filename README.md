# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions:  forgetting to handle negative inputs. The `factorial` function, as written, will cause a `RecursionError` when a negative number is passed as an argument because the recursive calls will never reach a base case. 

The solution file provides a corrected version of the function that handles negative input gracefully, returning an appropriate error message or handling it in a way suitable for the specific application.