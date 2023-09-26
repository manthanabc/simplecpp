# simplecpp
This project aims to be a simple alternative to IITB's simplecpp, its a wrapper over madison unis version of turtle [link here](https://w3.cs.jmu.edu/lam2mo/cs240_2015_08/turtle.html)
note that this basic wrapper only include turtle specific parts of the simplecpp library enought to get past your assignments and the output is an image file not a window, ahem making it cross platform (tested on windows and linux) so its a feature  not a bug.

# Usage
put the simplecpp file in same directory as your project file and use "" instead of <> while including simplecpp and rest should be the same
then make sure to use g++ (or any other cpp compiler) to compile your projects 
``` g++ to.c ```
and then execute a.exe to generate the image the result would be stored in resultant output.bmp file

# Miscellaneous
make sure to call the wait funtion as it saves the image and default resolution is 300x 300 which you can change if you want to.
