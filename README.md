This repository contains microbenchmarking code for studying performance
interference (e.g., OS interference). 

ftq/ : the fixed time quantum microbenchmark.  

common/ : files common to any benchmark code in here.  this currently is
          restricted to platform independent, high precision timers.  the
          cycle.h file is the redistributable timer header from the FFTW
          package.
