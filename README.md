# BMST
 **Binary Model Specifcation Test PACKAGE**

   This code comprises 3 specification tests for **Gretl** for binary Logit models
   and 2 specification tests for binary Probit models.

   1) Logit_burr(): LM test of the null that the distribution
   				is Logistic against the alternative
   				that is is Burr Type 2 (and hence skewed - to
   				the left or to the right)
   	References:
   	* J. M. Thomas (1993), "On Testing the Logistic Assumption in Binary
   	Dependent Variable Models" Empirical Economics, 1993, 18:381-392
   	* D. J. Poirier (1980), " A Lagrange Multiplier Test for Skewness in Binary
   	Logit Models. Economics Letters", 5, 141-143

   2) Logit_hom(): In the LM tests for homoskedasticity, the form
   				of the skedastic function is taken to be
   				exp(2Ztγ) where Zt is the vector giving the tth
   				observation on the r variables that are believed
   				to give rise to the heteroskedasticity.

   3) Logit_reset(): The LM tests for functional form are similar
   				to the familiar "RESET test" for the standard
   				linear OLS model.

   4) Probit_hom(): In the LM tests for homoskedasticity, the form
   				of the skedastic function is taken to be
   				exp(2Ztγ) where Zt is the vector giving the tth
   				observation on the r variables that are believed
   				to give rise to the heteroskedasticity.

   5) Probit_reset(): The LM tests for functional form are similar
   				to the familiar "RESET test" for the standard
   				linear OLS model.

    	* Davidson, R. & J. G. MacKinnon (1984), "Convenient Specification
   	Tests for Logit and Probit Models", Journal of Econometrics 25, 241 262.
   	* Davidson, R. & J. G. MacKinnon (2004), Econometric Theory and Methods,
   	Oxford University Press, Oxford.

   For more information see Dave Giles,
   ULR: http://web.uvic.ca/~dgiles/downloads/binary_choice/index.html

   Dave Giles' original Eviews codes were translated by Artur Tarassow
   
   ---------------------------------------------------------------------------
   CHANGELOG:
   	Vers. 0.5:
   	- Joint package of separate functions
   	- NOTE: This package replaces the LOGIT_HETERO.gfn package (vers. 0.2)
   		which will not further developed!
