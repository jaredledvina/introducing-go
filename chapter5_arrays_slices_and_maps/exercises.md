1. How do you access the fourth element of an array or slice?

Using, `arrayname[3]` for an array and `slicename[2:3]` for a slice.

2. What is the length of a slice created using make([]int, 3, 9)?

The slice has a length of 9 but, points ontl to the first 3 elements. 

3. Given the following array, what would x[2:5] give you?

```
x := [6]string{"a","b","c","d","e","f"}
```

It would return, `c, d, e, f`

4. Write a program that finds the smallest number in this list:

```
x := []int{
    48,96,86,68,
    57,82,63,70,
    37,34,83,27,
    19,97, 9,17,
}
```

See exercise_4.go
