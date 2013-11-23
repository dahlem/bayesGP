# Copyright (C) 2007-2013 Dominik Dahlem <Dominik.Dahlem@gmail.com>
#  
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without 
# modifications, as long as this notice is preserved.
# 
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

AC_PREREQ(2.61)
AC_INIT([Stochastic Kriging],
        [2.0],
        [Dominik Dahlem Dominik.Dahlem@gmail.com], 
        [bayesGP])

AM_INIT_AUTOMAKE

AC_CONFIG_FILES([
   DESCRIPTION
   Makefile
   inst/bayesGP.m
   inst/cv_error.m
   inst/gp.m
   inst/gpX.m
   inst/logit.m
   inst/logitinv.m
   inst/r_pred.m
   inst/scf_gaussian.m
   inst/scf_gaussianm.m
   inst/scf_gaussianu.m
   inst/ssp.m
   inst/sst.m
   inst/welford_mean.m
])


AC_OUTPUT

for top_builddir in . .. ../.. $ac_auxdir $ac_auxdir/..; do
  test -f $top_builddir/configure && break
done

AC_MSG_RESULT([

$PACKAGE $VERSION: Automatic configuration OK.

Type 'make' to compile des.

])
