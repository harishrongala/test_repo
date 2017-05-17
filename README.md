# What is Linear Dependence? 

A set of vectors {v<sub>1</sub>,...,v<sub>n</sub>} is linearly independent if there are scalars c<sub>1</sub>...c<sub>n</sub> (which <b>aren't</b> all 0) such that the following is true:

c<sub>1</sub>v<sub>1</sub> + ... + c<sub>n</sub>v<sub>n</sub> = 0

## Example

Let's say we have three vectors in a set: x<sub>1</sub> = (1, 1, 1), x<sub>2</sub> = (1, -1, 2), and x<sub>3</sub> = (3, 1, 4). 

These set of vectors are linear dependent because 2x<sub>1</sub> + x<sub>2</sub> - x<sub>3</sub> = 0. Why is this equal to zero? Again, because 2*(1,1,1) + 1(1,-1,2) - (3,1,4) = (2+1-3, 2-1-1, 2+2-4) = (0, 0, 0). If we can find some equation that satisfies a resultant of 0, it's considered linear dependent!


# What is Linear Independence? 

A set of vectors is considered linearly independent simply if they are not linear dependent! In other words, all the constants from the previous section should be equal to zero. c<sub>1</sub> = c<sub>2</sub> = ... = c<sub>n</sub> = 0

# Using Det

If the vectors are written in the form of a matrix, it's determinant can be used to classify if the vectors are linearly dependent or independent.

## Example

Consider the vectors again x<sub>1</sub> = (1, 1, 1), x<sub>2</sub> = (1, -1, 2), and x<sub>3</sub> = (3, 1, 4)

![Matrix](https://latex.codecogs.com/gif.download?%5Cbegin%7Bbmatrix%7D%201%20%26%201%20%26%203%20%5C%5C%201%20%26%20-1%20%26%201%20%5C%5C%201%20%26%202%20%26%204%20%5C%5C%20%5Cend%7Bbmatrix%7D)
