# Hidden Markov Models

Some code in R and C++(Rcpp) written for the paper [Understanding narwhal diving behaviour using Hidden Markov Models with dependent state distributions and long range dependence](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006425)

- The main code is "main-code.R".
- File "functions.cpp" provide C++ functions to support the analysis in the main R file.
- Files "drawing.R" provides plotting functions for the main R file.
- Two packages mt_1.0.tar.gz and plosM1_1.0.tar.gz are written in C++ (with Rcpp) to support fast computation in the analysis.
The package mt_1.0.tar.gz runs > 100 times faster than diveMove package for extracting dives, thanks to Rcpp.
