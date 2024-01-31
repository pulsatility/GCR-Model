Full-text access to bioRxiv preprint: https://biorxiv.org/cgi/content/short/2024.01.26.577491v1

# A Multiscale Spatial Modeling Framework for the Germinal Center Response

Derek P. Mu1, Christopher D. Scharer2, Norbert E. Kaminski3, and Qiang Zhang4* 

1. Montgomery Blair High School, Silver Spring, MD 20901, USA

2. Department of Microbiology and Immunology, School of Medicine, Emory University, Atlanta, GA 30322, USA

3. Department of Pharmacology & Toxicology, Institute for Integrative Toxicology, Michigan State University, East Lansing, Michigan 48824, USA

4. Gangarosa Department of Environmental Health, Rollins School of Public Health, Emory University, Atlanta, GA 30322, USA
 

Abstract:

The germinal center response or reaction (GCR) is a hallmark event of adaptive humoral immunity. Unfolding in the B cell follicles of the secondary lymph organs, a GC culminates in the production of high-affinity antibody-secreting plasma cells along with memory B cells. By interacting with follicular dendritic cells (FDC) and T follicular helper (Tfh) cells, GC B cells exhibit complex spatiotemporal dynamics. Driving the B cell dynamics are the intracellular signal transduction and gene regulatory network that responds to cell surface signaling molecules, cytokines, and chemokines. As our knowledge of the GC continues to expand in depth and in scope, mathematical modeling has become an important tool to help disentangle the intricacy of the GCR and inform novel mechanistic and clinical insights. While the GC has been modeled at different granularities, a multiscale spatial simulation framework – integrating molecular, cellular, and tissue-level responses – is still rare. Here, we report our recent progress toward this end with a hybrid stochastic GC framework developed on the Cellular Potts Model-based CompuCell3D platform. Tellurium is used to simulate the B cell intracellular molecular network comprising NF-κB, FOXO1, MYC, AP4, CXCR4, and BLIMP1 that responds to B cell receptor (BCR) and CD40-mediated signaling. The molecular outputs of the network drive the spatiotemporal behaviors of B cells, including cyclic migration between the dark zone (DZ) and light zone (LZ) via chemotaxis; clonal proliferative bursts, somatic hypermutation, and DNA damage-induced apoptosis in the DZ; and positive selection, apoptosis via a death timer, and emergence of plasma cells in the LZ. Our simulations are able to recapitulate key molecular, cellular, and morphological GC events including B cell population growth, affinity maturation, and clonal dominance. This novel modeling framework provides an open-source, customizable, and multiscale virtual GC simulation platform that enables qualitative and quantitative in silico investigations of a range of mechanic and applied research questions in future.

Keywords: B cells, germinal center, dark zone, light zone, affinity maturation, proliferative burst, chemotaxis
