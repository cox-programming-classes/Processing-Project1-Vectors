# Project 1 - Vectors

In this project you are going to build one of the fundamental components that we will use throughout the class.  Doing computations with Vectors will allow us to simplify a lot of graphical operations.  
  
## Vector2
A class which represents a 2-Dimensional Vector and encapsulates the useful arithmetic operations that we will want to do with Vectors.  
  
### Properties
You must decide what are the appropriate pieces of data to represent a 2-dimensional Vector.  The constructor method might give you a hint ;)  
  
### Constructor
Complete the Constructor method that is provided.  
`public Vector2(float x, float y)`  
  
### Arithmetic Operations
Write the implementations for each of the provided method headers.  Remember to use the keyword **this** correctly!

#### Addition and Subtraction and Inverse
These methods should be trivial to write ;)  Easy to do in a 1 liner
Inverse refers to **this** vector specifically~

#### Dot Product and Magnitude
Depending on what math you have learned, computing the Dot Product (a.k.a. the "Inner Product") may require a little research.  Magnitude is also the "Length" of the vector and can be computed in more than one way (to get the same answer of course!)

#### Unit Vector
Again, depending on your math background--may need some research.  A Unit Vector is a Vector with Magnitude **1** in the same direction.

## Bonus Methods!
Here are some addtional methods that you may write that will also make the project more rich and powerful.  We will eventually write some of these together ;)

#### Perpendicular Vector (Easy)
Compute *a* vector which is Perpendicular to **this** vector. This was an Algebra I problem ;) But, it has an interesting relationship to the "Cross Product" operation in higher dimensions!  
`public Vector2 perpendicular()`  

#### Angle Between Vectors (Moderate)
Compute the Angle (in radians) between **this** vector and the *other* vector.  
`public float angleTo(Vector2 other)`  

#### Rotate Vector (Difficult)
Compute **this** vector rotated by a given number of Radians.  This will almost certainly require you to do some research!  
`public Vector2 rotate(float rads)`  
