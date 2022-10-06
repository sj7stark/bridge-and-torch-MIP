# bridge-and-torch-MIP
An integer programming model for solving the bridge and torch problem

# Introduction
An example bridge and torch problem is . . .

Suppose 4 people need to cross a bridge at night. They need light in order to cross the bridge, but they only have one small lantern. Additionally, the bridge can only support up 2 people at a time. The individuals have the following walking speeds:

* A takes 1 minute to cross the bridge.
* B takes 2 minutes to cross the bridge
* C takes 5 minutes to cross the bridge
* D takes 8 minutes to cross the bridge

Can everyone end up together at the other side of the bridge within 15 minutes?

# Model Formulation

Please see [bridge_and_torch_notebook.ipynb](https://github.com/sj7stark/bridge-and-torch-MIP/blob/main/bridge_and_torch_notebook.ipynb) for the model formulation. My model finds the minimum possible time it takes for everyone to end up on the other side.

# Python Packages
The notebook containing this model uses the following packages:

* `docplex`
* `pandas`

`pandas` is just used to view the solution in a dataframe. `docplex` is the package used to setup and solve our integer program. `docplex` comes with CPLEX, a state-of-the-art mathematical programming solver from IBM. You can download a free trial of CPLEX [here](https://www.ibm.com/account/reg/us-en/signup?formid=urx-20028).

# More Information
For more information about the bridge and torch problem, check out these pages:
* https://www.geeksforgeeks.org/puzzle-18-torch-and-bridge/
* https://en.wikipedia.org/wiki/Bridge_and_torch_problem
