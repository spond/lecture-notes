# BIOL 3111 / 5111: Genomics in Medicine & Disease (Fall 2026)
## Final Capstone Research Project: End-to-End Translational & Therapeutic Dossier
*From Molecular Target to Clinical Trial Forensics, Pharmacogenomic Safety Gates, and AI/Policy Audit*

* **Assignment Weight:** 300 Points (30% of 1,000 Total Course Points)
* **Official Due Date:** Tuesday, December 15, 2026 at 23:59 EST (Canvas Submission)
* **Early-Bird Bonus Window:** Submit between **Tuesday, December 8 and Monday, December 14, 2026** for up to **+60 bonus points** (maximum 20% bonus on the assignment, equivalent to 6% of the entire course grade or two full letter grades on the project).
* **Mandatory Non-Overlap Rule (Fresh Topic Required):**
  * You **must select a brand-new disease, drug, or therapeutic modality** that does **not** overlap with your Midterm Research Project disease. Self-plagiarism or recycling narrative text/figures from the Midterm will receive an automatic zero on the overlapping sections.
* **Collaboration Policy:**
  * **Solo or Teams of Two (2):** Students may complete the Capstone individually or in **teams of exactly two (2)** (either keeping their Midterm partner on a new topic, forming a new pair, or working solo).
  * **Single Joint Submission:** Teams upload **one unified PDF/Word manuscript** on Canvas with both authors' full names, Temple AccessNet IDs, email addresses, enrollment track, and a **CRediT Author Contribution Statement**.
* **Target Length & Scope:**
  * **Standard Undergraduate Track (`BIOL 3111`):** ~6–8 pages of core narrative text (~2,500–3,400 words), **4 mandatory empirical database figures**, **Table 1 (8 Translational Tiers)**, **Table 2 (Track A AI Audit & Clinical Stress-Test Table)**, and **12–15 verified peer-reviewed primary references**. Total document length is typically 9–12 pages.
  * **Honors / Graduate Track (`BIOL 3111 Honors / BIOL 5111`) — ~40% Expanded Scope:** ~8–9 pages of core narrative text (~3,600–4,500 words), **Dual-Trial Comparative Audit** (comparing a pivotal approval trial against a confirmatory, negative, subgroup, or real-world trial), **5 mandatory database figures** (adding **Figure 5**: 3D Structural Resistance Binding-Pocket Model or Clonal/Phylodynamic Escape Trajectory), **Table 1 expanded to 9 Tiers** (adding **Tier 9: Acquired Resistance, Clonal Escape & Next-Generation Countermeasure Engineering**), and **18–24 verified primary references**. Total document length is typically 12–15 pages.
  * *Note on Mixed Teams:* If an Honors or Graduate student pairs with a Standard undergraduate, the joint paper must fulfill the **Honors / Graduate Track specification** in full.

---

## 1. Executive Summary & Scientific Mission

While the Midterm Research Project dissected the multi-omic *causes* of human disease (Weeks 1–7: germline variants, structural CNVs, GWAS/PRS, chromatin conformation, and GTEx eQTLs), the second half of **Genomics in Medicine** (Weeks 8–14) confronts a harder clinical reality: **How do we translate a molecular target into a safe, effective therapy that actually improves human survival without poisoning genetically susceptible patients?**

