# Instructions to find Peptide Matches in MaxQuant output
The Python script uploaded here helps to find if a MaxQuant raw file has peptides that form part of the FEM1B protein. After running the MaxQuant program on a particular Raw file, 
copy the "peptides.txt" file from the "combined/txt" folder, where the output of the analysis has been generated and paste it in the same directory on which this script has been downloded.
Run the Python script using the following command.
```
$ python3 Peptides_Finder.py
```
Note that the peptides.txt file should be in the same directory and its name shouldn't be changed. The output will be a list of 20 values, numbered 1 to 20. If there is no match, the values are 0.
A match yields a non-zero positive number. Then, the code can be edited to print the peptide matched and subsequently searched in the FEM1B sequence. 
