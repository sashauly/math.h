# math.h

## Implementation of the standard math.h library in the C programming language. This library implements basic mathematical operations, which are then used in various algorithms.

   This is an educational project, so it's no longer supported!
> 15.12.2022

## Important notes

 - The library developed in C language of C11 standard using gcc compiler as a static library with the header file s21_math.h(see `s21_math.a` goal in Makefile)
 - The library's code, including headers, makefile and library itself located in the src folder
 - The total verifiable accuracy is 16 significant digits
- Verifiable accuracy of the fractional part is up to 6 decimal places.
 - Written code follows the Google style. Legacy and outdated functions are not used according to POSIX.1-2017 standard(see `clang` goal in Makefile).
 - Integration tests covered all of the library's functions by unit-tests using the `check.h` library. Unit-tests checks the results of implementation by comparing them with the implementation of the standard math.h library(see `test` goal in Makefile). 
 - Unit tests coverage checked using gcov. It provides a gcov report in the form of an html page(see `gcov_report` goal in Makefile).
 - The programs developed according to the principles of structured programming, duplication in the code is avoided

### Everything that was implemented in the math.h library is located down below:

| No. | Function | Description |
| --- | -------- | ----------- |
| 1 | `int abs(int x)` | computes absolute value of an integer value |
| 2 | `long double acos(double x)` | computes arc cosine |
| 3 | `long double asin(double x)` | computes arc sine |
| 4 | `long double atan(double x)` | computes arc tangent |
| 5 | `long double ceil(double x)` | returns the nearest integer not less than the given value |
| 6 | `long double cos(double x)` | computes cosine |
| 7 | `long double exp(double x)` | returns e raised to the given power |
| 8 | `long double fabs(double x)` | computes absolute value of a floating-point value |
| 9 | `long double floor(double x)` | returns the nearest integer not greater than the given value |
| 10 | `long double fmod(double x, double y)` | remainder of the floating-point division operation |
| 11 | `long double log(double x)` | computes natural logarithm |
| 12 | `long double pow(double base, double exp)` | raises a number to the given power |
| 13 | `long double sin(double x)` | computes sine |
| 14 | `long double sqrt(double x)` | computes square root |
| 15 | `long double tan(double x)` | computes tangent |  