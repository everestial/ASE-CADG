
a python script for writing the phased-block index values and phased-genotype values as text file.
The python script should be run exclusively on `python3` and the "output table" is used for downstream `phase-extender` and `phase-stitcher`.

The test files: input and expected output files are included.

Usage:

    python3 vcf_to_table-v2.py --vcf input_test.vcf --out expected_output_table.txt --unphased yes

