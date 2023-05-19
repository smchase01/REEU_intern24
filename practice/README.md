# What is R

Introduction to R

R is a language and environment for statistical computing and graphics. It is a GNU project which is similar to the S language and environment which was developed at Bell Laboratories (formerly AT&T, now Lucent Technologies) by John Chambers and colleagues. R can be considered as a different implementation of S. There are some important differences, but much code written for S runs unaltered under R.

R provides a wide variety of statistical (linear and nonlinear modelling, classical statistical tests, time-series analysis, classification, clustering, …) and graphical techniques, and is highly extensible. The S language is often the vehicle of choice for research in statistical methodology, and R provides an Open Source route to participation in that activity.

One of R’s strengths is the ease with which well-designed publication-quality plots can be produced, including mathematical symbols and formulae where needed. Great care has been taken over the defaults for the minor design choices in graphics, but the user retains full control.

R is available as Free Software under the terms of the Free Software Foundation’s GNU General Public License in source code form. It compiles and runs on a wide variety of UNIX platforms and similar systems (including FreeBSD and Linux), Windows and MacOS. (R Team 2023)

R current version: R version 4.3.0 (Already Tomorrow) has been released on 2023-04-21.
R past version: R version 4.2.3 (Shortstop Beagle) has been released on 2023-03-15.
R
R last release: R version 3.6.3 (Holding the Windsock) has been released on 2020-02-29.

Why is this important? 

R versions and releases might have different functionalities, syntax or software available. The latest upgrade from R version 3.6 to 4.0 left many packages outdated and are no longer available. You might see a similar message when the package is outdated.
> Warning in install.packages :
  package ‘genbankr’ is not available for this version of R

Software installation

If you want to install new software you need to type `install.packages("package_name")` and you will see the message below, look for `* DONE (package_name)` for a succesfull installation. If you don't see `* DONE` but a `WARNING` message, then you didn't install the package correctly. In that case, read the `WARNING` message, probably you are missing another R package. That will happen very often.

EXAMPLE:  
```R
install.packages("vegan")

Installing package into ‘/home/microway/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/vegan_2.6-4.tar.gz'
Content type 'application/x-gzip' length 1496110 bytes (1.4 MB)
==================================================
downloaded 1.4 MB
* installing *source* package ‘vegan’ ...
** package ‘vegan’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
.
.
.
installing to /home/you/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-vegan/00new/vegan/libs
** R
** data
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (vegan)
```
The downloaded source packages are in
	‘/tmp/Rtmp8SSbkP/downloaded_packages’



References:

R Team. 2023. R Statistical Software. 
