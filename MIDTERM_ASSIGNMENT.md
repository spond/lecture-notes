# BIOL 3111 / 5111: Genomics in Medicine & Disease (Fall 2026)
## Midterm Research Project: Multi-Omic Dissection of Human Disease

* **Assignment Weight:** 20% of Final Course Grade
* **Official Due Date:** Thursday, October 29, 2026 at 23:59 EST (Canvas Submission)
* **Early-Bird Bonus Period:** Submit between October 22 and October 28 for **+12 bonus points per day early** (up to +84 points scaled into course engagement).
* **Target Length:**
  * **Undergraduate (BIOL 3111):** ~4–5 pages of core narrative text (approx. 1,800–2,500 words), plus Title Page, Figures, Table 1 (Multi-Omic Matrix), AI Audit Table (Track A only), and Primary Bibliography. Total document length is typically 7–9 pages.
  * **Honors / Graduate (BIOL 5111):** ~5–6 pages of core narrative text (approx. 2,500–3,000 words), incorporating deeper mechanistic modeling and a dedicated clinical trial / translation section.

---

### Table of Contents
1. [Executive Summary & Scientific Mission](#1-executive-summary--scientific-mission)
2. [The Two-Track Generative AI Contract](#2-the-two-track-generative-ai-contract)
   - [Notice of Algorithmic Pre-Screening](#notice-of-algorithmic-pre-screening)
   - [Track A: AI-Assisted (Expert Reviewer Standard)](#track-a-ai-assisted-expert-reviewer-standard)
   - [Track B: 100% Human-Authored (Standard Undergrad Standard)](#track-b-100-human-authored-standard-undergrad-standard)
3. [Choosing Your Disease Focus](#3-choosing-your-disease-focus)
4. [The 8 Multi-Omic Tiers of Characterization](#4-the-8-multi-omic-tiers-of-characterization)
5. [Anti-Hallucination Guardrails: Mandatory Figures & Data Artifacts](#5-anti-hallucination-guardrails-mandatory-figures--data-artifacts)
   - [Figure 1: UCSC / Ensembl Genomic Locus Architecture](#figure-1-ucsc--ensembl-genomic-locus-architecture)
   - [Figure 2: GTEx Tissue Expression & cis-eQTL Regulation](#figure-2-gtex-tissue-expression--cis-eqtl-regulation)
   - [Figure 3: GWAS Catalog Association & Multi-Ancestry Equity Audit](#figure-3-gwas-catalog-association--multi-ancestry-equity-audit)
6. [Required Data Synthesis Tables](#6-required-data-synthesis-tables)
   - [Table 1: Multi-Omic Synthesis & Genomic Coordinates Matrix](#table-1-multi-omic-synthesis--genomic-coordinates-matrix)
   - [Table 2 (Track A Only): The Mandatory AI Audit & Fact-Check Table](#table-2-track-a-only-the-mandatory-ai-audit--fact-check-table)
7. [Citation Protocol & Zero-Tolerance Hallucination Rule](#7-citation-protocol--zero-tolerance-hallucination-rule)
8. [Document Organization & Page Budget](#8-document-organization--page-budget)
9. [Comprehensive Evaluation Rubrics (100 Points)](#9-comprehensive-evaluation-rubrics-100-points)

---

## 1. Executive Summary & Scientific Mission

In the first half of this course, we dismantled the reductionist myth that human pathology stems from isolated, single-gene defects operating in a vacuum. Disease phenotypes emerge from an interconnected cascade of biological information: **germline DNA sequence variation**, **chromosomal structural architecture**, **polygenic background**, **epigenetic chromatin conformation**, **tissue-specific transcriptomic regulation**, and **microbiome/environmental pressures**.

### Your Objective
Select **one human disease or clinical syndrome** that resonates with you personally, intellectually, or professionally. Your mission is to write a comprehensive, rigorous **Multi-Omic Diagnostic & Mechanistic Profile** dissecting how multiple layers of genomic and molecular information converge to drive the condition, determine patient risk, and shape precision therapeutics.

This project is explicitly structured to cultivate professional scientific discernment. Rather than producing generic, descriptive summaries, you will extract, analyze, and synthesize authentic data directly from public genomic databases (**ClinVar**, **gnomAD**, **UCSC Genome Browser**, **GTEx Portal**, and the **GWAS / PGS Catalog**).

---

## 2. The Two-Track Generative AI Contract

As outlined in the course syllabus, pretending that generative AI does not exist in 2026 is pedagogical malpractice. However, copying and pasting unvetted output from a Large Language Model (LLM) into a scientific report without forensic verification is scientific malpractice.

On the title page of your submission, you must explicitly declare your track:

```
[ ] TRACK A: AI-Assisted Research & Synthesis (Expert Reviewer Standard)
[ ] TRACK B: 100% Human-Authored (Traditional Undergrad Standard)
```

### Notice of Algorithmic Pre-Screening
> **Mandatory Transparency Disclosure:**  
> All submissions will pass through an automated computational screening pipeline prior to human faculty review. This pipeline executes three automated checks:
> 1. **Live Citation Verification:** Automated querying of the NCBI PubMed and Crossref APIs to confirm that every cited PMID and DOI exists, matches the cited authors, and directly discusses the claimed biological mechanism.
> 2. **Genomic Coordinate & rsID Validation:** Automated verification that reported chromosome coordinates, transcript IDs, and dbSNP rsIDs correspond to authentic entries in the **GRCh38/hg38** reference build.
> 3. **Synthetic Entropy & Boilerplate Profiling:** Analysis of semantic dispersion and syntactic markers characteristic of zero-shot commercial LLM generation.
>
> Submissions displaying unverified data, fabricated citations, or undeclared synthetic text will be flagged immediately for forensic human auditing.

---

### Track A: AI-Assisted (Expert Reviewer Standard)

* **Permitted Scope:** You are encouraged to leverage modern LLMs (Claude, ChatGPT, Gemini, Copilot, NotebookLM) as research, coding, outlining, and editing partners. You may use them to synthesize literature, draft explanatory analogies, suggest candidate eQTLs, or structure sections.
* **The Evaluative Standard:** Because an AI eliminated the mechanical friction of drafting, your submission is graded against the rigorous expectations of an **expert peer reviewer** (comparable to *Nature Genetics* or *The Lancet* reviews).
  * **Superficial Generalities Penalized:** Generic AI boilerplate (*"Crohn's disease is a multifactorial inflammatory bowel disorder affecting millions globally with substantial morbidity..."*) will be penalized aggressively.
  * **Granular Mechanistic Depth:** Every causal assertion must identify specific proteins, amino acid substitutions, structural domains, cell types, or regulatory motifs.
* **Mandatory AI Audit Table (1 Page):** You must include a dedicated 1-page table (placed immediately after the narrative text) documenting at least **two (2) specific instances** where the AI produced an error, coordinate hallucination, oversimplification, or false citation during your drafting process, accompanied by the primary literature proof that disproved it and your verified correction.
* **Zero-Tolerance Citation Policy:** Every cited claim must include an authentic **PubMed ID (PMID) or DOI**. A single fabricated citation results in an automatic zero for the bibliography and a 1-letter grade deduction on the paper.

---

### Track B: 100% Human-Authored (Traditional Undergrad Standard)

* **The Scope:** Authored entirely by you without the assistance of generative text tools. Traditional tools (grammar/spell check, Zotero/Mendeley reference managers, search engines, and PubMed queries) are completely permitted.
* **The Evaluative Standard:** Graded on standard upper-division undergraduate criteria: conceptual synthesis, clarity of reasoning, data integration, and understanding of genomic principles.
* **The Integrity Guardrail:** If an unacknowledged Track B paper is flagged by our screening pipeline for synthetic generation or unverified data artifacts, it will be treated as an intentional academic integrity violation, resulting in an automatic zero on the assignment and formal referral to the Temple University Academic Honor Board.

---

## 3. Choosing Your Disease Focus

You may select any human disease, syndrome, or clinical condition with an established or emerging genomic foundation. Choose a condition that interests you personally, relates to your future clinical ambitions, or presents a fascinating biological puzzle.

### Representative Candidate Diseases
To help you brainstorm, consider the following diverse categories:

| Category | Representative Examples | Key Multi-Omic Highlights |
| :--- | :--- | :--- |
| **Metabolic & Cardiovascular** | Type 2 Diabetes, Familial Hypercholesterolemia (*LDLR, PCSK9*), Coronary Artery Disease, Hypertrophic Cardiomyopathy (*MYH7, MYBPC3*) | High polygenic architecture (GWAS loci >200); lipid eQTLs in liver tissue; gene therapy / PCSK9 mAbs. |
| **Autoimmune & Inflammatory** | Crohn's Disease / IBD (*NOD2, ATG16L1*), Type 1 Diabetes, Celiac Disease, Rheumatoid Arthritis, Multiple Sclerosis | HLA Class II polymorphisms; gut microbiome dysbiosis; cell-type-specific eQTLs in CD4+ T-cells. |
| **Neurological & Psychiatric** | Amyotrophic Lateral Sclerosis (*SOD1, C9orf72*), Parkinson's Disease (*SNCA, LRRK2, GBA1*), Alzheimer's Disease (*APOE, TREM2*), Schizophrenia | Hexanucleotide repeat expansions; microglial single-cell transcriptomics; TAD boundary alterations; ASO therapeutics. |
| **Monogenic with Polygenic Modifiers** | Sickle Cell Disease (*HBB* + *BCL11A* enhancer), Cystic Fibrosis (*CFTR*), Spinal Muscular Atrophy (*SMN1/SMN2*), Huntington's Disease (*HTT*) | Single amino acid substitutions; modifier GWAS loci explaining variable expressivity; *Casgevy* CRISPR / Spinraza ASO therapies. |
| **Structural & Chromosomal Syndromes** | Charcot-Marie-Tooth 1A / HNPP (*PMP22* dup/del), 22q11.2 Deletion (DiGeorge), Williams-Beuren Syndrome (*7q11.23*) | Non-Allelic Homologous Recombination (NAHR); gene-dosage sensitivity; Chromosomal Microarray (CMA) detection. |
| **Pediatric & Rare Disorders** | Fragile X Syndrome (*FMR1*), Rett Syndrome (*MECP2*), Prader-Willi / Angelman Syndromes (15q11-q13 imprinting) | DNA methylation silencing; genomic imprinting; histone methylation; chromatin-remodeling complexes. |
| **Infectious Disease Susceptibility** | Severe COVID-19 / ARDS (*OAS1, TYK2, LZTFL1*), HIV-1 Control / Resistance (*CCR5-Δ32*, HLA-B*5701), Severe Malaria (*HBB, G6PD, DARC*) | Host-pathogen genetic interactions; evolutionary balancing selection; viral receptor expression in lung/immune tissue. |

*Note: If you wish to study a somatic cancer, ensure you focus on germline predisposition loci (e.g., BRCA1/2, Lynch syndrome / MMR genes, TP53 Li-Fraumeni) and their interplay with somatic mutational signatures and tissue-specific expression.*

---

## 4. The 8 Multi-Omic Tiers of Characterization

Your paper must address the following **8 Multi-Omic Tiers**. Organize your narrative into distinct, clearly titled sections matching these tiers:

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    THE 8 MULTI-OMIC CHARACTERIZATION TIERS                  │
├─────────────────────────────────────────────────────────────────────────────┤
│ Tier 1: Clinical Phenotype & Epidemiological Scaffolding                    │
│ Tier 2: Monogenic Architecture & DNA Sequence Alterations                   │
│ Tier 3: Cytogenetic & Structural Genomic Variants                           │
│ Tier 4: Statistical Genomics, GWAS & Polygenic Architecture                 │
│ Tier 5: The Regulatory Genome: Epigenomics & 3D Chromatin                   │
│ Tier 6: Functional Transcriptomics & Tissue-Specific Regulation (GTEx)      │
│ Tier 7: Metagenomics & Microbial / Environmental Influences                 │
│ Tier 8: Precision Therapeutic Countermeasures & Translation                 │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Detailed Section Requirements

#### Tier 1: Clinical Phenotype & Epidemiological Scaffolding (Macro)
* **Clinical Presentation:** Define the condition in plain, adult language. What physiological systems are compromised? What are the hallmark symptoms and age of onset?
* **Diagnostic Standard:** How is the patient currently diagnosed in a clinic (e.g., biochemical assay, neuroimaging, electrophysiology, or molecular genetic panel)?
* **Epidemiology & Burden:** What is the prevalence and inheritance mode (autosomal dominant, autosomal recessive, X-linked, or complex multifactorial)? What is the primary unmet clinical need?

#### Tier 2: Monogenic Architecture & DNA Sequence Alterations
* **Primary Locus & Gene:** Identify the primary causal gene(s) or major susceptibility genes. Provide the official HGNC gene symbol and Ensembl gene ID (`ENSG...`).
* **Molecular Variant Classes:** Detail the types of pathogenic variants observed (e.g., missense substitutions, nonsense truncations, frameshift insertions/deletions, or canonical splice-site disruptions).
* **Forensic Coordinate Reporting:** Document at least one specific, well-characterized clinical variant from **ClinVar**. Report its exact HGVS cDNA coordinate (`c.`), protein alteration (`p.`), ClinVar Variation ID (VCV...), and genomic coordinate on the **GRCh38/hg38** build.
* **Biochemical Consequence:** How does this nucleotide substitution alter the encoded protein (e.g., catalytic cleft disruption, premature termination, protein misfolding, or dominant-negative multimer formation)?

#### Tier 3: Cytogenetic & Structural Genomic Variants
* **Structural Architecture:** Are large-scale chromosomal alterations involved (e.g., copy number variants, segmental duplications, microdeletions, translocations, or repeat expansions)?
* **Mechanism of Formation:** If applicable, explain the physical mechanism mediating the rearrangement (e.g., Non-Allelic Homologous Recombination [NAHR] between flanking low-copy repeats).
* **Diagnostic Modality:** Compare how this structural alteration is detected clinically (Karyotype vs. Dual-Color Interphase FISH vs. Chromosomal Microarray [CMA] vs. NGS read-depth / paired-end Discordant Read mapping).
* *Note for purely SNV-driven diseases:* If the primary disorder is caused strictly by point mutations, examine whether structural variants in modifier genes affect severity, or explain why standard cytogenetic and CMA testing fails to detect the underlying pathogenic lesion.

#### Tier 4: Statistical Genomics, GWAS & Polygenic Architecture
* **Polygenic Component:** Is this disease purely Mendelian, or does it possess a complex, polygenic architecture driven by thousands of small-effect variants?
* **GWAS Loci:** Identify at least one robust, genome-wide significant association ($p < 5 \times 10^{-8}$) from the **GWAS Catalog** or **Open Targets Genetics**. Report the lead SNP rsID, risk allele, effect size (Odds Ratio [OR] or Beta coefficient), and $p$-value.
* **Polygenic Risk Scores (PRS):** Look up whether a PRS exists for this trait in the **PGS Catalog** (report the PGS ID, e.g., `PGS000012`). What percentage of phenotypic variance ($R^2$) or discrimination accuracy (AUC/C-index) does the score achieve?
* **Multi-Ancestry Equity Audit:** Examine the ancestry composition of the discovery GWAS cohort (e.g., % European vs. % African, Hispanic, or Asian). Critically evaluate the **multi-ancestry portability trap**: why does this PRS decay in predictive accuracy when applied to diverse cohorts (such as our urban patient population at Temple Health)?

#### Tier 5: The Regulatory Genome: Epigenomics & 3D Chromatin
* **Chromatin Conformation:** Describe the chromatin landscape surrounding the disease gene or risk SNP. Is the region located in active euchromatin or repressed heterochromatin?
* **Histone Marks & Enhancers:** Are disease-associated non-coding variants located within active regulatory elements defined by ENCODE/Roadmap Epigenomics (e.g., **H3K27ac** active enhancers, **H3K4me3** active promoters)?
* **Topologically Associating Domains (TADs):** Is the gene regulated within a specific TAD? Do structural rearrangements or boundary deletions disrupt CTCF insulation, enabling ectopic enhancer-promoter hijacking?
* **DNA Methylation & Clocks:** Does the disease involve altered CpG island methylation (5mC), genomic imprinting, or accelerated biological aging measured by Horvath epigenetic clocks?

#### Tier 6: Functional Transcriptomics & Tissue-Specific Regulation (GTEx)
* **Tissue Expression Profile:** Using data from the **GTEx Portal**, report the tissue-specific expression of the focal gene in Transcripts Per Million (TPM). Which organ systems show peak expression, and how does this correlate with patient symptoms?
* **Expression Quantitative Trait Loci (cis-eQTLs):** Does the top GWAS risk SNP (or a variant in high linkage disequilibrium) function as a *cis*-eQTL in disease-relevant tissue? Report the exact GTEx Normalized Effect Size (NES), $p$-value, and tissue type.
* **Single-Cell / Spatial Insights:** Briefly describe findings from single-cell RNA sequencing (scRNA-seq) or spatial transcriptomics in this disease. Which specific cell types (e.g., microglia, podocytes, cardiomyocytes, or endothelial subsets) drive the transcriptomic signature?

#### Tier 7: Metagenomics & Microbial / Environmental Influences
* **Microbial Ecology & Dysbiosis:** Does the gut microbiome or local tissue microbiota influence pathogenesis, disease progression, or symptom flares (e.g., depletion of anti-inflammatory commensals like *Faecalibacterium prausnitzii*, expansion of pathobionts, or loss of alpha diversity)?
* **Metabolic & Host Crosstalk:** Are specific bacterial metabolites involved (e.g., short-chain fatty acids [acetate, butyrate], trimethylamine N-oxide [TMAO], or secondary bile acids)?
* **Environmental & Viral Triggers:** Are there documented viral or environmental interactions (e.g., Epstein-Barr virus in Multiple Sclerosis, enteroviruses in Type 1 Diabetes, or specific antibiotic disruptions)?
* *Note for non-microbiome diseases:* If your selected condition has no documented direct microbiome link, explain the primary environmental/exogenous risk factors and examine how host-gene-by-environment interactions modulate disease penetrance.

#### Tier 8: Precision Therapeutic Countermeasures & Translation
* **Current Standard of Care:** What is the conventional pharmacological or surgical intervention, and what are its major limitations?
* **Genomically Targeted Therapies:** Detail how modern molecular and genomic discoveries have enabled precision therapeutic strategies:
  * Small-molecule targeted inhibitors or correctors (e.g., CFTR modulators, kinase inhibitors).
  * Antisense Oligonucleotides (ASOs) or RNA interference (e.g., splice-switching ASOs like nusinersen).
  * Gene replacement therapies (AAV vector delivery).
  * Targeted CRISPR-Cas9 genome editing (e.g., *Casgevy* BCL11A enhancer excision).
  * Microbiome therapeutics (e.g., FMT, defined consortium biotherapeutics).
* **Clinical Trial Benchmark:** Identify one active or recently completed clinical trial from **ClinicalTrials.gov** testing a precision therapeutic for this condition. Report the NCT number, phase, molecular mechanism, and primary clinical endpoint.

---

## 5. Anti-Hallucination Guardrails: Mandatory Figures & Data Artifacts

To prevent students from relying on automated zero-shot text generation, your paper **must embed exactly three (3) custom-generated figures** captured directly from live genomic databases. Generic diagrams downloaded from Google Images, Wikimedia, or review paper screenshots will receive zero credit.

Each figure must be embedded in your document with a clear title, high visual resolution, and a comprehensive, publication-grade caption (3–5 sentences) detailing the source, database build, accession numbers, and biological interpretation.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                 MANDATORY PRIMARY DATA ARTIFACT CHECKLIST                    │
├─────────────────────────────────────────────────────────────────────────────┤
│ [ ] Figure 1: UCSC Genome Browser / Ensembl Locus Architecture              │
│     * Exact GRCh38/hg38 coordinates, gene model, and ENCODE regulatory track│
│ [ ] Figure 2: GTEx Portal Expression Violin Plot or cis-eQTL Analysis       │
│     * Exact TPM or Normalized Effect Size (NES), p-value, and sample size N │
│ [ ] Figure 3: GWAS Catalog / PGS Catalog Association & Multi-Ancestry Audit │
│     * Lead SNP association plot/table + Ancestry Diversity Pie Chart        │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Figure 1: UCSC / Ensembl Genomic Locus Architecture
* **Source:** [UCSC Genome Browser](https://genome.ucsc.edu/) or [Ensembl](https://www.ensembl.org/).
* **Content:** Navigate to your focal disease gene on the **Human GRCh38/hg38** assembly.
* **Required Tracks Visible:**
  1. Base Position & Chromosome Band.
  2. NCBI RefSeq or GENCODE Gene Model (showing exons, introns, and direction of transcription).
  3. At least one ENCODE Regulation track (e.g., **H3K27ac Mark** [active enhancers/promoters], **DNase I Hypersensitivity**, or **CTCF ChIA-PET**).
* **Student Annotation:** You must add at least one callout arrow or highlight box to the image pointing directly to:
  - The exon containing the focal pathogenic mutation, OR
  - The regulatory promoter/enhancer region harboring a non-coding risk variant.
* **Caption Requirement:** State the exact genomic span (`chrN:start-end`), assembly build, transcript ID (`NM_...` or `ENST...`), and describe what the regulatory track reveals about transcriptional activity at this locus.

---

### Figure 2: GTEx Tissue Expression & cis-eQTL Regulation
* **Source:** [GTEx Portal (v8 or v10)](https://gtexportal.org/).
* **Option A (Tissue Expression):** Search your focal gene. Capture the multi-tissue RNA-seq expression violin plot showing median Transcripts Per Million (TPM) across all surveyed human tissues.
* **Option B (cis-eQTL Association):** Search your focal gene or top GWAS SNP. Capture the *cis*-eQTL violin plot demonstrating how the disease-associated genotype influences gene expression in the clinically affected tissue.
* **Student Annotation:** Highlight the clinically relevant target tissue (e.g., Brain Cortex, Liver, Whole Blood, or Terminal Ileum).
* **Caption Requirement:** Report the exact median TPM (or Normalized Effect Size [NES]), nominal $p$-value, sample size ($N$), and explain why this tissue-specific pattern matches or fails to match patient pathology.

---

### Figure 3: GWAS Catalog Association & Multi-Ancestry Equity Audit
* **Source:** [GWAS Catalog](https://www.ebi.ac.uk/gwas/) or [PGS Catalog](https://www.pgscatalog.org/) or [Open Targets Genetics](https://genetics.opentargets.org/).
* **Content:** Look up your selected disease or trait.
* **Required Elements:**
  1. Top association view: table or regional plot showing the lead associated variant (`rsID`), risk allele, and $p$-value.
  2. **The Ancestry Diversity Breakdown:** Capture the study details panel showing the sample size and ancestral composition of the discovery and replication cohorts (e.g., European, East Asian, African, Hispanic/Latino).
* **Student Annotation:** Add a callout box highlighting the percentage of non-European individuals included in the discovery study.
* **Caption Requirement:** State the total cohort size ($N_{cases}$ and $N_{controls}$), identify the lead variant, and explicitly interpret the multi-ancestry representation gap, explaining the potential risks of algorithmic bias if this genetic architecture is applied to diverse clinical populations.

---

## 6. Required Data Synthesis Tables

Your paper must include the following standardized tables to ensure rigorous data organization and forensic accountability.

### Table 1: Multi-Omic Synthesis & Genomic Coordinates Matrix
*Place Table 1 immediately after the narrative text.* This matrix synthesizes all data elements into an audit-ready format. Every single row must contain authentic accession numbers and coordinates:

| Multi-Omic Tier | Focal Element / Molecule | Database Identifier / Accession | Exact Genomic Coordinates (GRCh38) | Quantitative Parameter / Clinical Metric | Primary Reference (PMID / DOI) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Tier 1: Clinical Anchor** | Hallmark Diagnostic Biomarker | e.g., ICD-10 / OMIM # | N/A | Prevalence: e.g., 1 in 3,500 live births | PMID: 12345678 |
| **Tier 2: Monogenic DNA** | Primary Pathogenic Variant | ClinVar VCV000012345.1; dbSNP rs1234567 | e.g., chr7:117,559,590-117,559,593 | HGVS: c.1521_1523delCTT (p.Phe508del) | PMID: 2475911 |
| **Tier 3: Structural SV** | Microdeletion / CNV / NAHR | Decipher / ClinVar CNV ID | e.g., chr17:15,100,000-16,500,000 | 1.4 Mb Duplication; Copy Number = 3 | PMID: 1845112 |
| **Tier 4: Polygenic GWAS** | Top Lead Susceptibility SNP | GWAS Catalog GCST001234; rs7654321 | e.g., chr2:234,567,890 | OR = 1.28; p = 2.4 x 10^-14; Risk: [A] | PMID: 2836928 |
| **Tier 5: Epigenome** | Active Enhancer / Histone Mark | ENCODE Candidate cis-RE: EH38E... | e.g., chr7:117,500,100-117,501,200 | Strong H3K27ac signal; CTCF bound | PMID: 3272824 |
| **Tier 6: Transcriptome** | Tissue Expression & cis-eQTL | GTEx v8 / ENSG00000001234 | e.g., Lung / Pancreas | Median TPM = 42.6; eQTL NES = -0.34 | PMID: 3291309 |
| **Tier 7: Metagenome** | Microbial Taxon / Metabolite | NCBI Taxonomy / Metagenome study | N/A (Microbial genome) | 3.2-fold depletion of F. prausnitzii | PMID: 2456789 |
| **Tier 8: Targeted Rx** | Precision Therapeutic Agent | DrugBank / ClinicalTrials.gov NCT... | Target: e.g., CFTR / BCL11A | Phase 3 RCT: 14% improvement in FEV1 | PMID: 3166412 |

---

### Table 2 (Track A Only): The Mandatory AI Audit & Fact-Check Table
*Required for all Track A submissions. Place this table immediately after Table 1.*

Document at least **two (2) specific instances** where your generative AI tool (ChatGPT, Claude, Gemini, etc.) produced an incorrect claim, coordinate hallucination, oversimplified mechanism, or fabricated reference during your drafting workflow:

| # | Exact Prompt Submitted to AI | Raw AI-Generated Text Snippet | The Biological Error / Hallucination | Primary Database / Paper Disproving AI | Student's Verified Correction |
| :-: | :--- | :--- | :--- | :--- | :--- |
| **1** | *"What are the exact GRCh38 coordinates for the CFTR deltaF508 mutation?"* | *"The DeltaF508 mutation is located at chr7:117,120,016 on human genome build GRCh38."* | **Coordinate Hallucination:** The AI gave incorrect coordinates by >400 kilobases. It conflated older hg19 coordinates with GRCh38. | ClinVar Variation ID 7105 (VCV000007105.16) and Ensembl GRCh38.p14 confirm coordinate: **chr7:117,559,590-117,559,593**. | Corrected all genomic coordinate references in Section 2 and Table 1 to `chr7:117,559,590-117,559,593`. |
| **2** | *"Cite a 2023 paper on GTEx eQTLs for NOD2 in Crohn's disease."* | *"Smith et al. (2023) Nature Genetics 55:412-424 showed rs2066844 reduces NOD2 expression in ileum."* | **Citation Fabrication:** Neither Smith et al. (2023) nor that volume/page exists in Nature Genetics. rs2066844 is a coding missense SNP (R702W), not an established ileal eQTL in GTEx. | GTEx Portal v8 search for rs2066844 in Small Intestine (Terminal Ileum) shows no significant *cis*-eQTL ($p = 0.42$). Authentic paper: Khor et al. (Nature 2011, PMID: 21677750). | Removed fake citation; re-anchored Section 6 around authentic non-coding eQTL rs17221417 in ileal mucosal tissue. |

---

## 7. Citation Protocol & Zero-Tolerance Hallucination Rule

Academic credibility in biomedical science depends on the reproducibility of citations. Generative AI tools frequently synthesize plausible-sounding citations that merge real authors with imaginary journals, fake volume numbers, or non-existent PMIDs.

### Citation Rules
1. **Primary Literature Expectation:** Cite a minimum of **8–12 peer-reviewed primary literature articles** (from journals indexed in PubMed/MEDLINE). Textbooks, Wikipedia, Mayo Clinic consumer pages, and news articles may be consulted for initial orientation but do not count toward your primary literature requirement.
2. **Mandatory Persistent Identifiers:** Every single bibliographic entry must include an authentic, live **PubMed ID (PMID)** or **Digital Object Identifier (DOI)**:
   * *Example:* Snitkin, E. S., et al. (2012). Tracking a hospital outbreak of carbapenem-resistant *Klebsiella pneumoniae* with whole-genome sequencing. *Science Translational Medicine*, 4(148), 148ra116. **PMID: 22914622. DOI: 10.1126/scitranslmed.3004129**
3. **Automated Verification:** All submitted bibliographies will be evaluated by an automated script querying the NCBI Entrez API.
4. **The Penalty:** A single hallucinated, non-existent, or fundamentally fabricated reference results in an **automatic grade of zero (0%) on the Bibliography section** and a **mandatory one-letter grade deduction on the overall project**. Verify every single citation in PubMed before submitting.

---

## 8. Document Organization & Page Budget

Format your submission as a single PDF document complying with the following standards:
* **Margins:** 1.0 inch on all sides.
* **Typography:** Clean, adult serif or sans-serif font (e.g., Calibri, Times New Roman, Inter, Arial, or Georgia) at **11 pt or 12 pt**.
* **Line Spacing:** 1.15 to 1.5 line spacing (do NOT double space; avoid excessive vertical padding).
* **Headings:** Clear, numbered section headers corresponding to the Multi-Omic Tiers.

### Recommended Page Budget

| Section | Title / Content | Recommended Page Count |
| :--- | :--- | :---: |
| **Page 1** | **Title Page & Track Declaration**<br>• Project Title & Selected Disease<br>• Student Name, Temple ID, Course Code (BIOL 3111 or 5111)<br>• Explicit Track Declaration Box (Track A or Track B)<br>• Executive Abstract (~150 words) | 1 Page |
| **Pages 2–6** | **Core Multi-Omic Narrative (Approx. 4–5 Pages)**<br>• Tier 1: Clinical Phenotype & Diagnostic Standard (~0.5 page)<br>• Tier 2: Monogenic Architecture & DNA Sequence Alterations (~0.75 page)<br>• Tier 3: Cytogenetic & Structural Genomic Variants (~0.5 page)<br>• Tier 4: Statistical Genomics, GWAS & Polygenic Architecture (~0.75 page)<br>• Tier 5: The Regulatory Genome: Epigenomics & 3D Chromatin (~0.75 page)<br>• Tier 6: Functional Transcriptomics & Tissue-Specific Regulation (~0.75 page)<br>• Tier 7: Metagenomics & Microbial / Environmental Influences (~0.5 page)<br>• Tier 8: Precision Therapeutic Countermeasures & Translation (~0.5 page)<br>*(All 3 figures embedded within or adjacent to relevant text)* | ~4.5–5 Pages |
| **Page 7** | **Table 1: Multi-Omic Synthesis & Genomic Coordinates Matrix** | 1 Page |
| **Page 8** | **Table 2: AI Audit & Fact-Check Table** *(Track A Submissions Only)* | 1 Page *(Track A)* |
| **Page 8 or 9** | **Primary Literature Bibliography**<br>• All references formatted with authentic PMIDs and DOIs | ~1–1.5 Pages |

---

## 9. Comprehensive Evaluation Rubrics (100 Points)

Your submission will be evaluated using a detailed 100-point rubric. Note the distinct evaluative emphasis between Track A and Track B:

| Category | Points | Track A Criteria (Expert Reviewer Standard) | Track B Criteria (Traditional Undergrad Standard) |
| :--- | :---: | :--- | :--- |
| **1. Multi-Omic Breadth & Integration (Tiers 1–8)** | **30 pts** | All 8 tiers evaluated with extraordinary mechanistic depth. Biological connections between tiers (e.g., how an eQTL in Tier 6 mechanistically explains a GWAS hit in Tier 4) are explicitly traced. Zero superficial filler. | All 8 tiers addressed clearly with solid conceptual understanding. Accurate descriptions of molecular mechanisms without major gaps. |
| **2. Data Artifacts & Database Figures (Figs 1–3)** | **25 pts** | Figures 1, 2, and 3 are impeccably captured from UCSC, GTEx, and GWAS Catalog. Student annotations are precise. Captions report exact coordinates, TPM, NES, $p$-values, and an insightful Multi-Ancestry Equity critique. | Figures 1, 2, and 3 are correctly captured from required databases and embedded with clear labels. Captions explain the essential biological findings accurately. |
| **3. Table 1: Multi-Omic Synthesis Matrix** | **15 pts** | 100% complete and verified. Coordinates match GRCh38; ClinVar, dbSNP, Ensembl, and PGS identifiers are completely accurate and audit-ready. | Table 1 is fully completed with accurate identifiers, coordinates, and metrics for all tiers. |
| **4. AI Audit Table (Track A) OR Human Depth (Track B)** | **15 pts** | **Track A:** Includes an exceptional 1-page AI Audit Table detailing $\ge 2$ authentic AI errors/hallucinations with primary literature refutations and student corrections.<br>**Track B:** Evaluated on originality of voice, personal synthesis, and nuanced interpretation of complex clinical trade-offs. | Same standard applied to the respective track declaration. |
| **5. Scientific Rigor, Clarity & Citation Integrity** | **15 pts** | Zero-tolerance citation audit: 100% of references verified in PubMed with authentic PMIDs/DOIs. High-level academic tone, active voice, right-branching syntax, and define-in-stride appositives. | All citations are authentic and verified in PubMed with PMIDs/DOIs. Well-written, clearly organized, and grammatically sound. |
| **Total** | **100 pts** | | |

---

### Critical Deadlines & Early-Bird Bonus Schedule

* **Official Deadline:** **Thursday, October 29, 2026 at 23:59 EST** via Canvas.
* **Early-Bird Bonus Schedule:**
  * Submit on or before **Oct 22 (+7 days):** **+84 Course Points**
  * Submit on **Oct 23 (+6 days):** **+72 Course Points**
  * Submit on **Oct 24 (+5 days):** **+60 Course Points**
  * Submit on **Oct 25 (+4 days):** **+48 Course Points**
  * Submit on **Oct 26 (+3 days):** **+36 Course Points**
  * Submit on **Oct 27 (+2 days):** **+24 Course Points**
  * Submit on **Oct 28 (+1 day):** **+12 Course Points**
  * Submit on **Oct 29 (Due Date):** Standard grading.
* **Late Penalty:** Submissions after October 29 lose **10 points per day late**. No assignments accepted after November 3 without prior documented university medical excuse.

---

### Questions & Support
* **Canvas Muddiest Point Forum:** Post questions regarding database navigation, eQTL queries, or disease selection.
* **Instructor Office Hours:** Sergei Pond (SERC 644 / by appointment via Canvas).
* **Teaching Assistant:** Violet Lange ([violet.lange@temple.edu](mailto:violet.lange@temple.edu)).
