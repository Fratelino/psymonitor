## Test environments
* local OS X install, R 3.5.0
* linux 14.04 (on travis-ci), R 3.4.4
* Windows Server 2012 on appveyor (devel and release)
* Rhub
  * Fedora Linux, R-devel, clang, gfortran
  * Ubuntu Linux 16.04 LTS, R-release, GCC
  * Windows Server 2008 R2 SP1, R-devel, 32/64 bit
* win-builder (devel, release)


## R CMD check results

0 errors | 0 warnings | 0 note


## Resubmission

This is a resubmission. In this version I have:

* Inserted `suppressWarnings(RNGversion("3.5.0"))` to make our package successfully pass the checks for current R-devel
and R-release.

  
