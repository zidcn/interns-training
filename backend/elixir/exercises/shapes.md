# Shapes

We'll practice list comprehensions in this exercise by printing different shapes out given their sizes.

```Elixir
iex> Shapes.square(5)
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *

iex> Shapes.rectangle(5, 3)
* * *
*   *
*   *
*   *
* * *

iex> Shapes.rectangle(4, 8)
* * * * * * * *
*             *
*             *
* * * * * * * *

iex> Shapes.pyramid(5)
    *
   * *
  * * *
 * * * *
* * * * *

iex> Shapes.diamond(5)
    *
   * *
  * * *
 * * * *
* * * * *
 * * * *
  * * *
   * *
    *

iex> Shapes.pascal_triangle(5)
    1
   1 1
  1 2 1
 1 3 3 1
1 4 6 4 1
```