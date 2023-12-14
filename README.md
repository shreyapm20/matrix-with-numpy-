# matrix-with-numpy-
import numpy 
x=numpy.array([1,2],[4,5])
y=numpy.array([7,8],[9,10])
# Addition of the matrices 
print("The element wise addition of the matrix is :")
print(numpy.add(x,y))
# substraction of the matrices 
print("The subtraction of the given two matrices is:") 
print(numpy.subtract(x,y)) 
 #multiplication of matrices 
print("The multiplication of the given two matrices is:") 
print(numpy.dot(x,y)) 
#transposeof matrix a 
print("The transpose of matrix a is:")
print(x.T)
#transpose of matrix b 
print("The transpose of matrix b is:")
print(y.T)


