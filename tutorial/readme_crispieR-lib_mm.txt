crispieR-lib.R \
  -i crispieR-lib/testmm/author/supplementary_data_2_-_mm_library.xlsx \
	-k xlsx \
	-e 1 \
	-j 1 \
	-u F \
	-g 2 \
	-n 1 \
	-z NGG \
	-a Mouse \
	-t "^ENSMUSG\\d+?_(.+?)_.+$" \
	-c 0None_none,0Safe_safe \
	-d Non-targeting,Non-targeting \
	-p testmm \
	-v crispieR-lib/data/mm39.2020-07-30.2bit,crispieR-lib/data/mm10.2021-04-08.2bit \
	-w crispieR-lib/data/mm39.refseq.exons.tsv.gz,crispieR-lib/data/mm10.refseq.exons.tsv.gz \
	-y crispieR-lib/data/MRK_List2.rpt.gz \
	-o crispieR-lib
