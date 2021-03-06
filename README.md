# nora-projects
These are all my projects using Python 3. With the exception of [guessinggame.py](https://github.com/nora-nz/nora-projects/blob/main/guessinggame.py) they are solutions to bioinformatics-related programming challenges found on rosalind.info.

## GC content of random-length nucleotide sequences
[Rosalind_GC_content.py](https://github.com/nora-nz/nora-projects/blob/main/Rosalind_GC_content.py) takes in a file containing FASTA format tags associated with nucleotide sequences. I used RegEx to separate tags from sequences and order them into key-value pairs. The percentage of G and C nucleotides is then calculated, compared and the tag of the highest percentage sequence is returned. 

## Hamming distance
[Rosalind_Hamming_distance.py](https://github.com/nora-nz/nora-projects/blob/main/Rosalind_Hamming_distance.py) compares two nucleotide sequences and returns how many differences there are between - also called the Hamming distance.

## Recurrence relation
[Rosalind_Recurrence_relations.py](https://github.com/nora-nz/nora-projects/blob/main/Rosalind_Recurrence_relations.py) returns the final item of a sequence based on the number of recurrences and a rate defining coefficient in the context of rabbit populations. In a challenge I am currently working on the logistic map is further complicated by an additional coefficient.

## RNA translation
[Rosalind_Translate_RNA_into_protein.py](https://github.com/nora-nz/nora-projects/blob/main/Rosalind_Translate_RNA_into_protein.py) translates nucleotide codons into an amino acid sequence. I used a dictionary which contains codons as keys and single letter amino acid codes as values. The stop codons insert a space instead of "Stop". A potential improvement for the future could be to only start an amino acid sequence if a methionine residue is found.

## Guessing game
[guessinggame.py](https://github.com/nora-nz/nora-projects/blob/main/guessinggame.py) is the first program I made after a beginner Python course. It is an interactive game where the program scans the user's input, compares it with a dictionary and returns yes/no answers if the user's guess is an attribute of the object of the current round.
