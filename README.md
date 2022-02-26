# Alineamiento-de-a-pares

conda activate analisis_de_secuencias

efetch -db #SequencesOrNucleotide -id #ID -format fasta > #Name1
efetch -db #sequences -id #ID -format fasta > #Name2
less #Name1
less #Name2

sudo apt  install eog

dottup -graph png -asequence #Name1 -bsequence #Name2
#Word size: number
eog #dottup.1.png or other name

dotmatcher -graph png -asequence #Name1 -bsequence #Name2 -windowssize #Number -threshold #Number
eog #dotmatcher.1.png or other name

needle -asequence #Name1 -bsequence #Name2
#Gap opening penalty and extension penalty #Number
