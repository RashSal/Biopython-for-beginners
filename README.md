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
Suppose we wanted to filter a FASTA file by length, for example exclude protein sequences less than 100 amino acids long.
you can run the following script:

filter.py
filter1.1.py
filter1.2.py

#Editing sequences

A very common task is pulling out particular sequences from a large sequence file.
Python strings, Biopython Seq and SeqRecord objects can all be sliced to extract a sub-sequence or partial record. In this case, we want to take everything up to but excluding the final letter:
you can run the following script:

edit.py

#Working with Sequence Features
Doing a print like this tries to give a human readable display. There are three key properties:
.type which is a string like CDS or gene.
.location which describes where on the genome this feature is
.qualifiers which is a puthon dictionary full of all the annotation for the feature (things like gene identifiers).

for example you can use the following scripts:

filter_2.py
total_gene_lengths.py




