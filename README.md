# assignment1.2


1.What are the different methods to call a function in R?
answer:
a.
            #built-in function can be called without defining them first
            eg: seq(), mean(), max()
            #user defined functions need to be created first.
            eg: 
            new.function()<-- function(a){
            r <-- a+1
            }
            #call the function
            new.function(6)
b.
           #Call the function without supplying an argument.
          eg: new.functiom()
c.
          new.function <- function(a,b) {
             result <- a * b
             print(result)
             }
          #call the function by position of arguments
          new.function(5,3)
          # Call the function by names of the arguments.
          new.function(a = 11, b = 5)
d
          #Calling a Function with Default Argument
          eg:
          # Create a function with arguments.
          new.function <- function(a = 3, b = 6) {
             result <- a + b
             print(result)
          }
          # Call the function with giving new values of the argument.
          new.function(9,5)
          
2.the lazy evaluation of a functionmeans,the argument is evaluated only if its used inside the body of the function.
ANSWER: TRUE

3.a insights driven from descriptive analysis isnt meaningful. FALSE -helps understand past occurences
3.b the number of values in each element in a list should be equal.- FALSE
3.c the datasets are not stored in the memory of the computer using r. TRUE
3.d data frames and matrices are 2 dimnensional however arrays are multi-dimensionai. TRUE
