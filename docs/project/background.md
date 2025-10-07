# Background

## Genetic Diseases: A Global Challenge

Genetic diseases occur when changes in our DNA disrupt how genes function, leading to abnormal or missing proteins. These conditions cover a wide range of consequences from disorders caused by a single gene mutation to complex diseases involving many genes and environmental factors. While each rare genetic disease affects only a small number of people, together they impact more than 300 million individuals worldwide. Advances in DNA sequencing now allow us to identify the exact genetic causes of most single-gene disorders, but turning this knowledge into effective therapies remains challenging in modern medicine.

Traditional treatments, such as giving patients the missing protein, enzyme replacement, or small-molecule drugs, often help with symptoms but don’t fix the root cause: the faulty DNA. Gene-based therapies aim to do exactly that by repairing or replacing the defective gene itself. Over the past decade, tools like ZFNs, TALENs, and especially CRISPR/Cas9 have transformed this field by allowing precise editing of DNA sequences. These “molecular scissors” can cut DNA at a chosen site, enabling correction or replacement of short sequences. In some cases, CRISPR-based approaches have already achieved cures for single-gene diseases.

However, there are still hurdles: limited efficiency in non-dividing tissues like neurons or liver cells, potential off-target edits, and challenges in safely delivering these tools into the body. Moreover, most current editors are suited for fixing single-base errors or small insertions, but not for replacing large or complex sections of DNA.

Gene editing is therefore both a scientific frontier and a medical opportunity. The ability to repair disease-causing mutations directly at their source could lead to long-lasting cures. Yet, for broad clinical use, we need technologies that go beyond one mutation at a time — systems that can replace or restore entire genes regardless of the underlying mutation.

## The Economic Challenge of Genetic Medicines

Developing gene therapies is not only scientifically difficult but also economically demanding. Most current editing platforms are designed for a single mutation, meaning that each therapy serves only a very small patient group. This limited reach makes it hard to justify the enormous costs of research, manufacturing, and clinical trials.

To make genetic therapies more affordable and accessible, new approaches are needed. Ones that can correct multiple mutations within the same gene using a single therapeutic design. Technologies that enable allele-independent gene correction could transform the economics of this field. If one construct could restore normal gene function across many different variants, the potential patient base would grow dramatically, making treatment development more sustainable while giving more patients access to curative options.

## Bridge Recombinases: A New Class of Programmable Genome Editors

Bridge recombinases are a newly discovered family of genome-editing enzymes that work in a fundamentally different way from CRISPR.

While CRISPR/Cas9 acts like molecular scissors — cutting DNA at a specific site guided by a guide RNA — bridge recombinases act more like molecular glue. They use a bridge RNA (bRNA) to bring together two DNA molecules — a target in the genome and a donor carrying a new piece of DNA — and then recombine them precisely, without making double-stranded breaks.

These enzymes come from the IS110 family of mobile genetic elements. Each bridge recombinase combines a DEDD-family recombinase enzyme with its own structured bRNA. The bridge RNA has two loops: one binds to the genomic target site, and the other binds to the donor DNA. This dual binding physically aligns both DNA molecules so the recombinase can join them seamlessly.

This mechanism enables three core operations: insertion, deletion, and inversion of DNA fragments — all without relying on the cell’s natural repair systems. That’s a major difference from CRISPR, which depends on the cell’s DNA repair pathways to complete the edit after making a cut.

Just like changing the sequence of a CRISPR guide RNA directs Cas9 to a new site, altering the bridge RNA sequence can redirect the recombinase to a new genomic location. But bridge recombinases go beyond CRISPR in one important way: they can precisely insert large DNA fragments (up to several kilobases), while CRISPR edits are usually limited to small changes. This makes bridge recombinases especially promising for gene replacement therapies, where an entire functional gene needs to be inserted.

So far, two bridge recombinases, IS621 and ISCro4, have been characterized. They share about 88% sequence identity, suggesting that many other natural variants likely exist, some potentially even more efficient. Both of these enzymes have shown that RNA-guided recombination works reliably: IS621 functions well in bacteria, and ISCro4 in mammalian cells. Together, they define a new and powerful class of RNA-programmable genome editors that could overcome many limitations of existing technologies.

## Alpha-1 Antitrypsin Deficiency as a Proof of Concept

Alpha-1 Antitrypsin Deficiency (A1ATD) is a genetic disorder caused by mutations in the SERPINA1 gene. These mutations lead to low levels or misfolding of the α1-antitrypsin protein, a key molecule that protects the lungs and liver from damage. More than 150 disease-causing variants of SERPINA1 have been identified, including the common S (Glu264Val) and Z (Glu342Lys) variants, along with many rare mutations. Because so many different mutations can cause the same disease, A1ATD is a perfect model for testing broad, multi-allelic gene correction strategies.

Clinically, A1ATD often goes undiagnosed because its symptoms overlap with other conditions such as asthma, COPD, or chronic liver disease. The disease manifests as lung damage (due to lack of functional α1-antitrypsin) and liver injury (due to accumulation of misfolded protein in hepatocytes).

<figure markdown>
![A1ATD](https://idec-teams.github.io/2025_Evolution_Suisse_2025/img/A1ATD.jpg)
<figcaption> Figure 3: A1ATD
</figcaption>
</figure>

Recent work by Beam Therapeutics has shown that delivering genetic medicines directly into the liver using lipid nanoparticles (LNPs) can restore α1-antitrypsin expression in humans to therapeutic levels. This demonstrates that enough liver cells can be genetically corrected in vivo to cure the disease, making A1ATD an ideal proof-of-concept model for testing new editing systems.

In this context, bridge recombinase–based therapy could offer a universal solution. By inserting a healthy copy of the SERPINA1 gene directly into its natural location in the genome, this method could restore function no matter which mutation caused the disease, a single treatment for all variants.

## Our IDEC 2025 Project: Evolving Bridge Recombinases

In our 2025 IDEC project, we aim to push bridge recombinases beyond their natural limits. Our team is developing a directed evolution strategy to improve both their efficiency and specificity. Building on the known IS621 and ISCro4 enzymes, we are combining deep mutational learning (DML) with two continous evolution systems:
	•	E. coli Orthogonal Replication (EcORep) 
	•	Phage-Assisted Continuous Evolution (PACE)

Our goal is to map and understand the fitness landscape of bridge recombinases — essentially, how different mutations affect their activity — and evolve versions that are better at inserting large DNA fragments precisely and efficiently.

As a proof of principle, we focus on Alpha-1 Antitrypsin Deficiency (A1ATD). If we can use an evolved bridge recombinase to replace the faulty SERPINA1 gene with a healthy one, it would demonstrate a powerful new way to correct genetic diseases at their root — and potentially make large-scale, mutation-independent cures a reality.
