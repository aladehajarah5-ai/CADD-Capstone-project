# CADD-Capstone-project
Capstone project completed during The insilico Lab CADD training
# CAPSTONE PROJECT REPORT

## Computer-Aided Drug Design (CADD) Workflow Using SARS-CoV-2 Main Protease (7SFB)

### Introduction

As part of my training at The Insilico Lab, I completed a capstone project designed to apply the concepts and tools learned throughout the three-week Computer-Aided Drug Design (CADD) program. This project focused on the SARS-CoV-2 Main Protease (7SFB), an important protein involved in viral replication and a promising target for drug discovery.

The project integrated several computational techniques, including drug-likeness screening, protein preparation, binding site analysis, ADMET prediction, and AI-based protein structure evaluation. The aim was to understand how these tools work together in the early stages of drug discovery and development.

### Project Objective

The objective of this project was to evaluate potential drug candidates and perform a complete computational workflow using modern CADD tools. The project also aimed to explore the role of artificial intelligence in protein structure prediction and validation.

---

## Step 1: Drug-Likeness Screening

The first stage of the project involved evaluating five compounds:

• Aspirin
• Ibuprofen
• Acetaminophen
• Naproxen
• Diclofenac

Using SwissADME, I assessed the physicochemical properties and drug-likeness of each compound. Parameters such as molecular weight, hydrogen bond donors and acceptors, lipophilicity, and oral bioavailability were examined using Lipinski's Rule of Five.

This step is important because compounds that fail drug-likeness criteria are less likely to become successful drug candidates. The analysis showed that all five compounds satisfied the major requirements for drug-likeness.



<img width="1366" height="768" alt="molecule 1 swiss" src="https://github.com/user-attachments/assets/f7667dba-44be-490a-80d5-03f095b6e2ad" />

---

## Step 2: Protein Preparation

The experimental structure of the SARS-CoV-2 Main Protease (7SFB) was obtained from the Protein Data Bank (PDB).

Using UCSF Chimera, the protein structure was prepared for computational analysis. This involved removing unnecessary molecules, cleaning the structure, and ensuring it was suitable for downstream applications.

Protein preparation is a critical step because errors or unwanted molecules in the structure can affect the accuracy of subsequent analyses.
<img width="1366" height="768" alt="molecule 1 swiss" src="https://github.com/user-attachments/assets/10aa0de2-4c58-4c0f-9624-914e5c3ce6b1" />

📷 Insert original protein structure image.

📷 Insert prepared protein structure image.

---

## Step 3: Binding Site Identification

To identify the most promising binding region on the protein, I used DoGSiteScorer through ProteinPlus.

The analysis identified several potential pockets, with Pocket P_0 emerging as the most druggable region. Important properties of this pocket included:

• Pocket Volume: 642.94 Å³
• Surface Area: 776.96 Å²
• Druggability Score: 0.75

Key amino acid residues involved in the binding pocket included THR26, HIS41, CYS44, ASP48, and PRO52.

Understanding the binding pocket is essential because it helps predict where drug molecules are most likely to interact with the protein.

📷 Insert binding pocket visualization.

---

## Step 4: ADMET Prediction

The selected compounds were further analyzed using ADMETlab 3.0.

ADMET prediction evaluates:

• Absorption
• Distribution
• Metabolism
• Excretion
• Toxicity

These properties provide insight into how a compound may behave in the human body and whether it has characteristics suitable for drug development.

Comparative analysis showed differences in the safety and pharmacokinetic profiles of the compounds. Acetaminophen displayed a balanced ADMET profile, while some compounds showed potential limitations related to toxicity or metabolism.

📷 Insert ADMETlab results.

---

## Step 5: AI-Based Protein Structure Prediction

One of the most exciting aspects of this project was using AlphaFold3 to predict the three-dimensional structure of the target protein from its amino acid sequence.

The protein sequence was retrieved and submitted to AlphaFold3 for structure prediction. The resulting model demonstrated high confidence and provided an opportunity to evaluate the performance of AI in structural biology.

📷 Insert AlphaFold3 predicted structure.

---

## Step 6: Structural Validation and Comparison

To assess the accuracy of the AlphaFold3 prediction, the predicted structure was aligned with the experimentally determined structure using PyMOL.

The comparison produced:

• RMSD: 0.568 Å
• Atoms Aligned: 2002
• pTM Score: 0.93

The low RMSD value indicates excellent agreement between the predicted and experimental structures, demonstrating the reliability of AlphaFold3 for protein structure prediction.

This comparison highlights how artificial intelligence can support and accelerate modern drug discovery research.

📷 Insert alignment and overlay image.

---

## Tools Used

Throughout this project, I gained practical experience using:

• SwissADME
• UCSF Chimera
• PyMOL
• ProteinPlus (DoGSiteScorer)
• ADMETlab 3.0
• AlphaFold3
• PubChem
• Protein Data Bank (PDB)

---

## Key Takeaways

This capstone project provided a complete introduction to the computational drug discovery workflow. I learned how compounds are evaluated for drug-likeness, how proteins are prepared and analyzed, how binding pockets are identified, and how AI can be used to predict and validate protein structures.

Beyond learning new software tools, the project strengthened my understanding of how computational methods contribute to faster and more efficient drug discovery.

---

## Acknowledgement

I would like to sincerely thank all the facilitators and the entire The Insilico Lab team for their guidance, patience, encouragement, and commitment throughout this training. Your support made complex concepts easier to understand and gave me the confidence to explore computational drug discovery more deeply.

This training has been an amazing learning experience, and I am truly grateful for the knowledge and skills gained over the past three weeks.
<img width="1366" height="768" alt="molecule 1 swiss" src="https://github.com/user-attachments/assets/671874fe-014a-4dd9-9fd3-3114461b6f21" />
