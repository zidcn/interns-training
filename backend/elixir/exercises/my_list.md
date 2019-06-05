We use nested lists to represent trees, for example:
```
[1, 2, [3, 4]]
    / \   \
   1   2  [3, 4]
           / \
          3   4
```

a. Implement `MyList.count_leaves/1`.

b. Implement `MyList.reverse/1`.

c. Implement `MyList.deep_reverse/1` which also reverse nested lists.

d. Implement `MyList.flat/1`.

e. Implement `MyList.tree_map`:
```elixir
MyList.tree_map([1, 2, [3, 4]], fn x -> x * x end)
# => [1, 4, [9, 16]]
```