### Your Mission
Select **one precision therapeutic regimen, targeted drug, biologic/cell therapy, or pharmacogenomic intervention** (either from the 20 pre-vetted dossiers in the [Interactive Final Capstone Explorer](final.html) or an instructor-approved custom topic distinct from your Midterm). You will author a publication-grade **End-to-End Translational & Therapeutic Dossier** that traces your chosen therapy across the complete translational pipeline:
1. **Molecular Target & Somatic/Immunogenomic Mechanism** (`cBioPortal`, `COSMIC`, `AlphaFold / PDB`, `ClinVar`)
2. **Drug Engineering, Delivery Route & Formulation Architecture** (Small molecule `-ib`, mAb/ADC `-mab`, CAR-T `-cel`, ASO/siRNA, or CRISPR; oral first-pass vs. parenteral delivery)
3. **Forensic Clinical Trial Audit** (`ClinicalTrials.gov` NCT record, Intention-to-Treat vs. Per-Protocol, Kaplan–Meier / Hazard Ratio, NNT, surrogate endpoint validity, and demographic representation)
4. **Pharmacogenomic ADME & Toxicity Safety Gate** (`ClinPGx` / `CPIC` Level 1A/A dosing rules, Star-Allele Activity Score math, prodrug vs. active-drug risk inversion, and multi-ancestry allele frequencies)
5. **Pharmacoeconomics, Bioethics, Press-Release Hype Audit & Clinical AI Stress-Test** (`$/QALY`, `GINA`/privacy, FDA label vs. marketing claims, and testing how a frontier LLM handles a complex clinical edge case).

---

## 2. The Regimen-Wide Pharmacogenomics (`PGx`) Rule

A common question arises when selecting cutting-edge biologics (`-mab`), Antibody–Drug Conjugates (`ADCs`), CAR-T cell therapies (`-cel`), or CRISPR gene therapies (`Casgevy`): *"Monoclonal antibodies and gene therapies are not metabolized by hepatic CYP450 enzymes—how do I complete the Pharmacogenomics Tier?"*

> **The Regimen-Wide PGx Rule:**  
> Real patients never receive a precision therapy in a biological vacuum. If your primary drug is a small molecule with a direct `CPIC` / `FDA` pharmacogene (e.g., clopidogrel/`CYP2C19`, warfarin/`CYP2C9+VKORC1`, codeine/`CYP2D6`, tamoxifen/`CYP2D6`, abacavir/`HLA-B*57:01`, simvastatin/`SLCO1B1`), you will audit that primary gene–drug pair.  
> **If your primary therapy is a biologic, ADC, CAR-T, ASO, or gene therapy**, you must audit the mandatory **`CPIC` / `ClinPGx` pharmacogene governing its combination chemotherapy backbone, conditioning regimen, pre-medication, or toxicity-rescue drug**:
> * **Oncology mAbs / PARP Inhibitors / ADCs (e.g., Olaparib after FOLFIRINOX; T-DXd DXd payload / Capecitabine control):** Audit **`DPYD`** (`*2A`, `HapB3` for `5-FU`/capecitabine) and **`UGT1A1*28/*6`** (for irinotecan `SN-38` or topoisomerase payload clearance).
> * **CAR-T Cell Therapy & Leukemia Biologics (e.g., Tisagenlecleucel, Venetoclax):** Audit **`G6PD` deficiency** for mandatory **rasburicase** tumor lysis syndrome (`TLS`) prophylaxis, plus **`TPMT` + `NUDT15`** (`6-mercaptopurine` maintenance).
> * **CRISPR / Stem-Cell Conditioning (e.g., Casgevy in Sickle Cell):** Audit **`GSTP1`/`GSTA1`** myeloablative busulfan conditioning pharmacokinetics and **`CYP2D6`** opioid pain crisis management.
> * **Anti-Amyloid mAbs & Immune Checkpoint Blockade:** Audit **`APOE ε4/ε4`** homozygote ARIA-E/H cerebral hemorrhage gating (Lecanemab/Donanemab) or **`HLA` class I/II** allele associations with immune-related adverse events (`irAEs`).

---

## 3. The Honors & Graduate Track Addendum (`BIOL 3111H / BIOL 5111` — +40% Scope Expansion)

