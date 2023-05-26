# The Cutting Stock Problem

The origin of the cutting stock problem is in the paper industry. Given paper rolls of fixed width and a set of orders for rolls of smaller widths, the objective of the Cutting Stock Problem is to determine how to cut the rolls into smaller widths to fulfill the orders in such a way as to minimize the amount of scrap. The problem is tackled here (https://neos-guide.org/case-studies/sc/mfg/the-cutting-stock-problem/) with the use of a solver.

The approach used here involves the use of a Constrained Quadratic Model (CQM) from Dwave (https://cloud.dwavesys.com/). The solution is computed using the LeapHybridCQMSampler.

The solution obtained has been compaired to the solution obtained with some online CSP available and it matches the result in terms of the total numberof minimum rolls required for this specific values (453)

Once again proving that Dwave Quantum Annealer can be used when properly queried. 


## References
An Example (from Linear Programming by Vasek Chvatal, 1983)
