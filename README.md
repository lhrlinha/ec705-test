# Assignment 3: Bootstrapping Standard Errors

### Task: 

- Part (A) Obtain the bootstrapped standard errors of the regression specified in lecture notes 4-5.
- Part (B) Execute the program on BU SCC cluster.

### Directions:

#### Part (A)
* Write two versions: parallelized and unparallelized. 
* Confirm that your bootstrapped SE is approximately the same as the analytical standard errors (reported as the results of lm function).
* Check that the parallelized version is faster than the unparallelized version.
* Upload the *.R code* and *output* of your results. The output should be a table that shows the SE derived from all three methods (analytic, non-paralell bootstrap, and parallel bootstrap), as well as the time it took for each method. This only needs to be a table in a plain text file.  
* Use the appropriate folder structure and ensure your working directory is appropriately set. 

### Grading for Part (A)

To achieve full marks in Part (A)

* You must include tests such that the code throws an error if the bootstrapped standard errors are not close enough to the value derived analytically
* Write functions which calculate the standard error for each method: parallel bootstrap, non-parallel bootstrap, and analytic. Ensure the functions take `N`, `R`, and `flights` as inputs
* Write the results to separate `.txt` or `.tex` file. The output file submitted as part of the assignment should be created by the code for reproducibility

#### Part (B)
* Clone your assignment repo on BU SCC server.
* Write a .sh script that execute your code on BU SCC cluster.
* *Git push* your *.sh file* and *output* file in the assignment repo.
  - At this point, you should be able to git push your code and results from your local computer or server (not manually uploading from GitHub website)

### Grading in Part (B)

To achieve full marks in Part (B)

* Complete the assignment using only git and *no* manual uploading
