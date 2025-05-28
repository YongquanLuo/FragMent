# A code to study the fragmentation of filaments (FragMent)
FragMent is a python/C module which collates a number techniques used to study fragmentation in filaments. It also performs model selection using a frequentist and Bayesian approach to find the best descriptor of a filament's fragmentation. The code is open-source and can be downloaded here.

The accompanying paper can be found [here](http://adsabs.harvard.edu/abs/2019arXiv190106205C). It details the sensitivities of each method and explains in more detail a number of the procedures one should use when analysing fragmentation.

While the code was designed to investigate filament fragmentation the functions are general and may be used for any set of 2D points to study more general cases of fragmentation.

## Using the code
This code is Windows version of FragMent(https://github.com/xinglunju/FragMent). The C portion of the module has been compiled as FragMent_C.dll file. If you want to modify the C portion of module, you should edit the FragMent_C.c and then run the following command in Windows powershell:
```
gcc -shared -o FragMent_C.dll FragMent_C.c -g
```
The new module file FragMent_C.dll will be generated in the file directory.
