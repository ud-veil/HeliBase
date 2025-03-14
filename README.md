# HeliBase
## Helicase reference database
HeliBase is a fasta file of 174 reference helicase sequences collected by Dr. Rachel Keown, as part of her MS (Keown, 2021) and PhD (Keown, 2024) research, from UniProtKB and metagenome-assembled contigs (Keown et al, 2022; Nasko et al, 2018). Sequences represent multiple helicase superfamilies (SF) and families: SFA (RecA, UvsX), SF1 (PcrA, UvrD, Dda, RecB, RecD), SF2 (UvrB, UvsW, RecG, SNF2), SF3 (twinkle protein), and SF4 (Gp4, Gp41, DnaB).

## Rationale
The Viral Ecology and Informatics Lab (VEIL) at the University of Delaware leverages viral replication genes to investigate environmental phage, viruses that infect bacteria. Genome replication is critical to phage biology and infection phenotype. Phage replication proteins provide informative genome to phenome connections and an ability to predict genome replication biochemistry and infection phenotype from sequence data. Identifying phage replication proteins from a collection of environmental sequences requires well curated reference sequence datasets.

## HeliBase curation
HeliBase was created in 2021 (Keown, 2021) with a subset of helicase families encoded by phage as described in literature and published metagenomes. Initial reference sequences were mined from UniProtKB (release 2021_01, accessed January 30, 2021) with an emphasis on Swiss-Prot phage entries, and additional UniProtKB sequences with >60% amino acid identity were added for a total of 10-20 sequences per helicase family. SNF2 sequences were mined from metagenome- and virome-assembled contigs (Keown et al, 2022 Supplemental Table S1; Nasko et al, 2018) to include environmental representatives. Sequences from each family were annotated using the conserved domain database batch search (CDD-BATCH; Wang et al., 2023). Several entries have since been migrated to UniParc. Sequences representing additional helicase families were added in 2023 (Keown, 2024). Initial sequences were retrieved from UniProtKB SwissProt (gold) entries from model phage or bacteria. Additional UniProtKB sequences with >70% amino acid identity were added. Helicase families are each represented by 7-20 individual sequences. 
| Superfamily | Family | Num Seqs | Average Length (aa) |
| -------- | -------- | -------: | -------: |
| SFA | RecA | 7 | 361 |
|  | UvsX | 8 | 377 |
| SF1 | PcrA | 9 | 733 |
| | UvrD | 11 | 747 |
| | Dda | 10 | 439 | 
| | RecB | 12| 1122 |
| | RecD | 10 | 629 |
| SF2 | UvrB | 8 | 679 |
| | UvsW | 10 | 511 |
| | RecG | 14 | 708 |
| | SNF2 | 20 | 509 |
| SF3 | twinkle | 15 | 777 |
| SF4 | Gp4 | 20 | 544 |
| | Gp41 | 11 | 476 |
| | DnaB | 9 | 459 |

## References
Keown, R. A., 2021. "Understanding the ocean ecosystem starting with its smallest members: Improving genome to phenome approaches for studying unknown viral populations." MS thesis, University of Delaware.

Keown, R. A., 2024. "From Single Amino Acid to Environmental Ecology and Back: The Saga of DNA Polymerase I." PhD diss., University of Delaware.

Keown, R. A., Dums, J. T., Brumm, P. J., MacDonald, J., Mead, D. A., Ferrell, B. D., Moore, R. M., Harrison, A. O., Polson, S. W., & Wommack, K. E., 2022. "Novel viral DNA polymerases from metagenomes suggest genomic sources of Strand-Displacing Biochemical Phenotypes". Frontiers in Microbiology, 13, 858366.

Nasko, D. J., Chopyk, J., Sakowski, E. G., Ferrell, B. D., Polson, S. W., & Wommack, K. E., 2018. "Family A DNA polymerase phylogeny uncovers diversity and replication gene organization in the virioplankton." Frontiers in microbiology, 9, 3053.

Wang, J., Chitsaz, F., Derbyshire, M.K., Gonzales, N.R., Gwadz, M., Lu, S., Marchler, G.H., Song, J.S., Thanki, N., Yamashita, R.A. and Yang, M., 2023. "The conserved domain database in 2023." Nucleic acids research, 51(D1), pp.D384-D388.
