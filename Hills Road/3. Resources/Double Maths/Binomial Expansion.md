# Binomial Expansions
## What is it
Binomial expansion can be used to find the result of binomials to higher powers. When dealing with binomial expansions, the 'choose' function is used to find values. The 'choose' function is as follows : `(n r) = n! / r! * (n - r
)!`. This can be used to find the values inside Pascal's triangle. 

## How to use it
The choose function on a calculator is usually shown as `nCr` , or 'n choose r'. 

Say we have an expression `(x+1)^8`. To find the values once we have expanded the function we do: `8C0 * x^8 * 1^0` then add `8C1 * x^7 * 1^1`, as you can see as one power increases the other decreases. 

Using the expanded expression to however many decimal places, we can then find and estimate for a non-integer to the same power. For example, say we want to find `2.895^8`, then we can do `(x+1)^8 = 2.895^8`, therefore `x+1 = 2.895` and from there we can substitute the value of `x` back into the expression to get an approximation to the true value.