| Dimension | Standard Track (`BIOL 3111`) | Honors / Graduate Track (`BIOL 3111H / BIOL 5111`) | Scope Expansion |
| :--- | :--- | :--- | :---: |
| **Core Narrative Length** | ~6–8 pages (~2,500–3,400 words) | **~8–9 pages (~3,600–4,500 words)** | **+35–40% text length** |
| **Clinical Trial Audit (Tiers 4–5)** | 1 pivotal Phase 2/3 `ClinicalTrials.gov` NCT trial | **Dual-Trial Comparative Autopsy:** Compare **2 NCT trials** (e.g., pivotal approval trial vs. confirmatory, negative, subgroup, or ancestry-divergent trial such as `EU-PACT` vs. `COAG`, `DESTINY-Breast04` vs. `06`, `BELLINI` vs. `CANOVA`, `PREPARE` vs. `TAILOR-PCI`) | **2-Trial Comparative Matrix** |
| **Translational Tiers (Table 1)** | 8 Translational Tiers (Tiers 1–8) | **9 Translational Tiers:** Adds **Tier 9: Acquired Resistance, Clonal Escape & Next-Generation Countermeasure Engineering** | **+1 Full Section & Matrix Row** |
| **Mandatory Empirical Figures** | **4 Figures:**<br>1. Target/Somatic/3D Pocket<br>2. `ClinicalTrials.gov` Design/Endpoint<br>3. `ClinPGx` / `CPIC` + Ancestry<br>4. AI Stress-Test / FDA Equity Audit | **5 Figures (Mandatory Figure 5 added):**<br>Figures 1–4 **PLUS Figure 5: 3D Structural Resistance Binding-Pocket Model (`AlphaFold/PDB`) OR Clonal/Phylodynamic Escape Trajectory (`cBioPortal/Nextstrain`)** | **+25% Figure Requirement** |
| **Primary Literature Bibliography** | **12–15 peer-reviewed articles** (verified PMIDs/DOIs) | **18–24 peer-reviewed articles** (verified PMIDs/DOIs) | **+50% Citation Depth** |
| **Total Document Length** | Typically 9–12 pages | **Typically 12–15 pages** | **~40% Overall Expansion** |

---

## 4. The Eight Core Translational Tiers (+ Tier 9 for Honors/5111)

Address every tier in a dedicated, clearly numbered section of your manuscript:

1. **Tier 1: Disease Pathophysiology & The Unmet Therapeutic Bottleneck**
   * Define the clinical condition, anatomical site, staging/severity metrics, and why historical standard-of-care therapy (e.g., non-selective cytotoxic chemotherapy, empirical trial-and-error dosing) fails or produces unacceptable toxicity.
2. **Tier 2: Molecular Target Architecture & Somatic / Immunogenomic Landscape**
   * Identify the exact molecular target (HGNC symbol, Ensembl ID, GRCh38 coordinates, protein domain architecture). For oncology topics, query **`cBioPortal`** or **`COSMIC`** to report the somatic mutation frequency, hotspot amino acid substitutions (e.g., `KRAS p.Gly12Cys`, `EGFR p.Leu858Arg`), or mutational signature (`SBS`). For non-oncology topics, report the `ClinVar` pathogenic alleles, `HLA` binding pocket residues, or target expression profile.
3. **Tier 3: Precision Therapeutic Engineering, Delivery Route & Formulation**
   * Classify the therapeutic modality (`-ib` kinase/allosteric inhibitor, `-mab` antibody/ADC, `-cel` CAR-T, gapmer ASO, GalNAc-siRNA, or CRISPR-Cas9). Explain why the drug is delivered via its specific **route of administration** (oral tablet vs. IV infusion vs. intrathecal injection vs. inhalation), how its **formulation/packaging** (prodrug ester mask, enteric coating, lipid nanoparticle, viral vector, or antibody linker) navigates physiological barriers, and whether it undergoes **hepatic first-pass extraction**.
