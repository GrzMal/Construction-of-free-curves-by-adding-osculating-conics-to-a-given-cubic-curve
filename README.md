In order to check computational results in the article: "Construction of free curves by adding osculating conics to a given cubic curve" you need to:

1a. Modify one of the core files of SINGULAR. This modification allows user to make field extensions computations, which are not cover by original library. To do so:
a) download "classify.txt" file
b) change name of this file to "classify.lib"
c) replace the original file of the same name. The standard path for this file is (...\cygwin64\usr\local\share\singular\LIB)

or

1b.
a) download "classify.txt" file
b) insert line ' <"classify.txt"; ' into
c) replace the original file of the same name. The standard path for this file is (...\cygwin64\usr\local\share\singular\LIB)

2. Run in SINGULAR "cmp.txt" file.


