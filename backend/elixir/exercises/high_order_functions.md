a. Define a function `double` that takes a function of one argument as argument and
returns a function that applies the original function twice. For example, if `inc` is a function that adds 1 to its argument, then `double(inc)` should be a function that adds 2. Think about `((double(double(double))).(inc)).(5)

b. Let f and g be two one-argument functions. The composition f after g is defined to be
the function x -> f(g(x)). Define a procedure compose that implements composition. For example,
```elixir
inc = fn x -> x + 1 end
square = fn x -> x * x end

(compose(square, inc)).(6)
# => 49
```

c. Implment a function `repeated` that does this:
```elixir
(repeated(square, 2)).(5)
# => 625

(repeated(inc, 10)).(5)
# => 15
```