Repo Structure

.
├── Church
│   ├── Church_ORF
│   │   ├── SeqNAM_Church_ORF.fa
│   │   └── orfipy_2024_03_28_23_27_11.935416.log
│   ├── Church_subsequence.ipynb
│   ├── SeqNAM_Church.fa
│   ├── SeqNAM_Church_subseqs.fa
│   ├── src_boise_conversion.ipynb
│   └── src_boise_jsnn.jpg
├── README.txt
├── Random
│   ├── Random_ORF
│   │   ├── orfipy_2024_03_28_16_21_30.675255.log
│   │   └── random_subseq_orfs.fa
│   ├── random_sequence.fa
│   └── random_sequence_generator.ipynb
└── Seqnam
    ├── SeqNAM-wetlab.jpg
    ├── orfipy_2024_03_28_16_38_22.814443.log
    ├── seqNAM.fasta
    └── seqnam_orfs.fa

6 directories, 16 files


File Descriptions
Church
	src_boise_conversion.ipynb converts the src_boise_jsnn.jpg image into a nucleic acid sequence and produces the SeqNAM_Church.fa file.
	Church_subsequence convers the SeqNAM_Church.fa file into subsequences of length 368 and outputs the SeqNAM_Church_subseqs.fa file.
	Church_ORF contains all of the found ORF's after running orfipy on the SeqNAM_Church_subseqs.fa file.


Random
	random_sequence_generator.ipynb generates a random sequences and outputs the random_sequence.fa file
	Random_ORF contains all of the found ORF's after running orfipy on the SeqNAM_Church_subseqs.fa file.

Seqnam
	SeqNAM.fasta is the fasta file containing the sequences to encode the src_boise_jsnn.jpg file found in the Church subdirectory.
	seqnam_orfs contains all of the found ORF's after running orfipy on the seqNAM.fasta file.
