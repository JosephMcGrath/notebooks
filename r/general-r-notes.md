# R Notes

## [Namespaces](http://r-pkgs.had.co.nz/namespace.html)

### Search Path

When referencing an object in R, it looks for the name in a set order of places. First it looks in the global environment, if not there, then in all of the attached packages in the order that they were attached (see below).

### Loading & Attaching Packages

* Load - Loads all the code associated with the package. Including:
    * Code,
    * Data,
    * DLLs,
    * S3 & S4 methods,
    * Running the ````.onload()```` function.
* Attach - Adds the package into the search path.

This means that if a package is loaded, but not attached, the only way to access it's components is via the ````::```` syntax. Using ````::```` will also load (but not attach) the package however.

Both the ````library()```` and ````require()```` functions will load the package, then attach it - making the difference between the two something of a technicality under normal use. The ````search()```` function will list the current namespaces. A package can be loaded without attaching using the ````requireNamespace()```` or ````loadNamespace()```` functions.

The two suggested ways to load packages are with:

* ````library(x)```` - which loads & attached a package, or throws an error if it's not installed.
* ````requireNamespace(x, quietly = TRUE)```` to test if the package is installed or not - returning ````TRUE```` or ````FALSE````.
