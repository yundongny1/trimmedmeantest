This is the repository for testing if a Go Library for trimmed mean was created succesfully. To see the library, go to https://github.com/yundongny1/trimmedmean/.
To use this library, run 'go get github.com/yundongny1/trimmedmean' in the terminal of your local directory. There are two functions in this library TrimmedMeanFloat and TrimmedMeanInt for finding the trimmed mean of a slice of ints and floats. 

The method is as below:
TrimmedMeanFloat(x, trim = 0), where trim is the fraction (0 to 0.5) of observations to be trimmed from each end of x before the mean is computed. This function will not take values higher than 0.5
