# WAFOM-error

## Basic

* Dimension over R = 16
* Dimension over F2 = 16
* Number of precision digits = 32

## Point set generation

* Basis for 10000 digital nets are randomly selected.

## WAFOMs

* WAFOM values for c = -2, -1, 0, 1, 2 are calculated.

## Errors

* QMC integration error for f(x) := cos(2^cΣx_i) are calculated.
* The lg-abs-error is plotted:
    * E[i] := log_2|err(P, f)|.

## Files

* If the first/second digit of the name of a file is i, the c-value for WAFOM/integrand is i-2.
