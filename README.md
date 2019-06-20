# Calculate ANSI S3.5-1997 Speech Intelligibility Index

Author: Gregory R. Warnes

Maintainer: Gregory R. Warnes <greg@warnes.net>

This package calculates ANSI S3.5-1997 Speech Intelligibility Index
(SII), a standard method for computing the intelligibility of
speech from acoustical measurements of speech, noise, and hearing
thresholds. This package includes data frames corresponding to
Tables 1 - 4 in the ANSI standard as well as a function utilizing
these tables and user-provided hearing threshold and noise level
measurements to compute the SII score.  The methods implemented
here extend the standard computations to allow calculation of SII
when the measured frequencies do not match those required by the
standard by applying interpolation to obtain values for the
required frequencies

Development of this package was funded by the Center for Bioscience
Education and Technology (CBET) of the Rochester Institute of
Technology (RIT).
