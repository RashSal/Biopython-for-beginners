# Biopython-for-beginners
This respiratory contains biopython codes that cane help to edit, filter, search, count and do many other cool stuff with DNA sequences obtained from various biological material :)

#Reading Sequence Files in Biopython
Dealing with assorted sequence file formats is one of the strengths of Biopython. 
The primary module we'll be using is Bio.SeqIO, which is short for sequence input/output (following the naming convention set by BioPerl's SeqIO module).
https://biopython.org/wiki/SeqIO
example scripts:
1. beg_extract_seq.py
2. count_fasta.py
3. count_record.py

#Checking proteins starting with methionine

The following scripts can be used to check all the protein sequences starting with a methionine (represented as the letter "M" in the standard IUPAC single letter amino acid code), and to count how many records fail this. 

example scripts:
1. check_start_met.py
2. check_start_met_1.py

#Converting a sequence file

For example, we have the E. coli K12 chromosome as a FASTA file NC_000913.fna and as a GenBank file NC_000913.gbk. Suppose we only had the GenBank file, and wanted to turn it into a FASTA file, how can we do it. The following scripts can help ypu with that.

convert.py

#Filtering a sequence file