4. **Tier 4: Pivotal Clinical Trial Architecture & Endpoint Forensics (`ClinicalTrials.gov`)**
   * Retrieve the pivotal trial record from **`ClinicalTrials.gov`** (report the exact `NCT` number, phase, enrollment size $N$, inclusion/exclusion biomarker criteria, randomization ratio, and blinding scheme). Critique the **control arm fairness** (was the control group given current best standard of care?) and evaluate whether the primary endpoint is a true clinical outcome (**Overall Survival [OS]** / symptom resolution) or a **surrogate endpoint** (`PFS`, `ORR`, lab biomarker)—explicitly testing for the **Surrogate Paradox**.
5. **Tier 5: Biostatistical Efficacy, Number Needed to Treat (`NNT`) & Trial Diversity Audit**
   * Extract the primary statistical outcomes: **Hazard Ratio (`HR`)** or **Odds Ratio (`OR`)**, $95\%$ confidence interval, $p$-value, **Absolute Risk Reduction (`ARR`)**, and calculate the **Number Needed to Treat (`NNT = 1 / ARR`)**. Audit the trial's **Baseline Demographic Table**: report the exact percentage of Black, Hispanic, Asian, and White participants enrolled, and critique whether the trial cohort reflects the real-world patient population. *(Honors/5111: Perform a head-to-head comparative analysis of your **two** selected NCT trials).*
6. **Tier 6: Pharmacogenomic ADME & Toxicity Safety Gate (`ClinPGx` / `CPIC`)**
   * Query **`ClinPGx` (`PharmGKB`)** and **`CPIC Guidelines`** for the pharmacogene governing your drug or regimen (see Section 2). Report the key star alleles (`*2`, `*3`, `*5`, `*17`, `*28`) or `rsIDs`, calculate the **CPIC Activity Score (`AS`)** across Normal, Intermediate, Poor, and Ultrarapid Metabolizers, explain whether the drug is an **active parent drug or an inactive prodrug** (and how that inverts PM vs. UM risk), evaluate **phenoconversion** risks from co-medications, and compare allele frequencies across global ancestry groups in **`gnomAD`**.
7. **Tier 7: Bioethics, Pharmacoeconomics, Health Policy & Access Equity**
   * Analyze the real-world societal translation of the therapy: report the **Wholesale Acquisition Cost (`WAC`)** per course/year, evaluate cost-effectiveness (`ICER` in `$/QALY` relative to the `$100,000–$150,000/QALY` threshold), examine insurance prior-authorization bottlenecks, and discuss relevant genomic policy/ethical dimensions (`GINA` employment vs. life-insurance gaps, direct-to-consumer raw-data false positives, or global south access disparities).
8. **Tier 8: The Hype vs. Reality Verdict & Clinical AI Stress-Test**
   * **Part A (Press-Release Hype Audit):** Locate an official pharmaceutical company press release, news headline, or DTC advertisement for the therapy and contrast its framing (e.g., boasting of relative risk reduction or surrogate response) against the actual **FDA Package Insert Boxed Warnings** and Overall Survival data.
   * **Part B (Clinical AI Edge-Case Stress-Test):** Submit a complex clinical vignette—combining your disease/drug with a high-risk `CPIC` pharmacogenomic diplotype (or an unphased *cis/trans* / phenoconversion trap)—to a frontier LLM (ChatGPT, Claude, or Gemini). Document what the AI got right, where it over-generalized, omitted an ancestry-specific allele, or hallucinated a dosing rule, and write the verified clinical consult note.
9. **Tier 9 (Honors / `BIOL 5111` Requirement): Acquired Resistance, Clonal Escape & Next-Generation Countermeasures**
   * Dissect the Darwinian evolutionary trajectory by which tumors, pathogens, or host immune systems escape your therapy (e.g., on-target gatekeeper mutations like `EGFR C797S`, `KRAS Y96D`, `BRCA2` frame-restoring reversion indels, `CD19` exon-2 skipping, or anti-AAV neutralizing antibodies). Propose and evaluate a concrete next-generation countermeasure (e.g., 4th-generation allosteric inhibitor, bispecific CAR-T, ctDNA *cis/trans* liquid-biopsy monitoring).

