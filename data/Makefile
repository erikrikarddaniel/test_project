all: final_sequences.co.alnfaa ampliseq.ASV_tables.tsv.gz bac120_metadata_r207.tsv

final_sequences.co.alnfaa:
	wget https://raw.githubusercontent.com/LNUc-EEMiS/reference_phylogenies/master/ring-hydroxylase_alpha/final_sequences.co.alnfaa

ampliseq.ASV_tables.tsv.gz:
	scp rackham:projects/pinhassi_sequencing/ampliseq.ASV_tables.tsv.gz .

bac120_metadata_r207.tsv:
	wget https://data.gtdb.ecogenomic.org/releases/release207/207.0/bac120_metadata_r207.tar.gz
	tar xzf bac120_metadata_r207.tar.gz
