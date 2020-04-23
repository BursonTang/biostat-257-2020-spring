*Burson Tang*

### Overall Grade: 75/85

### Quality of report: 10/10

* Is the homework submitted (git tag time) before deadline?

    - Yes. `Fri Apr 17 10:07:36`

* Is the final report in a human readable format html?

    - Yes.
	
* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?

    - Yes.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?

    - Yes.


### Correctness and efficiency of solution: 45/55

* Q1 - N/A

* Q2 (6/10 pts)

    - `Q2.4` This is false. `0 * Inf = NaN`. `(-2 pts)`
	
    - `Q2.5` This is also false. Let `x = 0.1` and `a = 7`. `(-2 pts)`

* Q3 (9/10 pts)

    - `Q3.3` Please explain why the `julia` compiler can optimize for integer input. This is because computation with integers fully obey distributive and associative rules from basic arithmetic. `(-1 pt)`

* Q4 (9/10 pts)

    - `Q4.3` be more specific about the numerical instability. The problem with using the expanded polynomial form is *catastrophic cancellation* from adding numbers of very different magnitudes. `(-1 pt)`

* Q5 (11/15 pts)

    - `Q5.4` was not answered. `(-4 pts)`

* Q6 (10/10 pts) 


### Usage of Git: 5/5

* Is the hw submission put into the `master` branch?

    - Yes.

* Are there enough commits? Are commit messages clear?

    - Yes. Avoid doing one big commit.

* Is the hw1 submission tagged?

    - Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly?

    - Yes.

* Do not put a lot auxillary files into version control.

    - Yes.
		

### Reproducibility: 5/5

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

    - Yes.

* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

    Not applicable for hw1.


### Julia code style: 10/10

* Rule (4): 4 spaces for indenting. 
    
* Rule (6): Never place more than 80 characters on a line.

* Rule (7): Always include a single space after a comma. 
 
* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them.

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
