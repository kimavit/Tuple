Tuple data type.
===
> #### Tuple is immutable sequences containing, unlike strings, completely arbitrary data.

Tuples support:
1. Access to an element by index (only for obtaining element values);
2. Methods, in particular index(), count();
3. Built-in functions, in particular len(), sum(), min() and max();
4. Slices;
5. The membership operator in;
6. The concatenation (+) and repetition (*) operators.

Iterating through the elements of a tuple:
````ruby
numbers = (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
for i in range(len(numbers)):
    print(numbers[i])
````
````ruby
numbers = (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
for num in numbers:
    print(num)
````
Comparing tuples

