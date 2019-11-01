Adenosine sequence

Locates the position of stretches containing only adenosine in a protein.

Usage:
python adenosine_sequence.py -F proteome.fasta -O output.csv -N 10 -P 999999 -I 0

-F [required]: Fasta archive containing proteins list
-O [required]: Output file in csv format
-N [required]: Insert wanted number of adenosines in a roll
-P [optional]: Position of the last amino acid of each protein to be searched for
-I [optional]: Position of the last amino acid of each protein to be searched for