---

## 5. Anti-Hallucination Guardrails: Mandatory Database Figures

Every submission must embed **custom-captured, student-annotated screenshots/plots** directly from live public biomedical databases (**4 Figures for Standard Track**; **5 Figures for Honors/Graduate Track**):

* **Figure 1 (Molecular Target, Somatic Spectrum, or 3D Drug-Binding Pocket):** Captured from **`cBioPortal`** (lollipop plot / OncoPrint of somatic mutations), **`RCSB PDB / AlphaFold`** (3D structure showing the drug binding pocket or pathogenic residue), or **`UCSC / ClinVar`**. *Must include student callout arrows labeling the active site or key mutation.*
* **Figure 2 (`ClinicalTrials.gov` Pivotal Trial Design & Outcome Audit):** Captured from **`ClinicalTrials.gov`** (Study Design / Arms table or Results Outcome Measure table for your exact `NCT` number) paired with the published Kaplan–Meier curve. *Must annotate the primary endpoint, control arm, Hazard Ratio, and demographic breakdown.*
* **Figure 3 (`ClinPGx` / `CPIC` Dosing Table & Multi-Ancestry Allele Frequency):** Captured from **`ClinPGx.org` (`PharmGKB`)** or **`CPICpgx.org`** showing the Level 1A clinical dosing table for your regimen's pharmacogene, plus **`gnomAD`** population allele frequencies. *Must annotate the exact dose adjustment (e.g., 50% or 90% cut, or drug switch) and highest-risk ancestry group.*
* **Figure 4 (Clinical AI Stress-Test & FDA Label / Hype Comparison):** Side-by-side visual or annotated screenshot of your **FDA Package Insert Boxed Warning / Indications** alongside your **LLM Clinical Edge-Case Prompt & Critique**, highlighting the exact safety gate or nuance you audited.
* **Figure 5 (Honors / `BIOL 5111` Requirement — Resistance Structure or Clonal Escape):** Either a **3D Structural Model (`RCSB PDB / AlphaFold / Mol*`)** mapping the acquired resistance mutation (e.g., steric clash at the drug-binding cleft) **OR** a **Clonal Evolution / Phylodynamic Escape Plot (`cBioPortal` serial ctDNA / `Nextstrain`)**.

---

## 6. Required Data Synthesis Tables

### Table 1: End-to-End Translational & Pharmacogenomic Synthesis Matrix
Place immediately after your narrative text:

| Translational Tier | Focal Element / Gene / Drug | Database Identifier / Accession | Genomic Coordinates (GRCh38) / Star Allele | Quantitative Clinical / Statistical Metric | Primary Reference (PMID / DOI) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Tier 1: Unmet Need** | Disease & Standard-of-Care Failure | OMIM / ICD-10 Code | N/A | 5-yr Survival or SoC Toxicity Rate | PMID: ... |
| **Tier 2: Target Locus** | Molecular Target Gene & Driver | HGNC; Ensembl; cBioPortal / ClinVar VCV | chrN:start-end (GRCh38) | Mutation Frequency / Kd Binding Affinity | PMID: ... |
| **Tier 3: Drug Design** | Therapeutic Agent & Route/Packaging | DrugBank Accession / ChEMBL ID | Target Domain / Pocket | Bioavailability (F%), Half-Life (t1/2) | PMID: ... |
| **Tier 4: Trial Design** | Pivotal Clinical Trial Architecture | ClinicalTrials.gov NCT... | Biomarker Inclusion Gate | Phase, N, Control Arm, Primary Endpoint | PMID: ... |
| **Tier 5: Trial Efficacy** | Primary Outcome, NNT & Diversity | NCT Results / NEJM / Lancet | % Non-European Enrolled | HR / OR (95% CI), p-value, ARR, NNT | PMID: ... |
| **Tier 6: PGx Safety Gate** | Regimen Pharmacogene & Diplotype | ClinPGx PA... / CPIC Level 1A; rsID | chrN:start-end; Star Alleles | Activity Score (AS), % Dose Cut, gnomAD AF | PMID: ... |
| **Tier 7: Policy & Cost** | Pharmacoeconomics & Access | FDA Label / ICER Report | N/A | Annual WAC ($), ICER ($/QALY) | PMID: ... |
| **Tier 8: Hype & AI Audit** | FDA Boxed Warning vs. AI Vignette | DailyMed / FDA NDA # | Edge-Case Diplotype Tested | Specific AI Failure Mode / Label Warning | PMID: ... |
| **Tier 9: Resistance (Honors)** | Acquired Escape Mutation & Next-Gen Rx | PDB ID / COSMIC / Second NCT... | chrN:start-end (HGVS c./p.) | Fold-Change IC50 Shift; Comparator Trial HR | PMID: ... |

