In our work [1], we proved that the period polynomials attached to 
the derivative of $L$-functions of cusp forms $f \in S_k(\Gamma_0(N))$ 
has all of its zeros in the unit circle, for all but finitely many pairs 
of weight $k$ and level $N$. We tried to cover (some of) the remaining
finitely many cusp forms. 

The list of the pair of weight and level $(k, N)$ which requires the 
manual verifications can be found in [1], Table 3. We wrote SageMath 
codes to do this. Although still finitely many cusp forms are remaining 
to be verified, we could reduce the Table 3 into much simpler table, Table 1. 

Our codes consist of two parts. This file, "01_L_vales.ipynb", generates 
the $L'$-values attached to cusp newforms.

Based on these values, "02_number_of_zeros_of_period_polynomial.ipynb" 
generates the period polynomials and counts the number of zeros on the unit 
circle of them.

All of the codes are written by [Hojin Kim](https://mathsci.kaist.ac.kr/~hjkim), o
ne of the authors of [1]. 

You need to install the following python modules on your environment:
* `numpy`, 
* `pandas`, and
* `pickle`. 

The `SageMath` version I used is `9.2`

--- 

Reference(s) : 

[1] Im, Bo-Hae; Kim, Hojin; Riemann hypothesis for period polynomials attached to the derivatives of $L$-functions of cusp forms for $Γ_0(N)$. _J. Math. Anal. Appl._ 509 (2022), no. 2, Paper No. 125971.
