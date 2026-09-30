# Cell & Molecular Biology Lab Activity: Characterization of a Plastid Genome Cell and Molecular Biology

**Name:** Bahian, Celine R.
**Course:** BIO300- Cell and Molecular Biology
**Section:** B

# 1. Purpose
In this activity, you will select one plant genus with an available complete plastid genome, retrieve one complete plastid/chloroplast 
genome from a public database, upload the genome to your ownusegalaxy.org account, characterize its sequence and annotated genes, and 
document the complete exercise in a GitHub repository. 

# 2. Learning Outcomes  
Locate and verify a complete plastid/chloroplast genome in NCBI.  
Explain basic plastid-genome terms such as LSC, SSC, IR, CDS, rRNA, tRNA, intron, pseudogene,and GC content.  
Describe the overall organization and gene content of a selected plastid genome.  
Use Galaxy to upload a plastid genome and obtain basic sequence statistics.  
Compare plastid genomes with mitochondrial and nuclear genomes.  
Evaluate practical advantages and limitations of plastid genomes in biological studies.  Document the data source, analysis steps, results, and interpretation in GitHub.

# 3. Choosing and Recording a Plant Genus 

Zea

<img width="245" height="76" alt="image" src="https://github.com/user-attachments/assets/7a73f9be-d5b0-4ab8-ba16-f139dede0963" />

**Figure 1.** NCBI record for the Zea mays chloroplast complete genome (NC_001666.2), showing the 140,384 bp genome length and available GenBank
and FASTA files.

# 4. Data Source and Genome Selection 

| Item | Information |
|---|---|
| Chosen genus | *Zea* |
| Selected species | *Zea mays* |
| Common name | Maize / Corn |
| Family | Poaceae |
| Organelle | Chloroplast (plastid) |
| Genome type | Complete chloroplast genome |
| NCBI accession/version | **NC_001666.2** |
| Database | NCBI RefSeq / Nucleotide |
| Genome length | **140,384 bp** |
| Topology | Circular |
| Sequence status | Complete genome |
| Source | NCBI Nucleotide / RefSeq |
| Associated publication | Maier et al. (1995), *Complete sequence of the maize chloroplast genome: gene content, hotspots of divergence and a unique symmetry of its rRNA genes* |
| NCBI record | https://www.ncbi.nlm.nih.gov/nuccore/NC_001666.2 |

<img width="1365" height="678" alt="image" src="https://github.com/user-attachments/assets/d88dc02e-f80f-4c67-ba07-0f5856149742" />

**Figure 2.** FASTA sequence record of the selected Zea mays chloroplast complete genome (NC_001666.2) retrieved from NCBI, showing the nucleotide sequence used as the genome sequence source for the study.

# 5. Files to Obtain

| File | Format | Purpose | File/Accession |
|---|---|---|---|
| Genome sequence | FASTA | Upload to Galaxy and obtain sequence statistics | *Zea mays* chloroplast genome, **NC_001666.2** |
| Annotated genome | GenBank / RefSeq | Identify genes, coordinates, introns, pseudogenes, and other features | *Zea mays* chloroplast genome, **NC_001666.2** |
| Source information | NCBI record link / accession | Document the origin of the genome used | **NC_001666.2** — https://www.ncbi.nlm.nih.gov/nuccore/NC_001666.2 |

# 6. Galaxy Workflow 

| Statistic | Galaxy Result |
|---|---:|
| Genome length | 140,384 bp |
| Number of sequence records | 1 |
| GC content | 38.46% |
| Complete plastome represented by one sequence | Yes |

<img width="1362" height="681" alt="image" src="https://github.com/user-attachments/assets/c66a11ed-029b-44a0-82ed-dcafe0dd464c" />

**Figure 3.** Galaxy workflow for analyzing the Zea mays chloroplast genome using FASTA Statistics. The uploaded FASTA file (NC_001666.2) was 
processed to obtain sequence statistics, including genome length, nucleotide counts, and GC content.

# 7. Plastid Genome Terms to Understand 

| Term | Meaning |
|---|---|
| **Plastid genome / plastome** | The DNA found inside a plastid. In green plants, this usually refers to the chloroplast DNA. |
| **LSC** | Stands for Large Single-Copy region. It is one of the main regions of the plastid genome. |
| **SSC** | Stands for Small Single-Copy region. It is another main region of the plastid genome. |
| **IR** | Stands for Inverted Repeat region. Many plastid genomes have two copies of this region. |
| **CDS** | Means protein-coding sequence. It is a DNA sequence that contains information for making a protein. |
| **tRNA gene** | A gene that produces transfer RNA, which is involved in protein production. |
| **rRNA gene** | A gene that produces ribosomal RNA, which is part of the plastid ribosome. |
| **Intron** | A non-coding part of a gene that is removed from the RNA during RNA processing. |
| **Pseudogene** | A gene-like sequence that has lost, or may have lost, its normal function. |
| **GC content** | The percentage of guanine (G) and cytosine (C) bases in the genome. |
| **Accession** | A unique identification number given to a sequence record in a database. |
| **Annotation** | Information added to a genome that identifies genes and other important features. |

