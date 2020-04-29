'Exploratory' /  'open-ended'class project ideas
================================================

You aren't constrained to one, and this is in addition to reporting on your Folding@Home project summary:

- Make an animation to illustrate the Folding@Home process visually that we could add to some of the online material to represent the class's Folding@Home component. One idea would be to unfold a SARS-CoV-2 structure using the following and then just reverse the frames to produce a video or gif file:
	- http://proteopedia.org/wiki/index.php/Sculpting_protein_conformations
	- http://proteopedia.org/wiki/index.php/User:Wayne_Decatur/Generate_Unfolded_Structures  
	Describe briefly the process of making the visuals in a page at Proteopedia.
	
- Expand on some topic or topic pages at Proteopedia.
- Topic pages of Cryo-EM structues of SET1 family complexes (both yeast and human; h/t to Kevin Namitz's thesis seminar).
- Add an entire new topic page on something interesting to you. (Probably best done in your namespace first so you can move it when you are happy with it. And this way you'll know as you are planning it, no one can edit it to deviate from your vision.)
- Add the details of making your homology model for Alaji's nanocourse and make some molecular structure scenes featuring some aspects of it that you would want to communicate to a reader/collaborator. (Probably best done in your namespace first so you can move it when you are happy with it. And this way you'll know as you are planning it, no one can edit it to deviate from your vision.) As an example sort of along those lines, see http://proteopedia.org/wiki/index.php/User:Wayne_Decatur/Sandbox_1_vs_21_vs_2_vs_12 which was a companion to an email discussion.
- Make a full-featured interactive Proteopedia page to accompany a paper on SARS-CoV-2 or any article that interests you. (see 'Suggestions for material for making a Proteopedia page to accompany a paper on SARS-CoV-2' below)

Proteopedia's pages may offer some other ideas:
* [Wanted pages](http://proteopedia.org/wiki/index.php/Wanted_pages)
* [Pages needing expansion‎](http://proteopedia.org/wiki/index.php/Pages_needing_expansion)
* [Pages needing improvement‎](http://proteopedia.org/wiki/index.php/Pages_needing_improvement)

- Work out pseudocode for a task you do commonly and would like to automate? How to modularize? Any ideas on how to make any parts a relity? Where to run it?

- Work out a computational workflow for some analysis involving SARS-CoV-2 or report on someone's. What would it take to install even some of the software? Could you get the software? Could you install it on a linux machine in the cloud? Your computer (theoretically)? 

- Outline a new test for detecting COVID-19 patients? (h/t to Alaji's nanocourse) How would it be better/complementary?

- Do a virtual screening with protease or other SARS-CoV-2 proteins following the following reference tutorial and describe process and outcome on a page at Proteopedia:
https://twitter.com/gxytraining/status/1244545901898727426    March 30 2020  
	>"Virtual screening of the SARS-CoV-2 main protease with rDock and pose scoring, a new tutorial by @SimonBray18 , https://training.galaxyproject.org/training-material/topics/computational-chemistry/tutorials/covid19-docking/tutorial.html #UseGalaxy #COVID19"

- Examine electron density for some off residues in SARS-CoV-2 structures and make visuals in Proteopedia:

	https://twitter.com/CrollTristan/status/1252874918984773635
	>"Busily adding waters to 7bv2 (Nsp12-7-8 complex with RNA and remdesivir). Lovely map - but it (and 7bv1) has the same register shift in the C-terminal helix as 7btf and 6nur. Also a flipped adenosine in the RNA helix, and the magnesium ions seem questionable."
	>"Also a missed cis-proline (chain A, residue 505). Notice that this doesn't show up as a geometry outlier (but a good local-fit-to-density tool would pick it up - I really should get something integrated into ISOLDE)."



Suggestions for material for making a Proteopedia page to accompany a paper on SARS-CoV-2
-----------------------------------------------------------------------------------------

- Make a Proteopedia topic page featuring an interactive structure scene version of Figure 1a and possibly Figur 1b from https://www.nature.com/articles/s41564-020-0688-y/figures/1 . To fully do that it may involve superposition via PyMOL or Jmol. (For Jmol that involves the 'compare' command.) The corresponding figure legend in the paper reads, "a, Betacoronaviruses, including SARS-CoV, interact with the host-cell receptor via the RBD in spike (Protein Data Bank ID: 5X5B; 2AJF). b, Engineered silent mutations in SARS spike facilitated replacement of the RBD sequence. SARS spike amino acid numbers are indicated in black for the silent cloning sites and orange for the RBD." Full paper reference: Functional assessment of cell entry and receptor usage for SARS-CoV-2 and other lineage B betacoronaviruses. Michael Letko, Andrea Marzi & Vincent Munster. Nature Microbiology volume 5, pp. 562–569(2020) Published: 24 February 2020. PMID: 32094589 DOI: 10.1038/s41564-020-0688-y .

- Make a Proteopedia topic page featuring an interactive structure scene version of Figure 1a and possibly Figur 1b from https://www.nature.com/articles/s41564-020-0688-y/figures/1 . However, employ homology modeling, using I-TASSER or Phyre2, to first convert the viral sequence to the SARS-CoV-2 sequence (unless, there a no differences?) and then use superposition via PyMOL or Jmol to make a model with the SARS-CoV-2 proteins interacting with the receptor. (For Jmol that involves the 'compare' command.) The corresponding figure legend in the paper reads, "a, Betacoronaviruses, including SARS-CoV, interact with the host-cell receptor via the RBD in spike (Protein Data Bank ID: 5X5B; 2AJF). b, Engineered silent mutations in SARS spike facilitated replacement of the RBD sequence. SARS spike amino acid numbers are indicated in black for the silent cloning sites and orange for the RBD." Full paper reference: Functional assessment of cell entry and receptor usage for SARS-CoV-2 and other lineage B betacoronaviruses. Michael Letko, Andrea Marzi & Vincent Munster. Nature Microbiology volume 5, pp. 562–569(2020) Published: 24 February 2020. PMID: 32094589 DOI: 10.1038/s41564-020-0688-y .

- Inhibition of SARS-CoV-2 (previously 2019-nCoV) infection by a highly potent pan-coronavirus fusion inhibitor targeting its spike protein that harbors a high capacity to mediate membrane fusion
Shuai Xia, Meiqin Liu, Chao Wang, Wei Xu, Qiaoshuai Lan, Siliang Feng, Feifei Qi, Linlin Bao, Lanying Du, Shuwen Liu, Chuan Qin, Fei Sun, Zhengli Shi, Yun Zhu, Shibo Jiang & Lu Lu 
Cell Research volume 30, pages 343–355(2020) https://www.nature.com/articles/s41422-020-0305-x

	>"To understand the structural basis of the interactions between HR1 and HR2 regions of SARS-CoV-2, a fusion protein containing the major parts of HR1 (residues 910–988) and HR2 (residues 1162–1206) with a flexible linker (L6, SGGRGG) in between was constructed for crystallographic study. The crystal structure of HR1-L6-HR2 shows a canonical 6-HB structure with a rod-like shape 115 Å in length and 25 Å in diameter (Fig. 2b). The three HR1 domains form a parallel trimeric coiled-coil center, around which three HR2 domains are entwined in an antiparallel manner. The interaction between these two domains is predominantly a hydrophobic force."
	>"The space group of the collected dataset is P21. Molecular replacement was performed with PHENIX.phaser37 to solve the phasing problem, using the SARS-CoV S protein core structure (PDB code 1WYY) as a search model. The final model was manually adjusted in COOT and refined with Refmac.38 Data collection statistics and refinement statistics are given in Table 1. Coordinates were deposited in the RCSB Protein Data Bank (PDB code: 6LXT). The interaction model of EK1C4 peptide and HR1 domains of SARS-nCoV-2 was predicted by SWISS-MODEL sever39 using 6XLT as reference for EK1 moiety, and by Autodock 4 software40 for cholesterol moiety (Supplementary information, Fig. S8)."
	PDB id: 6lxt  (used 1wyy to solve phasing)

- S protein activation as a topic page. Possible material:
	- A Transmembrane Serine Protease Is Linked to the Severe Acute Respiratory Syndrome Coronavirus Receptor and Activates Virus Entry. Ana Shulla, Taylor Heald-Sargent, Gitanjali Subramanya, Jincun Zhao, Stanley Perlman, Tom Gallagher. Journal of Virology. Published online December 22, 2010. PMID:21068237 DOI: 10.1128/JVI.02062-10 https://jvi.asm.org/content/85/2/873
	- Activation of the SARS coronavirus spike protein via sequential proteolytic cleavage at two distinct sites. Sandrine Belouzard, Victor C. Chu, and Gary R. Whittaker. PNAS April 7, 2009 106 (14) 5871-5876; https://doi.org/10.1073/pnas.0809524106 https://www.pnas.org/content/106/14/5871
	- Different residues in the SARS-CoV spike protein determine cleavage and activation by the host cell protease TMPRSS2. Reinke LM, Spiegel M, Plegge T, Hartleib A, Nehlmeier I, Gierer S, Hoffmann M, Hofmann-Winkler H, Winkler M, Pöhlmann S. PLoS One. 2017 Jun 21;12(6):e0179177. doi: 10.1371/journal.pone.0179177. eCollection 2017.PMID: [28636671](https://www.ncbi.nlm.nih.gov/pubmed/28636671)
	- Characterization of spike glycoprotein of SARS-CoV-2 on virus entry and its immune cross-reactivity with SARS-CoV. Xiuyuan Ou, Yan Liu, Xiaobo Lei, Pei Li, Dan Mi, Lili Ren, Li Guo, Ruixuan Guo, Ting Chen, Jiaxin Hu, Zichun Xiang, Zhixia Mu, Xing Chen, Jieyong Chen, Keping Hu, Qi Jin, Jianwei Wang & Zhaohui Qian. Nature Communications volume 11, Article number: 1620 (2020) https://www.nature.com/articles/s41467-020-15562-9

- A topic page on SARS-CoV-2 proteins/ domains / RNA structures of unknown structure

	https://twitter.com/PDBeurope/status/1242726618579304448
	>"This week's #PDB release includes 68 structures of #COVID19 protease, with various bound fragments identified using PanDDA analysis. Work by @MartinWalshDLS, @Darenfearon, @londonlab and more @diamondLightSou . Find all new #COVID19 structures at https://ebi.ac.uk/pdbe/entry/search/index/?searchParams=%7B%22q_organism_name%22:%5B%7B%22value%22:%22Severe%20acute%20respiratory%20syndrome%20coronavirus%202%22,%22condition1%22:%22AND%22,%22condition2%22:%22Contains%22%7D%5D,%22q_latest_pdb_entry_type%22:%5B%7B%22value%22:%22new%22,%22condition1%22:%22AND%22,%22condition2%22:%22Equal%20to%22%7D%5D,%22resultState%22:%7B%22tabIndex%22:0,%22paginationIndex%22:1,%22perPage%22:%2210%22,%22sortBy%22:%22Sort%20by%22%7D%7D"
	https://twitter.com/Darenfearon/status/1242908558297116675
	>"If anyone wants to read more about what we are doing with these structures then head here: https://diamond.ac.uk/covid-19.html"
	https://www.diamond.ac.uk/covid-19.html


	[PDBe-KB COVID-19 Data Portal](https://www.ebi.ac.uk/pdbe/covid-19)
	>"Our new PDBe-KB COVID-19 data portal brings together all available PDB data from SARS-CoV-2 structures, to help researchers easily identify important structural features to support the development of treatments and vaccines."
- A topic page on SARS-CoV-2 NSP3
	- Alaji's nanocourse Session #4 went into detail of some of the many domains of this complex protein. Several potions have corresponding structures.  
	Pertinent reference:  
	Nsp3 of coronaviruses: Structures and functions of a large multi-domain protein. Jian Lei, Yuri Kusov, and RolfHilgenfeld. Antiviral Research Volume 149, January 2018, Pages 58-74.  https://doi.org/10.1016/j.antiviral.2017.11.001 https://www.sciencedirect.com/science/article/pii/S0166354217303972

- A topic page based on maing interactive scenes of the structures and interactions from the paper Alaji covered in depth in session #5 of his nanocourse. For session #5 he really did a journal club coverage of that paper and it had a lot of cotnent that would make good interactive visuals for a page related to the paper or topic:  
	REFERENCE FROM THAT SESSION: Inhibition of SARS-CoV-2 (previously 2019-nCoV) infection by a highly potent pan-coronavirus fusion inhibitor targeting its spike protein that harbors a high capacity to mediate membrane fusion. Xia S, Liu M, Wang C, Xu W, Lan Q, Feng S, Qi F, Bao L, Du L, Liu S, Qin C, Sun F, Shi Z, Zhu Y, Jiang S, Lu L. Cell Res. 2020 Apr;30(4):343-355. doi: 10.1038/s41422-020-0305-x. Epub 2020 Mar 30. PMID: 32231345  DOI: 10.1038/s41422-020-0305-x Example figure 1d legend: "d The superposition of 6-HB structure of SARS-CoV (PDB entry 1WYY), MERS-CoV (PDB entry 4NJL) and SARS-CoV-2 is shown in ribbon."   
	Related structure is structure of post fusion core of 2019-nCoV S2 subunit, PDB id: 6LXT

- A topic page on SARS-CoV-2 RNA nucleotide modifications:
	- https://twitter.com/SchragaSchwartz/status/1241439890514067458   March 2020
	>"First study on RNA transcriptome and epitranscriptome in  SARS-CoV-2. Finds a mysterious signal, potentially an RNA modification, in a purine rich motif:  [The architecture of SARS-CoV-2 transcriptome](https://www.cell.com/cell/pdf/S0092-8674(20)30406-2.pdf) "
	from The Architecture of SARS-CoV-2 Transcriptome.
	Kim D, Lee JY, Yang JS, Kim JW, Kim VN, Chang H.
	Cell. 2020 Apr 18. pii: S0092-8674(20)30406-2. doi: 10.1016/j.cell.2020.04.011. https://www.cell.com/cell/pdf/S0092-8674(20)30406-2.pdf  PMID: 32330414  :
	>"We, however, noticed intriguing differences in the ionic current (called “squiggles”) between negative control and viral transcripts (Figure 5A). At least 41 sites displayed substantial differences (over 20% frequency), indicating potential RNA modifications (Table S5). Notably, some of the sites showed different frequencies depending on the sgRNA species. Figures 5A-5C show an example that is modified more heavily on the S RNA than the N RNA, while Figures S2A-S2C present a site that is modified more frequently on the ORF8 RNA compared with the S RNA. Moreover, the dwell time of the modified base is longer than that of the unmodified base (Figure 5D, right), suggesting that the modification interferes with the passing of RNA molecules through the pore."


- A topic page on the non-structural proteins as a group or one of them


- A topic page on a specific approach at therapeutics

	https://twitter.com/VirusesImmunity/status/1243997325804142593    March 2020
	>"This is a cautionary tale of how anti-Spike antibody may make COVID disease worse. In this study, the authors show that anti-Spike IgG made SARS-CoV disease worse by switching macrophage from wound-healing to proinflammatory phenotype. A thread (1/n)"

- A topic page on SARS-CoV-2-human protein-protein interactions
- 
	https://twitter.com/DoctorBou/status/1242330062474469376    March 2020
	>"We in @KroganLab spent two weeks mapping #SARSCoV2-human protein-protein interactions. My favorite interactions were with DNA polymerase (why??), the nuclear pore, the centrosome, and mitochondrial complexes. The resemblance to cancer biology is striking. Why? Pls comment!"
	[A SARS-CoV-2-Human Protein-Protein Interaction Map Reveals Drug Targets and Potential Drug-Repurposing](https://www.biorxiv.org/content/10.1101/2020.03.22.002386v3)


Curated PDB entry collection in more context
--------------------------------------------

In more context, and linking to Protoepdia content, than say the [PDBe-KB COVID-19 Data Portal](https://www.ebi.ac.uk/pdbe/covid-19)
