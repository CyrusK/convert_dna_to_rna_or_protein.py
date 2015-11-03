# Convert DNA to RNA or Protein

Here is some Python script that I put together that takes a any DNA sequence (gDNA, cDNA, etc..) of any length and optionally prints its RNA translation or all of the possible valid protein(s) with start and stop codons included. The script will conveniently take an operation and filename of your choice from the command line and print the output

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