### Table 2 (Track A Only): Mandatory AI Audit & Clinical Stress-Test Table
Track A submissions must document **at least three (3) specific instances** where an LLM produced a factual error, coordinate/star-allele hallucination, ancestry omission, or unsafe clinical dosing recommendation during project preparation, paired with the primary literature/database proof and verified correction.

---

## 7. Comprehensive Evaluation Rubric (300 Points)

| Category | Pts | Track A Standard (Expert Peer Reviewer) | Track B Standard (100% Human-Authored) | Honors / Graduate Scope (`3111H / 5111`) |
| :--- | :-: | :--- | :--- | :--- |
| **1. Target Mechanism & Drug Engineering (Tiers 1–3)** | **60** | Granular structural and biochemical dissection of target, somatic/germline variants, delivery route, first-pass extraction, and formulation packaging. Zero generic filler. | Clear, accurate explanation of disease mechanism, molecular target, drug class, and route of delivery. | Integrates structural domain mechanics with multi-pathway systems context. |
| **2. Clinical Trial Forensics & Diversity Audit (Tiers 4–5)** | **75** | Rigorous audit of `ClinicalTrials.gov` NCT record, control arm fairness, ITT vs. Per-Protocol, HR/ARR/NNT math, surrogate endpoint critique, and enrollment equity. | Accurate reporting and thoughtful analysis of trial design, endpoints, statistics, and demographic representation. | **Dual-Trial Comparative Autopsy:** Head-to-head quantitative comparison of pivotal vs. confirmatory/subgroup/negative trials. |
| **3. Pharmacogenomic Safety Gate (`ClinPGx/CPIC`, Tier 6)** | **60** | Exact star-allele Activity Score math, active vs. prodrug mechanics, phenoconversion, and `gnomAD` multi-ancestry frequencies applied accurately under the Regimen-Wide PGx Rule. | Accurate identification and dosing interpretation of the regimen's `CPIC`/`ClinPGx` pharmacogene. | Models unphased *cis/trans* or structural CNV assay blind spots and clinical EHR Best Practice Alert workflow. |
| **4. Mandatory Database Figures & Table 1 Matrix** | **45** | Figures 1–4 custom-captured from live databases with sharp annotations; Table 1 100% complete and verified on GRCh38. | Figures 1–4 and Table 1 complete, clearly labeled, and integrated into the text. | Includes **Figure 5** (3D resistance structure or clonal escape trajectory) and **Tier 9** matrix row. |
| **5. Policy, Hype Audit, AI Stress-Test & Citations (Tiers 7–8)** | **60** | Incisive `$ / QALY` & press-release critique; Track A includes rigorous 3-case **Table 2 AI Audit**; 100% of 12–15 PMIDs/DOIs verified in PubMed. | Thoughtful ethics/cost analysis and LLM vignette reflection; 12–15 authentic references in original student voice. | **Tier 9 Acquired Resistance** narrative + **18–24 verified primary references**. |
