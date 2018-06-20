# Develop-Function-for-Gradient-Descent
UCLA Master of Applied Economics Econ 423 Assignment
- You will upload a python file named updateformulas_yourlastname.py 
- In this file, you will develop Python functions for derivatives (of the Cost Function J with respect to w1, w2, ...,wn, and b) based upon the slide deck:
   3.C.6: Linear Regression File 
PART 1 - 3 points
- The first function for derivatives will look like the following:

      def derivativesLoops(X, Y, W, b):
      ....
      return model
Here model is an NumPy vector: [dJ/dw1, dJ/dw2, ...., dJ/dwn]. X, Y, and W are also NumPy arrays following the convention used in the slide deck. This function will use the loops to determine derivatives. Therefore, you will use the summation relationship in the slide deck to create the nested loops. Your function should be general in the sense that it should determine number of features and number of training examples without the need of explicitly providing  the dimensions. 

PART 2 - 2 points
- The second function will perform the same function as the first function but will use the matrix relation from the slide deck to determine the derivatives:

      def derivativesMatrices(X, Y, W, b):
      ....
      return model
Notes:

- Your function will be tested with the several test cases. Your function should yield correct results. 
- Note that since both functions perform the same operations, they  should both yield the same result, for any given input.
- Your file should not contain anything other than two functions described above. 
- Follow the function definitions provided above. Any other function header will result in a deduction of points. 
