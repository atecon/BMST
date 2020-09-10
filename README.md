# BMST -- *Binary Model Specification Test* package
 
This Gretl package comprises the following specifications tests for binary logit and probit models:

1) Test on no heteroskedasticity for both Logit and Probit models.
2) Test on the correct functional form (RESET type of test) for both Logit and Probit models.
3) For Logit model test that the distribution is Logistic against the alternative that is Burr Type 2 (and hence skewed).
 
# Detailed help file
A detailed help file can be found here: https://github.com/atecon/BMST/blob/master/src/BMST_help.txt
 
# Sample script
The sample script can be found here: https://github.com/atecon/BMST/blob/master/src/BMST_sample.inp

# Changelog:
## v2.0, September 2020
   + Completely refactored.
   + New much simpler API.
   + Add unit-tests.
   + Required gretl version is now 2017d.

## v1.0, 2016
   + Initial version.

## v0.5
   + Joint package of separate functions.