# 8. Required Plastid Genome Characterization 

| Characteristic | *Zea mays* chloroplast genome |
|---|---|
| **Genus** | *Zea* |
| **Species** | *Zea mays* |
| **Family** | Poaceae |
| **NCBI accession/version** | **NC_001666.2** |
| **Genome size** | **140,384 bp** |
| **GC content** | **38.46%** |
| **Topology** | Circular |
| **LSC size** | **82,355 bp** |
| **SSC size** | **12,536 bp** |
| **IR size** | **22,748 bp each** |
| **Number of sequence records** | **1** |
| **Total annotated genes** | **104 genes** (reported in the original complete-genome publication) |
| **Protein-coding genes** | **70** |
| **tRNA genes** | **30** |
| **rRNA genes** | **4** |
| **Introns** | Present in some annotated genes |
| **Pseudogenes / gene fragments** | Gene-like/degenerated regions have been reported |
| **Gene duplications** | Genes in the IR regions occur in two copies |
| **Overall organization** | LSC–IR–SSC–IR |

### Gene Groups Identified

| Gene group | Examples / what to look for | Main function |
|---|---|---|
| **psa** | *psa* genes | Involved in Photosystem I and photosynthesis. |
| **psb** | *psb* genes | Involved in Photosystem II and photosynthesis. |
| **atp** | *atp* genes | Encode components of ATP synthase, which helps produce ATP. |
| **pet** | *pet* genes | Encode components of the cytochrome b6f complex involved in electron transport. |
| **rbcL** | *rbcL* | Encodes the large subunit of RuBisCO, which is involved in carbon fixation. |
| **rpo** | *rpo* genes | Encode RNA polymerase components used in transcription. |
| **rpl** | *rpl* genes | Encode ribosomal proteins of the large ribosomal subunit. |
| **rps** | *rps* genes | Encode ribosomal proteins of the small ribosomal subunit. |
| **rrn** | *rrn* genes | Encode ribosomal RNA. |
| **trn** | *trn* genes | Encode transfer RNAs used during protein synthesis. |
| **matK** | *matK* | Encodes a maturase involved in RNA processing. |
| **clpP** | *clpP* | Encodes a component of a protease involved in protein processing/degradation. |
| **accD** | *accD* | Involved in fatty-acid biosynthesis. |
| **cemA** | *cemA* | A conserved chloroplast envelope membrane-associated gene. |
| **ycf** | *ycf* genes | Conserved chloroplast genes with various functions; some functions remain uncertain. |

<img width="1362" height="684" alt="image" src="https://github.com/user-attachments/assets/f66bee2f-5241-4398-bd14-f356e418fde8" />

**Figure 4.** NCBI RefSeq record used for the plastid genome characterization of Zea mays, showing the complete chloroplast genome accession 
NC_001666.2, genome size of 140,384 bp, and circular topology. The record was used to obtain information required for the characterization, 
including genome size, topology, and annotated genomic features.

# 9. Questions for the Student Report
  
**1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.**

My selected organism is Zea mays, commonly known as maize or corn. It belongs to the family Poaceae. The complete chloroplast genome was 
obtained from the NCBI RefSeq/Nucleotide database with accession NC_001666.2. The genome has a total length of 140,384 bp.

**2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or
   nuclear sequence?**

The NCBI record is specifically named “Zea mays chloroplast, complete genome.” It is also listed as an NCBI Reference Sequence (NC_001666.2).
The sequence is about 140 kb long and contains many annotated chloroplast genes, including protein-coding genes, tRNA genes, and rRNA genes.
These features show that the sequence is a complete chloroplast genome and not just a barcode gene or a small genome fragment.

**3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these
regions when available.**

Yes, the Zea mays chloroplast genome has the common LSC–IR–SSC–IR arrangement. It contains a Large Single-Copy (LSC) region, a 
Small Single-Copy (SSC) region, and two Inverted Repeat (IR) regions.

**LSC:** 82,355 bp

**SSC:** 12,536 bp

**IR:** 22,748 bp

