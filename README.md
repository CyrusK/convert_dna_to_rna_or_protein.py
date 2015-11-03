# Convert DNA to RNA or Protein

Here is some Python script  I put together (DNA conversion above) that takes any DNA string (gDNA, cDNA, etc..) and optionally prints its RNA translation or all of the possible valid protein(s) sequences with start and stop codons included. The script will conveniently take an operation and filename of your choice from the command line and print the output.

For example:

$catdna.txt
GCGCTTGGTTTAATGACGGCTTGTTTCTTTTCTGTGGCTGCGTGAAAGCCTTGAGGGGCTCCGGGAGGGCCCTTT GTGCGGGGGGAGCGGCTCGGGGGGTGCGTGCGTGTGTGTGTGCGTGGGGAGCG

$python conversion.py --rna dna.txt
GCGCUUGGUUUAAUGACGGCUUGUUUCUUUUCUGUGGCUGCGUGAAAGCCUUGAGGGGCUCCGGGAGGGCCCUUU GUGCGGGGGGAGCGGCUCGGGGGGUGCGUGCGUGUGUGUGUGCGUGGGGAGCG

$python conversion.py --genes dna.txt

1 valid protein(s)can be produced from this sequence:
DNA: ATGACGGCTTGTTTCTTTTCTGTGGCTGCGTGA 
RNA: AUGACGGCUUGUUUCUUUUCUGUGGCUGCGUGA 
AA sequence: MTACFFSVAA

The code in this repository would be useful for anyone in biotech or pharma R&D doing big data genomic analysis.
