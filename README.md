# DnaKata
A kata based on DNA sequence parse and analyze

DNA corp is the future of biotech!

We want to create a revolutionary  DNA manager.
it will take a plain text file as input and a plain text file as output.

#Features:
Delete invalid nucleobase (Only ATGC are valid)

Reverse the sequence (reverse)

Input.txt >> 
reverse
ATGC

Output.txt >>
CGTA


Count repetition of a given fragment (count fragment)

Input.txt >> 
Count  GA
GATTACA

Output.txt >> 
1


Insert a fragment at given position (insert fragment position)

Input.txt >> 
insert GA 4
GATTACA

Output.txt >> 
GATTGAACA


Complete a DNA sequence (complete)

Input.txt >> 
complete
GATTACA

Output.txt >> 
GATTACA
CTAATGT

Insérer un TAG (tag tagContent fragmentToTag)
Input.txt >> 
tag junk ACA
GATTACA

Output.txt >> 
GATTACA
        |junk


