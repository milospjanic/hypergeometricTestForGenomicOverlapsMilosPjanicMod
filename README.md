# hypergeometric-test-for-genomic-overlaps

# Example usage

**./hypergeometric.sh file1.bed file2.bed background.bed**

# Example output 

**./hypergeometric.sh file1.bed file2.bed background.bed**
Number of uniq A overlapping B in genomic background 360

Number of uniq B overlapping A in genomic background 365

Number of uniq A not overlapping B in genomic background 3670

Number of uniq B not overlapping A in genomic background 45854

Number of genomic background not overlapping A or B 2229526

Hypergeometric p-value will be calculated with phyper in R as phyper(A-B overlap in BG, A no B in BG, total BG minus BG-A overlap, B no A in BG, lower.tail = FALSE, log.p = FALSE)

Hypergeometric p-value:

[1] 2.568593e-129

 num 2.57e-129
