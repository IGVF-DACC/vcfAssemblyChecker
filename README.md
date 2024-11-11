# vcfAssemblyChecker

This tool is developed by EBI Variation and can be downloaded here:
<https://github.com/EBIvariation/vcf-validator/releases/download/v0.10.0/vcf_assembly_checker_linux>

It assesses the correctness of a VCF file with respect to a FASTA file (that should contain the reference sequence). The assembly checker reads the CHR, POS and REF columns from the VCF, and for each line, looks into the FASTA file to see if the REF allele matches that region. A VCF file is considered valid if all the variants match the sequence in the FASTA file.

The version number is v0.10.0.