The two IR regions are repeated parts of the genome and separate the LSC and SSC regions.

**4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes 
located in the inverted-repeat regions may appear in two copies.**

The original complete maize chloroplast genome study reported 104 genes, including 70 protein-coding genes, 30 tRNA genes, and 4 rRNA genes.
Some genes are located in the inverted-repeat regions. Since the IR regions occur twice in the genome, genes located in these regions can 
also appear in two copies. The maize chloroplast genome also contains some degenerated reading frames and gene fragments, which are related
to changes or loss of gene function.

### 5.  Choose at least eight protein-coding plastid genes from different functional groups. List eachgeneand briefly explain its biological function

| Gene | Functional Group | Function |
|---|---|---|
| **rbcL** | Photosynthesis | Helps with carbon fixation during photosynthesis. |
| **psaA** | Photosynthesis | Part of Photosystem I and helps in the light reactions. |
| **psbA** | Photosynthesis | Codes for an important protein in Photosystem II. |
| **atpA** | ATP production | Part of ATP synthase, which helps produce ATP. |
| **petB** | Electron transport | Part of the cytochrome *b6f* complex and helps with electron transport. |
| **rpoB** | Transcription | Codes for a subunit of the plastid RNA polymerase. |
| **rpl16** | Translation | Codes for a ribosomal protein involved in protein synthesis. |
| **matK** | RNA processing | Involved in the processing and splicing of some chloroplast RNAs. |

**6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with 
introns if present in your genome.**

The chloroplast genome contains rRNA genes that are important parts of the chloroplast ribosome. Examples of tRNA genes include trnK, trnL,
trnM, trnS, and trnG. These tRNAs help during protein production.Some chloroplast genes also contain introns, which are parts of RNA that 
are removed during RNA processing. Examples of intron-containing genes include rpl2 and rpl16. The matK gene is also associated with the 
intron region of trnK.

**7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. 
If none are reported, state this clearly.**

The maize chloroplast genome has some unusual features, including degenerated reading frames and gene fragments. The original study also 
reported gene transfer and gene loss involving the plastid and nuclear genomes. Gene duplication also occurs in the inverted-repeat regions
because these regions are present twice in the chloroplast genome.

**8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or 
structural observations.**

The GC content of my Zea mays chloroplast genome is 38.46%, based on my Galaxy FASTA Statistics result.

Two other notable observations are:

The genome has one sequence record with a length of 140,384 bp, representing the complete chloroplast genome.
The genome has the typical LSC–IR–SSC–IR structure, with two IR regions containing duplicated sequences.

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| **Location** | Found inside plastids, such as chloroplasts. | Found inside mitochondria. |
| **Main role** | Mainly involved in photosynthesis and other plastid functions. | Mainly involved in cellular respiration and energy production. |
| **DNA** | Contains its own DNA. | Contains its own DNA. |
| **Inheritance** | Often inherited from one parent in plants, commonly the maternal parent, but exceptions exist. | Often inherited from one parent, but the pattern can vary among organisms. |
| **Copy number** | Can have multiple copies in a cell. | Can have multiple copies in a cell. |
| **Genome organization** | Plant plastid genomes commonly have LSC, SSC, and two IR regions. | Genome organization is more variable. |
| **Gene content** | Contains genes related to photosynthesis, transcription, translation, and other plastid functions. | Contains genes mainly related to respiration and mitochondrial functions. |
| **Evolution** | Can undergo gene loss, gene transfer, and rearrangements. | Can also undergo gene loss, gene transfer, and structural changes. |

**Similarities**

1.Both are organelle genomes.

2.Both contain their own DNA.

3.Both can occur in multiple copies per cell.

4.Both contain genes needed for organelle functions.

5.Both evolved from bacterial ancestors.

**Differences**

1.Plastid genomes are found in plastids, while mitochondrial genomes are found in mitochondria.

2.Plastids are mainly associated with photosynthesis, while mitochondria are mainly associated with cellular respiration.

3.Plastid genomes contain genes related to photosynthesis, while mitochondrial genomes contain genes mainly related to respiration.

4.Plant plastid genomes commonly have LSC, SSC, and IR regions, while mitochondrial genomes have more variable organizations.

5.Their patterns of inheritance and evolutionary changes can differ.

**10. Explain the practical value of plastid genomes in research. List as many advantages as youcancompared with the nuclear genome, including nuclear sex chromosomes where applicable, andalsoexplain important limitations. Give one research question for which plastid data would be useful andone for which nuclear genomic data would be more appropriate.**

Plastid genomes are useful in many areas of plant research. They are relatively small compared with nuclear genomes and contain many genes and regions that can be used for studying and comparing plants.

