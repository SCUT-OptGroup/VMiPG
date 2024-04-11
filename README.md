# VMiPG

This code uses the variable metric inexact proximal gradient (VMiPG) method  to solve TV image denoising problems and regression problems.

For example, see test_Cauchy.m, test_fLasso_group.m and test_fLasso_realdata.m.

(Note that the UCI dataset is not included in the package. To generate the UCI dataset, 
download the original datasets tested in above paper from UCI data repository 
and put them into the folder [test_fLasso\Util\genUCIdatafun\UCIdataorg]. 
Then, run genUCIdata.m. For demonstration purpose, 
''mpg7'' is left in the folder [test_fLasso\Util\genUCIdatafun\UCIdataorg].)
