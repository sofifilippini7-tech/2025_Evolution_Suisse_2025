---
hide:
  - navigation
---

 
# iDEC 2025 | Evolution Suisse 2025: Directed Evolution of Bridge Recombinases for Gene Replacement Therapies



## Challenge / Problem  

Replacing or repairing entire genes in human cells remains one of the biggest challenges in modern genome editing. Technologies such as CRISPR or base editors can change individual DNA letters with remarkable precision, but they are not well suited for inserting or replacing long DNA fragments such as full-length genes. These methods often depend on creating double-stranded DNA breaks and letting the cell repair them, which can lead to unwanted mutations, low efficiency in certain cell types, or even larger genomic rearrangements.  

Many genetic diseases, including those affecting only a few hundred or thousand patients, are caused by a large number of different mutations within the same gene. Developing a specific therapy for each individual variant is costly and time-consuming. To make genetic medicine more accessible, we need tools that can insert an intact gene copy into its natural genomic position, regardless of the underlying mutation.  

---

## Our Approach  

Our project focuses on a new class of genome editing enzymes called **bridge recombinases**. These enzymes combine a recombinase protein with an RNA molecule called a **bridge RNA (bRNA)** that guides the recombination process. The bridge RNA can bind to both the genomic target site and a donor DNA fragment. By doing so, it brings the two DNA pieces close together and allows the recombinase to join them precisely.  

Bridge recombinases share important features with CRISPR systems, as both use RNA to recognize specific DNA sequences. The key difference is in what happens afterward. CRISPR makes a cut in the DNA, and the cell has to repair it, whereas bridge recombinases perform a clean exchange without breaking both DNA strands. This makes the process safer and allows for the precise insertion of much larger DNA fragments.  

To further improve these enzymes, we apply **directed evolution**, a laboratory process that mimics natural selection. Through this approach, we aim to evolve bridge recombinases that are faster, more accurate, and suitable for therapeutic use. Our proof of concept focuses on **Alpha-1 Antitrypsin Deficiency (A1ATD)**, a genetic liver and lung disease caused by mutations in the *SERPINA1* gene. The ultimate goal is to insert a healthy copy of this gene directly into its natural genomic position in human cells, offering a universal treatment that works for all patients, no matter which mutation they have.  

---

## Workflow  

The first step in our workflow was the **identification of suitable target sites** in the *SERPINA1* gene. We selected several positions that are highly conserved across patients and located them upstream of most known pathogenic mutations, ensuring that insertion of a healthy gene copy would restore function for all variants.  

Next, we performed **computational screening using deep mutational learning (DML)**. This method allowed us to explore thousands of possible sequence variations in the recombinase and identify promising candidates with improved activity. DML helped us understand the enzyme’s fitness landscape and choose the best starting points for experimental evolution.  

For laboratory evolution, we employed two complementary systems. The first, called **EcORep**, uses a special DNA replicon inside *E. coli* that mutates at a high rate. Variants with higher recombination activity can be enriched over time, allowing the enzyme to evolve continuously toward better performance. The second system, **PACE** (phage-assisted continuous evolution), uses bacteriophages whose ability to reproduce depends on successful recombination. Only phages carrying active or improved recombinases can propagate, linking enzyme function directly to viral survival.  

---

## Key Achievements  

- We identified functional **target sequences within the SERPINA1 gene** that can be recognized by both **IS621** and **IS622** bridge recombinases, providing a foundation for precise insertion of a healthy gene copy.  

- We **designed and implemented a sequencing-based assay** to screen bridge recombinase variants and successfully **assembled a mutational library** that covers a broad distribution of sequence diversity, enabling deep mutational learning and identification of improved enzyme variants.  

- We **established an evolutionary selection logic using the EcORep system**, allowing continuous mutagenesis and enrichment of more active recombinase variants, and **validated the system experimentally through successful DNA cassette flipping** in *E. coli*.  

- We **developed and optimized a phage-assisted continuous evolution (PACE) framework** for bridge recombinases, confirming the feasibility of linking recombinase activity to phage propagation and establishing the groundwork for continuous evolution of high-performance variants.  
---
