## Test environments
* local OS X install, R 3.6.0
* ubuntu 14.04 (on travis-ci) (devel and release)
* win-builder (devel and release)

## R CMD check results

0 errors | 0 warnings | 0 notes

## 0.0.4 Submission

This patch release fixes the warnings on the CRAN check page due to the `lending_club` dataset being moved from rsample to modeldata.

## 0.0.3 Resubmission

### Review 1

I had an incorrectly specified Authors@R + Maintainer field combination. That
has been fixed.

## 0.0.3 Submission

This patch release is for compatibility with vctrs 0.2.0.

This also changes the maintainer to Davis, as he has taken over regular 
maintanence of the package.