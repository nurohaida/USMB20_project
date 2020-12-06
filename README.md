# USMB20_project

1.This wrapper script "haida_post_assembly.pl" calls the bash script "haida_post_assembly.bash" that   takes Spades assembled contig file ('contigs.fasta')  and list out filtered contigs with filter_coverage_kmer >5 and min length >=200
2.The listed files were subjected to second perl script "fastagrep.pl" by Tim Booth that will fetch the passed criteria contigs list fasta from the the source assembly.