**Advantages of plastid genomes**

Useful for plant species identification

Useful for DNA barcoding

Useful for phylogenetic analysis

Useful for studying evolutionary relationships

Useful for comparing closely related plant species

Useful for studying plant diversity

Useful for studying population history

Easier to analyze than the much larger nuclear genome

Contains conserved genes that can be compared between species

Useful for studying the evolutionary history of plastids

Useful in plant breeding and genetic research

**Limitations**

Plastid genomes do not contain all of the genetic information of a plant. They represent only one organelle genome, so they cannot show 
the complete genetic variation found in the nuclear genome. Plastid inheritance can also be biased toward one parent. Some traits are 
controlled by nuclear genes, so plastid DNA alone may not be enough to study them.

# Research question where plastid data would be useful

**What are the evolutionary relationships among maize and closely related grass species?**

Plastid genomes would be useful because conserved regions can be compared between different species. Research question where nuclear genomic data would be more appropriate

**Which genetic variants are associated with drought resistance in maize?**

Nuclear genomic data would be more appropriate because complex traits such as drought resistance can involve many genes located throughout the nuclear genome.

## 10. Plastid vs Mitochondrial Genome Comparison

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| **Cellular location** | Found inside plastids, such as chloroplasts. | Found inside mitochondria. |
| **Main biological functions** | Mainly involved in photosynthesis, carbon fixation, and other plastid functions. | Mainly involved in cellular respiration and energy production. |
| **Typical genome organization** | Usually a circular genome in land plants with a Large Single-Copy (LSC) region, Small Single-Copy (SSC) region, and two Inverted Repeat (IR) regions. *Zea mays* has this typical arrangement. | More variable than plastid genomes. Plant mitochondrial DNA can occur in different physical forms and can contain repeated sequences and recombined structures. |
| **Relative genome size** | Usually relatively small and conserved in land plants, commonly around 150 kb. The *Zea mays* chloroplast genome is **140,384 bp**. | Usually more variable in plants and can be much larger than plastid genomes. Some plant mitochondrial genomes are several hundred kb to more than 1 Mb. |
| **Gene content** | Contains genes involved in photosynthesis, transcription, translation, RNA processing, and other plastid functions. | Contains genes mainly involved in mitochondrial respiration and energy-related functions. |
| **Copy number** | Multiple copies of plastid DNA can occur within a cell or chloroplast. | Multiple copies of mitochondrial DNA can occur within a cell or mitochondrion. |
| **Inheritance** | Often inherited from one parent, commonly the maternal parent in many plants, but this varies among plant lineages. | Usually inherited from one parent, most commonly the maternal parent in many plants, but exceptions occur. |
| **Recombination / structural change** | Generally more structurally conserved, although recombination, gene loss, gene transfer, and rearrangements can occur. | Usually more structurally dynamic in plants. Recombination between repeated sequences can produce different genome arrangements and subgenomic forms. |
| **Mutation / substitution pattern** | Generally has relatively conserved substitution rates, although rates vary among species and genes. | Plant mitochondrial DNA often has low substitution rates in coding regions, but its mutation and structural patterns vary greatly among plant lineages. |
| **Common research applications** | Used for plant identification, DNA barcoding, phylogenetic studies, evolutionary research, species comparisons, and studying plant diversity. | Used for studying plant evolution, mitochondrial inheritance, genome rearrangements, respiration-related genes, cytoplasmic male sterility, and mitochondrial genome evolution. |

# References

NCBI Nucleotide: [https://ncbi.nlm.nih.gov/nuccore/NC_001666.2?report=fasta](https://ncbi.nlm.nih.gov/nuccore/?term=zea+plastid+complete+genome)

NCBI GenBank: https://ncbi.nlm.nih.gov/nuccore/NC_001666.2

usegalaxy.org: https://galaxy-main.usegalaxy.org/u/celinebahian/h/plastid-zea-bahian

Galaxy Training Network: https://galaxy-main.usegalaxy.org/?tool_id=toolshed.g2.bx.psu.edu%2Frepos%2Fiuc%2Ffasta_stats%2Ffasta-stats%2F2.0&version=latest

GitHub: https://github.com/celinebahian/cmb-plastid-genome--Zea---Bahian-

Maier, R. M., Neckermann, K., Igloi, G. L., & Kössel, H. (1995). Complete sequence of the maize chloroplast genome: Gene content, hotspots of divergence and fine tuning of genetic information by transcript editing. *Journal of Molecular Biology, 251*(5), 614–628. https://doi.org/10.1006/jmbi.1995.0460
