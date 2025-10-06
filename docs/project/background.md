# Background

## Genetic Diseases: A Global Challenge

Genetic diseases arise from alterations in the DNA sequence that compromise normal gene function, leading to abnormal protein expression or activity. They encompass a vast and heterogeneous group of disorders, ranging from single-gene defects to complex, multifactorial conditions. Although each individual rare disease affects relatively few people, collectively such disorders are estimated to impact more than 300 million individuals worldwide. The rapid progress of next-generation sequencing has enabled the identification of the molecular causes for most monogenic diseases, yet translating this genetic knowledge into effective therapies remains one of the central challenges of modern medicine.

Conventional treatments such as enzyme replacement, protein supplementation, or small-molecule drugs often alleviate symptoms but do not address the underlying genetic defect. In contrast, gene-based therapies aim to restore normal function by directly repairing or replacing defective DNA. Over the past decade, programmable nucleases such as ZFNs, TALENs, and CRISPR/Cas9 have revolutionized the field by enabling targeted genome modification with base-pair precision. These tools can disrupt, correct, or insert small DNA fragments and have already demonstrated curative potential for several monogenic disorders. However, significant challenges persist, including limited efficiency in post-mitotic tissues, the risk of off-target effects, and the difficulty of delivering large or complex edits safely and effectively in vivo.

Gene editing therefore represents both a scientific and translational frontier. The ability to correct disease-causing mutations at their source promises durable cures, but achieving broad clinical applicability requires technologies that go beyond single-variant repair. Approaches capable of large-scale and allele-independent gene correction could overcome the fundamental limitations of current genome editors and redefine the therapeutic landscape for rare genetic diseases.

## Challening Economics of Genetic Medicines 
The development of genetic medicines faces not only scientific but also economic challenges. Current editing platforms typically target a single allelic variant, meaning each therapy can address only a small subset of affected individuals. This limited scope restricts the market size for each therapeutic candidate and makes it difficult to justify the high costs of research, manufacturing, and clinical development. To make gene therapies accessible to patients with rare disorders, new modalities are required that can treat multiple allelic variants within the same gene or disease context.

Technologies that enable allele-independent gene correction could transform the economics of genetic medicine. A single therapeutic construct capable of restoring gene function across multiple mutations would drastically expand the patient base per indication. This would make development economically viable while simultaneously increasing patient access to curative treatments.

## Bridge Recombinases: A New Class of Programmable Genome Editors

Bridge recombinases represent a newly discovered class of RNA-guided DNA recombinases that mediate precise DNA rearrangements through a mechanism distinct from nuclease-based genome editing. Originating from the IS110 family of mobile genetic elements, these enzymes couple a DEDD-family recombinase with a structured non-coding RNA known as a bridge RNA (bRNA). The bRNA contains two internal loops that independently base-pair with a genomic target site and a donor DNA, bringing the two DNA molecules into proximity for site-specific recombination. This process enables three fundamental genomic operations—insertion, excision, and inversion—without introducing double-stranded breaks or relying on host DNA repair pathways.

Because bridge recombinases use RNA-guided recognition rather than fixed protein–DNA contacts, their targeting is inherently modular and programmable. Altering the sequence of the RNA guide is sufficient to redirect recombination to a new genomic locus. This broadens the concept of nucleic-acid-guided editing beyond CRISPR and extends it into the domain of large-fragment DNA integration. Unlike most current editors that are restricted to single-base or short-indel corrections, bridge recombinases can mediate the precise insertion of kilobase-scale DNA cassettes, making them particularly well suited for gene replacement therapies.

Two orthologs have been functionally characterized so far, IS621 and ISCro4, which share approximately 88 percent sequence identity. This degree of conservation suggests the likely existence of other naturally occurring and potentially more efficient variants. Both characterized orthologs demonstrate programmable, sequence-specific DNA insertion and high efficiency in bacterial (IS621) and mammalian systems (ISCro4), establishing bridge recombinases as a new molecular platform for RNA-programmed DNA recombination that could overcome the size, efficiency, and scalability limitations of existing genome-editing technologies.

## Alpha-1 Antitrypsin Deficiency as a Proof of Concept

Alpha-1 antitrypsin deficiency (A1ATD) is an autosomal co-dominant disorder caused by mutations in the SERPINA1 gene. These mutations lead to reduced levels or misfolding of the α1-antitrypsin protein, a key inhibitor of neutrophil elastase in the lungs and liver. More than 150 pathogenic variants of SERPINA1 have been identified, including the common S (Glu264Val) and Z (Glu342Lys) alleles, as well as numerous rare or population-specific mutations. This high allelic diversity makes A1ATD an ideal model for testing poly-allelic gene correction strategies.

Clinically, A1ATD is often underdiagnosed due to overlapping symptoms with other respiratory and hepatic disorders such as asthma, chronic obstructive pulmonary disease (COPD), or cryptogenic liver disease. The disease manifests as lung damage caused by insufficient α1-antitrypsin activity and as liver injury due to intracellular accumulation of misfolded protein.

<figure markdown>
![A1ATD](docs/img/A1ATD.jpg)
<figcaption> Figure 3: A1ATD
</figcaption>
</figure>

Beam Therapeutics has demonstrated that in vivo delivery of a genetic medicine using lipid nanoparticles (LNPs) can restore α1-antitrypsin expression in humans to therapeutic levels sufficient to rescue disease phenotypes of a specific allelic variant. This proof that enough hepatocytes can be functionally corrected through LNP delivery establishes A1ATD as a perfect model disease for validating new genome-editing platforms.

In this context, bridge recombinase–mediated gene replacement offers a universal therapeutic strategy. By inserting a healthy SERPINA1 cDNA copy at the endogenous locus, it could restore gene function regardless of the underlying mutation, positioning A1ATD as an ideal proof of concept for next-generation genetic medicines.

## Our IDEC 2025 Project: Evolving Bridge Recombinases

In this project our team set out to develop a dirceted evolution strategy for bridge recombinases with improved catalytic activity and specificity. Building on the discovery of IS621 and ISCro4, we established an experimental and computational platform that combines deep mutational learning (DML) with two complementary directed evolution systems: the E. coli orthogonal replication system (EcORep) and phage-assisted continuous evolution (PACE). 

Our goal is to explore the fitness landscape of bridge recombinases and evolve variants with enhanced efficiency for large-fragment gene insertion. As a proof of principle, we focus on Alpha-1 Antitrypsin Deficiency, aiming to enable bridge recombinase–mediated replacement of the defective SERPINA1 gene with a healthy copy. 
