Parts of tensorflow:-
-Graphs:Makes a graph of defined computations.It is a waty of defining operarions
-Sessions: rUNNING PART/WHOLE OF A GRAPH


Tensors
-A tensor is just a box of numbers — maybe a line, a table, a cube, or a bunch of cubes stacked together — and TensorFlow uses these to do all its calculations.
-Formally,"A tensor is a generalization of vectors and matrices to potentially higher dimensions. Internally, TensorFlow represents tensors as n-dimensional arrays of base datatypes."
-A vector is just a list of numbers arranged in a line — either horizontally or vertically.
-A matrix is a 2D grid (a table) of numbers — rows and columns.
-Scalar is just one value 
-Each tensor represents a partialy defined computation that will eventually produce a value. TensorFlow programs work by building a graph of Tensor objects that details how tensors are related. 
-Has Data type(mostly numbers) and shape(dimension)
*********CODING********
function for defining tensors:-
tf.Variable(value,datatype),datatype eg:-tf.float64,tf.int64,tf.string
**********Theory****************
-Rank/Degree of tensor is the no of dimention of a tensor
-Can be found as the deepest level of arer in a tensor
Shape of Tensor
-The number of values in each dimention
*******coding********
tensor.shape->TensorShape([A,....,z])
The leftmost number (A) is the outermost structure (like "how many groups")
The rightmost number is the innermost detail (like "how many values in a row")
tf.reshape(tensorname,newshape)
**New shape(multiplied) must have same number of elements as orignal***
EX-tf.reshape(tensor,[3,-1])
seperates into 3 lists and infers the amount needed in each
#also if you put the multipliction of orignal tensor you will get a huge array with no nested arrays
Types of Tensors:-
    -Variable
    -Constant
    -Placeholder
    -Sparsetensor
    ***Every Tensor Type execpt variable is immutabe****
colab-https://colab.research.google.com/drive/1XyBrqky4h7t8u0XF7Jp9NG5st8B6eDhs?usp=sharing
  
