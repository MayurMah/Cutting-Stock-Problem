# Cutting Stock Problem 

## Objective

Solve [Cutting Stock Problem](https://en.wikipedia.org/wiki/Cutting_stock_problem "Cutting Stock Problem") using Kantorovich Formulation & Gilmore-Gomory Formulation (using Column Generation)

## Files :
- cs.Kantorovich.partial2.mos: Mosel code for Kantorovich formulation
- kant1.dat: Input data file for Kantorovich formulation
- cs.colgen.partial.mos: Mosel code for Gilmore-Gomory Formulation (using Column Generation)
- cs1.dat, cs2.dat, cs3.dat: Input data files for Gilmore-Gomory Formulation (using Column Generation)
- cs.colgen.partial.minwaste.mos: Mosel code to modify the Gilmore-Gomory formulation to incorporate the objective of minimizing the total wasted paper in Cutting Stock Problem



## Execution:

Language: Mosel

1. Download Xpress IVE (https://www.fico.com/en/products/fico-xpress-optimization)
2. Open the .mos files in Xpress and run 
