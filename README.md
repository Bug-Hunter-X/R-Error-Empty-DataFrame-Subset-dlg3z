# R Error: Subset Indexing on Empty Data Frame

This repository demonstrates a common error in R programming involving subsetting data frames and handling empty subsets.  The code attempts to access an element of an empty subset, which leads to an error. The solution shows how to avoid this error using appropriate checks.

## Bug Description
The bug arises from attempting to access an element from an empty subset of a data frame.  R throws an error in this scenario because there are no elements to access.

## Solution
The solution involves checking if the subset is empty before attempting to access its elements. This can be done efficiently using functions like `nrow()` to check the number of rows.