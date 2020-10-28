# Process txt files for citations	

Using `python3 grobid-text-client.py --input ./input/FILENAME.txt processCitation` will tread every newline as a single citation.

If it does not work, have a look at the source code of the file grobid-text-client.py. 

To save the output, the script assumes there is a folder called input again in the input folder. This can most likely be fixed in a simple manner. Again have look at the source.

The original file is from [Github](https://github.com/darjusp/contribs/blob/master/grobid-client.py). 
