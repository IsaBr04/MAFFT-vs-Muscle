# AI Use Log
- Tool/model & version: Google AI Overview (Gemini 3)
- What I asked for: code to compare MUSCLE and MAFFT sequence alignments
- Snippet of prompt(s): "compare alignments from muscle v5 efa file and mafft fasta file in python colab"
- What I changed before committing: changed "AlignIO.read" to "SeqIO.parse" and "fasta" to "fasta-pearson"
per the inital error about comments being present in the FASTA file
- How I verified correctness (tests, sample data): tested output by comparing an MAFFT alignment file to itself and verifying that no differences were found
