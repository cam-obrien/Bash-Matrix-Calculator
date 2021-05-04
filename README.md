#Bash Matrix Calculator
Bash Matrix Calculator made as an assignment for an Operating Systems class

"In this assignment, you will write a bash shell script that calculates basic matrix operations using input from either a file or stdin. The input will be whole number values separated by tabs into a rectangular matrix. Your script should be able to print the dimensions of a matrix, transpose a matrix, calculate the mean vector of a matrix, add two matrices, and multiply two matrices."

Commands:

matrix dims [MATRIX]
  Prints the dimensions of a given matrix in the form "rows cols".
  
matrix transpose [MATRIX]
   Reflects elements of a matrix along the main diagonal, meaning a matrix of MxN will transpose to a matrix of NxM.
  
matrix mean [MATRIX]
  Returns a one lined vector containing the mean of each column of the matrix.

matrix add MATRIX_LEFT MATRIX_RIGHT
  Takes in two different matrices and adds them together to return a matrix with each sum. Returns an error if the two matrices given are incapable of being added together due to dimensional differences.

matrix multiply MATRIX_LEFT MATRIX_RIGHT
  Performs multiplication on two given matrices producing a new matrix with the correct product. Returns an error of the two matrices given are incapable of being added together due to dimensional differences.
