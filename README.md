# cudadapt




cutadapt --trim-n -a GATCGGAAGAGCACACGTCTG -a AGAGCACACGTCTG <input.file> | cutadapt -u 3 -a A{100} --no-indels -e 0.16666666666666666 - | cutadapt -O 8 --match-read- wildcards -g GTTCAGAGTTCTACAGTCCGACGATCSSS -m 18 -o <output.file> -




