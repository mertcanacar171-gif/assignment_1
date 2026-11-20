# MOBG2143 - Assignment 1 (Group 1)

## Group Members
* `mertcanacar171-gif`: Mert Can Acar
* `furki16bursa`: Furkan Turhan
* `Raxacorri`: Vaha Dipçin

## Assignment Questions

\# Student 1's Answer to Question 1



\*\*Q1.\*\* Please assign values to 5 different variables each corresponding to a different simple data type that exist in the Python language. Please pay attention for the \[PEP 8](https://www.python.org/dev/peps/pep-0008/) conventions in choosing variable names!



\*\*Answer:\*\*



```python

is\_coding\_region = True

gc\_content\_ratio = 0.58

exon\_count = 11

target\_gene\_name = "TP53"

mutation\_note = None

```


### Question 2
In this question, the structural regions of the human TP53 gene are assigned to string variables and concatenated to form the full gene sequence.

```python
promoter = "TATAAT"
five_prime_UTR = "GCTAGC"
start_codon = "ATG"
exon1 = "GAGGAGCCGCAGTCAGATCCTAGCGTCGAGCCCCCTCTGAGTCAGGAAACATTTTCAGACCTATGGAAACT"
intron = "GTGAGTAGTGGATCTGGTGGGTTGAGTAGTGGATCTGG"
exon2 = "ACTTCCTGAAAACAACGTTCTGTCCCCCTTGCCGTCCCAAGCAATGGATGATTTGATGCTGTCCCCGGACGATATTGAACAATGGTTCACTGAAGACCCAGGTCCAGATGAAGCTCCCAGAATGCCAGAGGCTGCTCCCCCC"
stop_codon = "TGA"
three_prime_UTR = "AATTAA"

my_fav_gene = (promoter + five_prime_UTR + start_codon + exon1 +
               intron + exon2 + stop_codon + three_prime_UTR)

print(my_fav_gene)


'''
