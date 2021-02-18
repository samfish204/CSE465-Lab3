# Lab 3:  More Exercises in Scheme

For this assignment, I have put some exercises about 
higher-order functions in scheme into different files. 

For each file, I provide a problem description at the 
top of the file and some examples of using a function
at the bottom of the file. 

You should look at the files that end in `.expected` to 
check what the output should be. 

Here are the different checks:
-  `make check-approx-der` - Check `approx-der.scm` which  returns the derivative of a function. 
- `make check-eval-poly` - Check `eval-poly.scm` which evaluates a polynomial whose coefficients are given as a list
- `make check-poly-func` - Check `poly-func.scm` which returns a function based on polynomial coefficients provided as a list. Each time you call the returned function it will evaluate the polynomial. 
- `make cube-all`  - Checl `cube-all.scm` which uses a higher order function (NOT RECURSION!) to cube all of the elements of a list. 
- `make reverse-fold` - Check `reverse-fold.scm`  which uses a higher order function (NOT RECURSION!) to reverse the elements of a list. You may NOT use the builtin `reverse` function. 
- `make even-values` - Checl `even-values.scm`  which uses a higher order function to remove all of the odd values from a list. NOT recursion. 

To run all of the tests use `make check` or just `make`. 

You will receive a zero if you submit and the checks do not all pass.
It is better to turn it in late than incomplete. 

# Grading Notes
This seems like many problems, but each one is small. 
If done correctly, each problem should have a short solution
(a few lines, often just one line of scheme). 

1. The grader will run 'make check' to confirm that all checks are successful. 
2. The grader will look at `reverse-fold.scm` to make sure that the `reverse` is not used. 
3. The grader will look at `cube-all.scm` to make sure that `map` is used properly.
4. The grader will look at `even-values.scm` to make sure that `filter` is used properly. 


