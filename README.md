# Fraction-of-Nucleotides-in-a-Strand
This program takes a nucleotide strand and provides the fraction/ratio for each nucleotide.

input='AGCTTTTCATTCTGACTGCAACGGGCAATATGTCTCTGTGTGGATTAAAAAAAGAGTGTCTGATAGCAGC'

a = 0
t= 0
c = 0
g = 0

for nt in input:
    if nt=='A':
        a=a+1
    elif nt == 'T':
        t=t+1
    elif nt == 'G':
        g=g+1
    elif nt== 'C':
        c= c+1
print (float(a)/float(len(input)))
print (float(t)/float(len(input)))
print (float(g)/float(len(input)))
print (float(c)/float(len(input)))
