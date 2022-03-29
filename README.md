# proj-portfoliobayes

## Modern Portfolio Optimization under Bayesian Approach

Project work as an attempt to highlight self-study/research efforts in [[Optimization and Computational Methods]], [[Quantitative Modeling]] and [[Bayesian Statistical Analysis]] using [[Python]]. 

Given that creating a portfolio of some financial assets is a base unit of work in many areas, I first study the basics of portfolio choice problem in the modern portfolio theory paradigm with an implementation of (Markowitz) mean-variance portfolio. 

After speculating on implications of such naive implementation, I complement the analysis with a Bayesian approach to introduce uncertainty in model parameters: Estimating a (posterior) distribution for the mean and variance of some security returns that are used as inputs to the portfolio optimization problem. 

In doing so, I will be using the Python libraries PyFinance, Pandas, NumPy, Matplotlib, SciPy, and PyMC3 to perform the statistical estimation and solve the optimization problem. I also planted some concise theory and background snippets here and there just to complement the material and hence, for an overall coherent representation