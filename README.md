# fftbw

This project offers routines to compute the fast Fourier transform (FFT), 
the fast sine transform (DST-I) and the fast cosine transform (DCT-I) of real and complex data.
Supported data types are arrays of type `float`, `double` and `long double`.
All routines are optimized for efficiency and can be done in-place.
Further, a lookup table for the sine function can be passed to all functions in order
to avoid recursion relations which might induce numerical inaccuracies for large data sizes.

Please see the header file for details on the usage.
