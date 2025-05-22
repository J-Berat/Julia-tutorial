# Julia Tutorial

This repository contains a complete Jupyter notebook introducing the Julia programming language for scientific computing, particularly useful for students and researchers transitioning from Python, MATLAB, or C++.

## Contents

The notebook covers:

- Types and arrays
- Basic operations and broadcasting
- Booleans and logic
- Loops, conditionals, and functions
- Multiple dispatch and keyword arguments
- Dictionaries
- DataFrames and CSV I/O
- FITS file handling with FITSIO
- Image processing with ImageFiltering
- Plotting with CairoMakie
- Useful macros like `@views`, `@inbounds`, `@.`, `@elapsed`, etc.
- Linear regression and basic statistics
- Probability distributions with Distributions.jl

## Requirements

To use the tutorial, install Julia and the following packages:

```julia
using Pkg
Pkg.add([
  "IJulia",
  "FITSIO",
  "DataFrames",
  "CSV",
  "ImageFiltering",
  "TestImages",
  "CairoMakie",
  "Statistics",
  "Distributions"
])
