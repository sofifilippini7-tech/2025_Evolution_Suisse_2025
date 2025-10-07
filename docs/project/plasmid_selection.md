# Phlasmid-based selection system for evolving bridge recombinases
## Evolutionary strategy and plasmid design
We designed an evolution logic that allows for the selection of improved bridge recombinases in *E. coli*. 
![Color_coded_Whole_Cell_View_3](https://github.com/user-attachments/assets/4b06a5a7-0665-4d57-95cd-71e48d96d1e4)
<figcaption>Figure 1: DE of IS621 using EcORep. A depicts the mutagenesis plasmid, the O-Replicon and the selection
plasmid in an E. coli cell. The mutagenesis plasmid carries the genes necessary for replicating the O-Replicon.
The O-Replicon carries IS621 under the control of the inducible PVanCC promoter. The selection plasmid
contains a casette with two antibiotic resistances, Gm resistance (GmR) and Kan resistance (KanR) facing in
opposite directions. Depending on the orientation of the cassette, either GmR or KanR is transcribed. The
cassette is flanked by donor and target sequences facing each other. This allows for IS621 + bRNA mediated
inversion. B depicts the selection process. Cells are grown in LB liquid culture. IS621 expression is induced
using vanillic acid (Van). Shortly before stationary phase, bRNA expression is induced by addition of aTc for
bRNA A or OHC14 for bRNA B. Presence of IS621 + bRNA promotes recombination. Selection is performed
by regrowing cells in media containing Kan or Gm. Cells that have successfully recombined express the correct
AB resistance and survive, cells that did not recombine die. This process promotes the survival of bacteria
carrying more active IS621 variants.
## Markdown footnotes for citations

Reference: [squidfunk.github.io/mkdocs-material/reference/data-tables/](https://squidfunk.github.io/mkdocs-material/reference/footnotes/)

All footnotes will appear at the end of the page. For example:

The International Directed Evolution Competition (iDEC)[^1] is an international competition on directed evolution[^2].

[^1]: [iDEC Website About Us Page](https://idec.io/pages/about_us.html)
[^2]:
    This is not a real citation.  
    Multiple line footnote is supported.

## Add images:

![dummy image](img/dummy.png){ width=800px }
