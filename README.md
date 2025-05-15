# GPfactor

This repository uses GPlearn to release factor mining.

# Tasks

There are 3 tasks you should accomplish:

*1. Change the input*

The original input of GPlearn is a 2D matrix [samples, features]. As for factor mining, the input is a 3D matrix [dates, stock_ids, features]. The given code has almost complete the task, please refer to code in genetic.py and _program.py with tag *Change*. But some codes have to be changed further in genetic.py with tag *Change later*. Your task is to understand the change of input and write the input validation code in genetic.py, which is the code with tag *Change later*.

*2. Add more funtions*

In function.py, some functions are not realized by GPlearn itself, especially those time series functions. Your task is to realize these functions and make sure the test in demo.ipynb could run correctly. Also, some functions may cause problem since the shape of input is changed, you should solve the problem as well if it appears.

*3. Validity of Test*

For some of the functions, like *delay*, they may cause some samples no longer effective in the test. Your should consider these situations and deal with them. This is an open question with no standard answer. Any reasonable solution is welcomed.