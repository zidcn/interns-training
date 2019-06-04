Implement a function that can calculate the given expression as string.

```Elixir
# First, it can handle expressions contain only '+' or '-' operator.
Expression.calc("1+2+3+4-5")
# => 5

# Then, it can handle '*' and '/' too(extra: try adding more operators such as `^`).

Expression.calc("3+4*5-14/2")
# => 16

# Finally, it can  also handle braces `()`.

Expression.calc("5*(6+3)+2*8")
# => 61

# How about negative numbers?
Expression.calc("5*(6+3)+2*(-5)")
# => 35
```