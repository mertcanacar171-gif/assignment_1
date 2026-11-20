### Question 2
In this question, the structural regions of the human TP53 gene are assigned to string variables and concatenated to form the full gene sequence.

```python
promoter = "TATAAT"
5_prime_UTR = "GCTAGC"
start_codon = "ATG"
exon1 = "GAGGAGCCGCAGTCAGATCCTAGCGTCGAGCCCCCTCTGAGTCAGGAAACATTTTCAGACCTATGGAAACT"
intron = "GTGAGTAGTGGATCTGGTGGGTTGAGTAGTGGATCTGG"
exon2 = "ACTTCCTGAAAACAACGTTCTGTCCCCCTTGCCGTCCCAAGCAATGGATGATTTGATGCTGTCCCCGGACGATATTGAACAATGGTTCACTGAAGACCCAGGTCCAGATGAAGCTCCCAGAATGCCAGAGGCTGCTCCCCCC"
stop_codon = "TGA"
3_prime_UTR = "AATTAA"

my_fav_gene = promoter + 5_prime_UTR + start_codon + exon1 intron + exon2 + stop_codon +
3_prime_UTR

print(my_fav_gene)

