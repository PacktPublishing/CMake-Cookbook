# Using the AddressSanitizer and reporting memory defects to CDash

In this recipe, we fabricate two bugs in our code, which may go undetected in a
normal test run. To detect these bugs, we couple CTest with dynamic analysis by
using
[AddressSanitizer](https://github.com/google/sanitizers/wiki/AddressSanitizer),
and report the defects to CDash.


- [cxx-example](cxx-example/)
- [fortran-example](fortran-example/)
