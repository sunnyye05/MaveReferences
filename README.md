# MaveReferences
Welcome to our table of Multiplexed Assay of Variant Effect (MAVE) studies.
To cite this document, please use the citation details for [MaveDB](https://www.mavedb.org/).

## Updating the table
As of release version 0.2.0, the references are now stored in a the tab-separated file 'maverefs.tsv' and formatted for the README using the 'format.py' script.

To add or edit a study:
1. [Fork this repository](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and create a local clone.
1. Open 'maverefs.tsv' in a spreadsheet program and make your changes.
1. Save 'maverefs.tsv', making sure it remains a tab-separated text file.
1. Run `python format.py` in the MaveReferences directory to re-format the README. Note that this script requires the idutils package (`pip install idutils`) for link formatting.
1. Commit your changes and [please submit a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

You can also submit changes using the GitHub issue tracker.

## Table of references
|PMID|DOI|First author|Year|Type|Molecule|Model|Selection Type|Mutagenesis Type|Sequencing Platform|Raw Data|Scores in Table|
|---|---|---|---|---|---|---|---|---|---|---|---|
|[19915551](https://www.ncbi.nlm.nih.gov/pubmed/19915551)|[10.1038/nbt.1589](https://doi.org/10.1038/nbt.1589)|Patwardhan|2009|MPRA|T3 promoter, T7 promoter, SP6 promoter, CMV promoter, HBB promoter, S100A4 promoter|in vitro|Transcription|microarray synthesis|Illumina|[SRP001721](https://www.ebi.ac.uk/ena/data/view/SRP001721)|TXT|
|[20439748](https://www.ncbi.nlm.nih.gov/pubmed/20439748)|[10.1073/pnas.1004290107](https://doi.org/10.1073/pnas.1004290107)|Kinney|2010|MPRA|lac promoter|E.coli|FACS|Cassette ligation|Roche 454|[SRA012345](https://www.ebi.ac.uk/ena/data/view/SRA012345)|No|
|[20711194](https://www.ncbi.nlm.nih.gov/pubmed/20711194)|[10.1038/nmeth.1492](https://doi.org/10.1038/nmeth.1492)|Fowler|2010|DMS|WW domain|Phage|Binding|doped oligo synthesis|Illumina|[SRP002725](https://www.ebi.ac.uk/ena/data/view/SRP002725)|No|
|[20714644](https://www.ncbi.nlm.nih.gov/pubmed/20714644)|[10.1039/c0mb00061b](https://doi.org/10.1039/c0mb00061b)|Ernst|2010|DMS|Synthetic PDZ domain|Phage|Binding|Kunkel|Roche 454|No|No|
|[21464309](https://www.ncbi.nlm.nih.gov/pubmed/21464309)|[10.1073/pnas.1016024108](https://doi.org/10.1073/pnas.1016024108)|Hietpas|2011|DMS|Hsp90|Yeast|Growth|NNN PCR|Illumina|No|TXT|
|[21825149](https://www.ncbi.nlm.nih.gov/pubmed/21825149)|[10.1073/pnas.1111218108](https://doi.org/10.1073/pnas.1111218108)|Zhang|2011|DMS|IgG|Phage|Binding|Combinatorial|Roche 454|No|No|
|[22325784](https://www.ncbi.nlm.nih.gov/pubmed/22325784)|[10.1016/j.str.2011.11.021](https://doi.org/10.1016/j.str.2011.11.021)|Adkar|2012|DMS|Ccdb|E.coli|toxin activity|PCR with specific codons|Roche 454|No|XLS|
|[22371081](https://www.ncbi.nlm.nih.gov/pubmed/22371081)|[10.1038/nbt.2136](https://doi.org/10.1038/nbt.2136)|Patwardhan|2012|MPRA|ALDOB enhancer, ECR11 enhancer, LTV1 enhancer|mouse liver|Transcription|doped oligo synthesis|Illumina|[SRA049159](https://www.ebi.ac.uk/ena/data/view/SRA049159)|TXT|
|[22371084](https://www.ncbi.nlm.nih.gov/pubmed/22371084)|[10.1038/nbt.2137](https://doi.org/10.1038/nbt.2137)|Melnikov|2012|MPRA|cAMP-regulated enhancer, interferon-B enhancer|Human cell culture (HEK239T)|Transcription|in silico design and synthesis|Illumina|GSE31982|XLS|
|[22609971](https://www.ncbi.nlm.nih.gov/pubmed/22609971)|[10.1038/nbt.2205](https://doi.org/10.1038/nbt.2205)|Sharon|2012|MPRA|designed promoters|Yeast|Fluorescence, Transcription|microarray synthesis|Illumina|No|No|
|[22634563](https://www.ncbi.nlm.nih.gov/pubmed/22634563)|[10.1038/nbt.2214](https://doi.org/10.1038/nbt.2214)|Whitehead|2012|DMS|Designed influenza binder|Yeast|FACS|synthesized|Illlumina|No|No|
|[22665811](https://www.ncbi.nlm.nih.gov/pubmed/22665811)|[10.1073/pnas.1202107109](https://doi.org/10.1073/pnas.1202107109)|Schlinkmann|2012|DMS|Neurotensin receptor 1 GPCR|E.coli|FACS|NNN PCR|Roche 454|No|No|
|[22846908](https://www.ncbi.nlm.nih.gov/pubmed/22846908)|[10.1016/j.jmb.2012.07.017](https://doi.org/10.1016/j.jmb.2012.07.017)|Traxlmayr|2012|DMS|IgG|Yeast|FACS|error-prone PCR|Roche 454|No|No|
|[23017428](https://www.ncbi.nlm.nih.gov/pubmed/23017428)|[10.1016/j.jmb.2012.09.014](https://doi.org/10.1016/j.jmb.2012.09.014)|Deng|2012|DMS|TEM1 Beta-lactamase|E.coli|Amp resistance|NNS Kunkel|Roche 454|No|XLS|
|[23035249](https://www.ncbi.nlm.nih.gov/pubmed/23035249)|[10.1073/pnas.1209751109](https://doi.org/10.1073/pnas.1209751109)|Araya|2012|DMS|WW domain|Phage|Binding|doped oligo synthesis|Illumina|Yes|No|
|[23041932](https://www.ncbi.nlm.nih.gov/pubmed/23041932)|[10.1038/nature11500](https://doi.org/10.1038/nature11500)|McLaughlin|2012|DMS|PSD95 PDZ|Bacteria|Special|NNS PCR|Illumina|No|No|
|[23103372](https://www.ncbi.nlm.nih.gov/pubmed/23103372)|[10.1016/j.bbrc.2012.10.066](https://doi.org/10.1016/j.bbrc.2012.10.066)|Fujino|2012|DMS|Fab antibody fragment|in vitro|Ribodisplay|"PCR with ""fragments"""|Roche 454|No|No|
|[23152521](https://www.ncbi.nlm.nih.gov/pubmed/23152521)|[10.1128/JVI.01658-12](https://doi.org/10.1128/JVI.01658-12)|Wu|2012|DMS|Neuraminidase|Human/H1N1|Oseltamivir resistance|error prone pcr|Roche 454|No|No|
|[23241746](https://www.ncbi.nlm.nih.gov/pubmed/23241746)|[10.1101/gr.144659.112](https://doi.org/10.1101/gr.144659.112)|Liachko|2012|MPRA|Autonomously replicating sequences|Yeast|Growth|doped oligo synthesis|Illumina|[SRA051406](https://www.ebi.ac.uk/ena/data/view/SRA051406)|No|
|[23287719](https://www.ncbi.nlm.nih.gov/pubmed/23287719)|[10.1126/science.1230161](https://doi.org/10.1126/science.1230161)|Ernst|2013|DMS|Ubiquitin|Phage|Binding|site-directed mutagenesis with doped oligos|ELISA|No|No|
|[23376099](https://www.ncbi.nlm.nih.gov/pubmed/23376099)|[10.1016/j.jmb.2013.01.032](https://doi.org/10.1016/j.jmb.2013.01.032)|Roscoe|2013|DMS|Ubiquitin|Yeast|Growth|NNN PCR|Illumina|No|XLS|
|[23509263](https://www.ncbi.nlm.nih.gov/pubmed/23509263)|[10.1073/pnas.1303309110](https://doi.org/10.1073/pnas.1303309110)|Starita|2013|DMS|E4B|Phage|Auto-ubiquitination|doped oligo synthesis|Illumina (barcoded and subassembly)|No|XLS|
|[23512712](https://www.ncbi.nlm.nih.gov/pubmed/23512712)|[10.1101/gr.144899.112](https://doi.org/10.1101/gr.144899.112)|Kheradpour|2013|MPRA|Regulatory motifs for HNF1, HNF4, FOXA, GATA, NFE2L2, GFI1, ZFP161|Human cell culture (K562 and HepG2)|Transcription|microarray synthesis|Illumina|GSE33367|TXT|
|[23625929](https://www.ncbi.nlm.nih.gov/pubmed/23625929)|[10.1074/jbc.M112.447326](https://doi.org/10.1074/jbc.M112.447326)|Gold|2013|DMS|AKAP|Phage|Binding|doped oligo synthesis|Illumina|No|No|
|[23765106](https://www.ncbi.nlm.nih.gov/pubmed/23765106)|[10.4161/mabs.24979](https://doi.org/10.4161/mabs.24979)|Forsyth|2013|DMS|IgG|Human cells|FACS|NNK PCR|Roche 454|No|PDF|
|[23818646](https://www.ncbi.nlm.nih.gov/pubmed/23818646)|[10.1073/pnas.1307449110](https://doi.org/10.1073/pnas.1307449110)|White|2013|MPRA|Crx target sequences|Mouse retina|Transcription|microarray synthesis|Illumina|No|TXT|
|[23825969](https://www.ncbi.nlm.nih.gov/pubmed/23825969)|[10.1371/journal.pgen.1003600](https://doi.org/10.1371/journal.pgen.1003600)|Jiang|2013|DMS|Hsp90|Yeast|Growth|NNN PCR|Illumina|No|XLS|
|[23827138](https://www.ncbi.nlm.nih.gov/pubmed/23827138)|[10.1016/j.jmb.2013.06.035](https://doi.org/10.1016/j.jmb.2013.06.035)|Procko|2013|DMS|Designed protein binder|Yeast|FACS|site-directed mutagenesis and error-prone PCR|Illumina|No|No|
|[23878237](https://www.ncbi.nlm.nih.gov/pubmed/23878237)|[10.1073/pnas.1215206110](https://doi.org/10.1073/pnas.1215206110)|Jacquier|2013|DMS|TEM1 Beta-lactamase|E.coli|Amoxicillin resistance|single nucleotide random|Sanger!|No|XLS|
|[23892608](https://www.ncbi.nlm.nih.gov/pubmed/23892608)|[10.1038/ng.2713](https://doi.org/10.1038/ng.2713)|Smith|2013|MPRA|Synthetic liver enhancers|mouse primary liver, human HepG2 cell line|Transcription|designed combinations of binding sites|Illumina|[SRP018414](https://www.ebi.ac.uk/ena/data/view/SRP018414)|XLS|
|[23897579](https://www.ncbi.nlm.nih.gov/pubmed/23897579)|[10.1074/mcp.O113.031708](https://doi.org/10.1074/mcp.O113.031708)|Kim|2013|DMS|Yeast degron|Yeast|Growth|doped oligo synthesis|Illlumina|No|No|
|[23921661](https://www.ncbi.nlm.nih.gov/pubmed/23921661)|[10.1101/gr.157891.113](https://doi.org/10.1101/gr.157891.113)|Mogno|2013|MPRA|Synthetic promoters|Yeast|Transcription|Combinatorial|Illumina|No|TXT|
|[23924614](https://www.ncbi.nlm.nih.gov/pubmed/23924614)|[10.1073/pnas.1301301110](https://doi.org/10.1073/pnas.1301301110)|Kosuri|2013|MPRA|Synthetic promoters and ribosome binding sites|E.coli|Transcription and translation|designed combinations of binding sites|Illumina|No|XLS|
|[24005320](https://www.ncbi.nlm.nih.gov/pubmed/24005320)|[10.1038/nature12443](https://doi.org/10.1038/nature12443)|Tinberg|2013|DMS|Designed digoxigenin binder|Yeast|FACS|doped oligo synthesis|Illumina|No|PDF (Counts)|
|[24064791](https://www.ncbi.nlm.nih.gov/pubmed/24064791)|[10.1261/rna.040709.113](https://doi.org/10.1261/rna.040709.113)|Melamed|2013|DMS|Pab1|Yeast|Growth|doped oligo synthesis|Illumina|No|XLS|
|[24112705](https://www.ncbi.nlm.nih.gov/pubmed/24112705)|[10.1111/pcmr.12171](https://doi.org/10.1111/pcmr.12171)|Wagenaar|2013|DMS|BRAF V600E|Human|vemurafenib resistance|NNN PCR|Illumina|No|No|
|[24204297](https://www.ncbi.nlm.nih.gov/pubmed/24204297)|[10.1371/journal.pgen.1003882](https://doi.org/10.1371/journal.pgen.1003882)|Rockah-Shmuel|2012|DMS|M.HaeIII|E.coli|Indel read-through, activity|error-prone PCR|Illumina|No|No|
|[24299404](https://www.ncbi.nlm.nih.gov/pubmed/24299404)|[10.1111/evo.12207](https://doi.org/10.1111/evo.12207)|Hietpas|2013|DMS|Hsp90|Yeast|Growth|NNN PCR|Illumina|No|XLS|
|[24381156](https://www.ncbi.nlm.nih.gov/pubmed/24381156)|[10.1073/pnas.1313605111](https://doi.org/10.1073/pnas.1313605111)|Strauch|2014|DMS|Designed IgG|Yeast|FACS|error-prone PCR|Illumina|No|No|
|[24567513](https://www.ncbi.nlm.nih.gov/pubmed/24567513)|[10.1093/molbev/msu081](https://doi.org/10.1093/molbev/msu081)|Firnberg|2014|DMS|TEM-1 BL|Bacteria|Growth|PFunkel|Roche 454|No|XLS|
|[24603708](https://www.ncbi.nlm.nih.gov/pubmed/24603708)|[10.1371/journal.pgen.1004169](https://doi.org/10.1371/journal.pgen.1004169)|Liachko|2014|MPRA|Autonomously replicating sequences|Yeast|Growth|doped oligo synthesis|Illumina|[SRP031760](https://www.ebi.ac.uk/ena/data/view/SRP031760)|No|
|[24633241](https://www.ncbi.nlm.nih.gov/pubmed/24633241)|[10.1038/nbt.2851](https://doi.org/10.1038/nbt.2851)|Zhao|2014|MPRA|3' UTR|Human cell culture (BEAS-2B, Jurkat or WiDr cells)|mRNA stability and protein level|microarray synthesis|Illumina|[SRX463338](https://www.ebi.ac.uk/ena/data/view/SRX463338)|XLS|
|[24656821](https://www.ncbi.nlm.nih.gov/pubmed/24656821)|[10.1016/j.celrep.2014.03.001](https://doi.org/10.1016/j.celrep.2014.03.001)|Oikonomou|2014|MPRA|3' UTR|Human cells (FlpIn293)|FACS|microarray synthesis|Illumina|GSE55396|XLS|
|[24722365](https://www.ncbi.nlm.nih.gov/pubmed/24722365)|[10.1371/journal.ppat.1004064](https://doi.org/10.1371/journal.ppat.1004064)|Qi|2014|DMS|NS4B|Human cell culture (Huh-7.5.1)|Growth|NNK PCR|Illumina|No|XLS|
|[24859245](https://www.ncbi.nlm.nih.gov/pubmed/24859245)|[10.1093/molbev/msu173](https://doi.org/10.1093/molbev/msu173)|Bloom|2014|DMS|influenza nucleoprotein|Human/H1N1|viral replication|NNN PCR|Illumina|[SRP036064](https://www.ebi.ac.uk/ena/data/view/SRP036064)|XLS|
|[24862281](https://www.ncbi.nlm.nih.gov/pubmed/24862281)|[10.1016/j.jmb.2014.05.019](https://doi.org/10.1016/j.jmb.2014.05.019)|Roscoe|2014|DMS|Ubiquitin|Yeast|Binding|NNN PCR|Illumina|No|XLS|
|[24914046](https://www.ncbi.nlm.nih.gov/pubmed/24914046)|[10.1093/nar/gku511](https://doi.org/10.1093/nar/gku511)|Melnikov|2014|DMS|APH(3')II|Bacteria|Growth|microarray synthesis|Illumina|[SRP042113](https://www.ebi.ac.uk/ena/data/view/SRP042113)|TXT|
|[25006036](https://www.ncbi.nlm.nih.gov/pubmed/25006036)|[10.7554/eLife.03300](https://doi.org/10.7554/eLife.03300)|Thyagarajan|2014|DMS|Hemagglutinin|Influenza|Growth|NNN PCR|Illumina|[SRP040983](https://www.ebi.ac.uk/ena/data/view/SRP040983)|TXT|
|[25030889](https://www.ncbi.nlm.nih.gov/pubmed/25030889)|[10.1101/gr.168773.113](https://doi.org/10.1101/gr.168773.113)|Sharon|2014|MPRA|designed promoters|Yeast|Fluorescence, Transcription|?|Illlumina|GSE55346|TXT|
|[25064858](https://www.ncbi.nlm.nih.gov/pubmed/25064858)|[10.1093/nar/gku689](https://doi.org/10.1093/nar/gku689)|Gajula|2014|DMS|AID|E.coli|Growth|NNS PCR|Illumina|No|PDF (Counts)|
|[25085423](https://www.ncbi.nlm.nih.gov/pubmed/25085423)|[10.1101/gad.245936.114](https://doi.org/10.1101/gad.245936.114)|Guy|2014|DMS|tRNA|Yeast|FACS|doped oligo synthesis|Illumina|No|XLS|
|[25170020](https://www.ncbi.nlm.nih.gov/pubmed/25170020)|[10.15252/msb.20145136](https://doi.org/10.15252/msb.20145136)|Noderer|2014|DMS|Start codon efficiency|Mammalian cell culture|FACS|degenrate PCR|Illumina (barcoded)|No|TXT|
|[25311858](https://www.ncbi.nlm.nih.gov/pubmed/25311858)|[10.1016/j.jmb.2014.09.025](https://doi.org/10.1016/j.jmb.2014.09.025)|Reich|2015|DMS|BH3|Yeast|FACS|?|Illumina|No|No|
|[25371431](https://www.ncbi.nlm.nih.gov/pubmed/25371431)|[10.1093/molbev/msu301](https://doi.org/10.1093/molbev/msu301)|Bank|2015|DMS|Hsp90|Yeast|Growth|NNN PCR|Illumina|No|No|
|[25451031](https://www.ncbi.nlm.nih.gov/pubmed/25451031)|[10.1016/j.jmb.2014.10.024](https://doi.org/10.1016/j.jmb.2014.10.024)|Doolan|2015|DMS|PrP|Yeast|FACS|site-directed mutagenesis|PacBio|No|No|
|[25455030](https://www.ncbi.nlm.nih.gov/pubmed/25455030)|[10.1016/j.cub.2014.09.072](https://doi.org/10.1016/j.cub.2014.09.072)|Olson|2014|DMS|GB1|mRNA display|Binding|NNK PCR|Illumina|No|XLS|
|[25522661](https://www.ncbi.nlm.nih.gov/pubmed/25522661)|[10.1186/s12977-014-0124-6](https://doi.org/10.1186/s12977-014-0124-6)|Al-Mawsawi|2014|DMS|HIV genome|HIV|Growth|error-prone PCR|Illumina|[PRJNA259391](https://www.ebi.ac.uk/ena/data/view/PRJNA259391)|XLS|
|[25559584](https://www.ncbi.nlm.nih.gov/pubmed/25559584)|[10.1038/nmeth.3223](https://doi.org/10.1038/nmeth.3223)|Kitzman|2014|DMS|Gal4|Yeast|Growth|PALS (array+PCR)|Illumina (barcoded and subassembly)|[PRJNA268398](https://www.ebi.ac.uk/ena/data/view/PRJNA268398)|No|
|[25657251](https://www.ncbi.nlm.nih.gov/pubmed/25657251)|[10.1126/science.1257360](https://doi.org/10.1126/science.1257360)|Podgornaia|2015|DMS|PhoQ|Bacteria|FACS|NNS PCR|Illumina|No|No|
|[25723163](https://www.ncbi.nlm.nih.gov/pubmed/25723163)|[10.1016/j.cell.2015.01.035](https://doi.org/10.1016/j.cell.2015.01.035)|Stiffler|2015|DMS|TEM1 B-lactamase|E.coli|Growth|NNS PCR|Illumina|No|XLS|
|[25823446](https://www.ncbi.nlm.nih.gov/pubmed/25823446)|[10.1534/genetics.115.175802](https://doi.org/10.1534/genetics.115.175802)|Starita|2015|DMS|BRCA1|Yeast, Phage|Growth, Binding|microarray synthesis|Illumina (barcoded and subassembly)|No|XLS|
|[25875337](https://www.ncbi.nlm.nih.gov/pubmed/25875337)|[10.1371/journal.pgen.1005147](https://doi.org/10.1371/journal.pgen.1005147)|Shalem|2015|MPRA|3' UTR|Yeast|Fluorescence, Transcription|microarray synthesis|Illumina|No|XLS|
|[26040002](https://www.ncbi.nlm.nih.gov/pubmed/26040002)|[10.1073/pnas.1422285112](https://doi.org/10.1073/pnas.1422285112)|Romero|2015|DMS|Bgl2|Bacteria/microfluidic droplets|Activity|error-prone PCR|Illumina|No|No|
|[26132554](https://www.ncbi.nlm.nih.gov/pubmed/26132554)|[10.1371/journal.pgen.1005310](https://doi.org/10.1371/journal.pgen.1005310)|Wu|2015|DMS|Polymerase PA|Influenza|Growth|error-prone PCR|Illumina|[PRJNA254185](https://www.ebi.ac.uk/ena/data/view/PRJNA254185)|XLS|
|[26170332](https://www.ncbi.nlm.nih.gov/pubmed/26170332)|[10.1073/pnas.1511328112](https://doi.org/10.1073/pnas.1511328112)|Kretz|2015|DMS|VWF|Phage|Binding/cleavage|doped oligo synthesis|Illumina|No|XLS|
|[26226986](https://www.ncbi.nlm.nih.gov/pubmed/26226986)|[10.1093/molbev/msv167](https://doi.org/10.1093/molbev/msv167)|Doud|2015|DMS|Nucleoproteins|Influenza|Growth|NNN PCR|Illumina|[SRP056028](https://www.ebi.ac.uk/ena/data/view/SRP056028)|TXT|
|[26274323](https://www.ncbi.nlm.nih.gov/pubmed/26274323)|[10.1371/journal.pcbi.1004421](https://doi.org/10.1371/journal.pcbi.1004421)|Rockah-Shmuel|2015|DMS|M.HaeIII|Bacteria|Activity|error-prone PCR|Illumina|No|XLS|
|[26296891](https://www.ncbi.nlm.nih.gov/pubmed/26296891)|[10.1074/jbc.M115.676635](https://doi.org/10.1074/jbc.M115.676635)|Kowalsky|2015|DMS|IgG|Yeast|FACS|PFunkel|Illumina|No|TXT|
|[26369947](https://www.ncbi.nlm.nih.gov/pubmed/26369947)|[10.1021/acssynbio.5b00131](https://doi.org/10.1021/acssynbio.5b00131)|Klesmith|2015|DMS|LGK|E.coli|Growth|PFunkel|Illumina|No|No|
|[26478181](https://www.ncbi.nlm.nih.gov/pubmed/26478181)|[10.1016/j.cell.2015.09.055](https://doi.org/10.1016/j.cell.2015.09.055)|Aakre|2015|DMS|ParD|Bacteria|Growth|ProxiMax|Illumina|No|No|
|[26496609](https://www.ncbi.nlm.nih.gov/pubmed/26496609)|[10.1016/j.cell.2015.09.054](https://doi.org/10.1016/j.cell.2015.09.054)|Rosenberg|2015|MPRA|Splice sites|HEK293|Isoform occurrence|degenrate PCR|Illumina|GSE74070|No|
|[26576614](https://www.ncbi.nlm.nih.gov/pubmed/26576614)|[10.1101/gr.193789.115](https://doi.org/10.1101/gr.193789.115)|Shen|2016|MPRA|Promoters and enhancers|Mouse retina, mouse cortex|Transcription|capture of existing elements|Illumina|GSM1463994|XLS|
|[26626484](https://www.ncbi.nlm.nih.gov/pubmed/26626484)|[10.1016/j.molcel.2015.10.029](https://doi.org/10.1016/j.molcel.2015.10.029)|Vvedenskaya|2015|MPRA|TSS|Bacteria|Transcription|MASTER|Illumina|[SRP057850](https://www.ebi.ac.uk/ena/data/view/SRP057850)|XLS|
|[26637602](https://www.ncbi.nlm.nih.gov/pubmed/26637602)|[10.1128/AEM.03074-15](https://doi.org/10.1128/AEM.03074-15)|Jin|2015|DMS|ACD-1|Bacteria|Growth|doped oligo synthesis|Roche 454|[PRJEB11657](https://www.ebi.ac.uk/ena/data/view/PRJEB11657)|No|
|[26656922](https://www.ncbi.nlm.nih.gov/pubmed/26656922)|[10.1016/j.jmb.2015.11.027](https://doi.org/10.1016/j.jmb.2015.11.027)|Jiang|2016|DMS|Neuraminidase|Influenza|Growth|NNN PCR|Illumina|[PRJNA272490](https://www.ebi.ac.uk/ena/data/view/PRJNA272490)|XLS|
|[26689263](https://www.ncbi.nlm.nih.gov/pubmed/26689263)|[10.1038/nmeth.3696](https://doi.org/10.1038/nmeth.3696)|Taylor|2016|DMS|lac repressor|Bacteria|Growth|microarray synthesis|Illumina|GSE75009|No|
|[26716404](https://www.ncbi.nlm.nih.gov/pubmed/26716404)|[10.7554/eLife.09532](https://doi.org/10.7554/eLife.09532)|Sahoo|2015|DMS|CcdB, DgkA|Bacteria|Growth|NNN PCR|Roche 454|No|No|
|[26754751](https://www.ncbi.nlm.nih.gov/pubmed/26754751)|[10.1186/s12864-015-2358-7](https://doi.org/10.1186/s12864-015-2358-7)|Wu|2016|DMS|M segment|Influenza|Growth|error-prone PCR|Illumina|[PRJNA285135](https://www.ebi.ac.uk/ena/data/view/PRJNA285135)|XLS|
|[26779844](https://www.ncbi.nlm.nih.gov/pubmed/26779844)|[10.1002/pro.2881](https://doi.org/10.1002/pro.2881)|Foight|2016|DMS|CD40, TANK|Bacteria|FACS|NNK PCR|Illumina|No|No|
|[26824389](https://www.ncbi.nlm.nih.gov/pubmed/26824389)|[10.7554/eLife.12125](https://doi.org/10.7554/eLife.12125)|Elazar|2016|DMS|Transmembrane segment|Bacteria|Growth|NNS PCR|Illumina|No|No|
|[26865697](https://www.ncbi.nlm.nih.gov/pubmed/26865697)|[10.1534/g3.116.027904](https://doi.org/10.1534/g3.116.027904)|Hoggard|2016|MPRA|Autonomously replicating sequences|Yeast|Growth|doped oligo synthesis|Illumina|[SRP065331](https://www.ebi.ac.uk/ena/data/view/SRP065331)|No|
|[26936925](https://www.ncbi.nlm.nih.gov/pubmed/26936925)|[10.1534/genetics.116.188037](https://doi.org/10.1534/genetics.116.188037)|Rich|2016|MPRA|SUL1 promoter|Yeast|Growth|error-prone PCR|Illumina (barcoded and subassembly)|[PRJNA273419](https://www.ebi.ac.uk/ena/data/view/PRJNA273419)|XLS|
|[26941320](https://www.ncbi.nlm.nih.gov/pubmed/26941320)|[10.1126/science.aad6881](https://doi.org/10.1126/science.aad6881)|Winkelman|2016|MPRA|TSS|Bacteria|Transcription|MASTER|Illumina|No|No|
|[27013733](https://www.ncbi.nlm.nih.gov/pubmed/27013733)|[10.1126/science.aad9195](https://doi.org/10.1126/science.aad9195)|Jardine|2016|DMS|IgG|Yeast|FACS|NNK PCR|Illumina|No|No|
|[27068472](https://www.ncbi.nlm.nih.gov/pubmed/27068472)|[10.1016/j.celrep.2016.03.046](https://doi.org/10.1016/j.celrep.2016.03.046)|Mishra|2016|DMS|Hsp90|Yeast|Growth|NNN PCR|Illumina|No|XLS|
|[27080103](https://www.ncbi.nlm.nih.gov/pubmed/27080103)|[10.1126/science.aaf0965](https://doi.org/10.1126/science.aaf0965)|Puchta|2016|DMS|snoRNA U3|yeast|inducible covering allele|doped oligo synthesis|Illumina (barcoded)|GSE77709|TXT (Counts)|
|[27080104](https://www.ncbi.nlm.nih.gov/pubmed/27080104)|[10.1126/science.aae0568](https://doi.org/10.1126/science.aae0568)|Li|2016|DMS|tRNA(Arg-CCU)|yeast|tRNA folding stability|random single nucleotide|Illumina|[PRJNA311172](https://www.ebi.ac.uk/ena/data/view/PRJNA311172)|No|
|[27111525](https://www.ncbi.nlm.nih.gov/pubmed/27111525)|[10.7554/eLife.15802](https://doi.org/10.7554/eLife.15802)|Mavor|2016|DMS|Ubiquitin|Yeast|Growth|NNN PCR|Illumina (barcoded)|[SRR3194828](https://www.ebi.ac.uk/ena/data/view/SRR3194828)|No|
|[27161764](https://www.ncbi.nlm.nih.gov/pubmed/27161764)|[10.1038/ncomms11558](https://doi.org/10.1038/ncomms11558)|Julien|2016|MPRA|FAS/CD95|Human|splicing|commercial library cassete ligation|collapsing read pairs|[PRJEB13140](https://www.ebi.ac.uk/ena/data/view/PRJEB13140)|XLS|
|[27162333](https://www.ncbi.nlm.nih.gov/pubmed/27162333)|[10.1073/pnas.1603271113](https://doi.org/10.1073/pnas.1603271113)|Vvedenskaya|2016|MPRA|TSS|in vitro, E.coli|Transcription|MASTER|Illumina|[SRP071742](https://www.ebi.ac.uk/ena/data/view/SRP071742)|No|
|[27173379](https://www.ncbi.nlm.nih.gov/pubmed/27173379)|[10.1016/j.jmb.2016.04.033](https://doi.org/10.1016/j.jmb.2016.04.033)|Steinberg|2016|DMS|TEM1 Beta-lactamase|E.coli|Amp resistance|PFunkel|Roche 454|No|XLS|
|[27193686](https://www.ncbi.nlm.nih.gov/pubmed/27193686)|[10.1038/nature17995](https://doi.org/10.1038/nature17995)|Sarkisyan|2016|DMS|GFP|Bacteria|Activity|error-prone PCR|Illumina|PRJNA282342.|TXT|
|[27259153](https://www.ncbi.nlm.nih.gov/pubmed/27259153)|[10.1016/j.cell.2016.04.027](https://doi.org/10.1016/j.cell.2016.04.027)|Tewhey|2016|MPRA|eQTL peaks|Human cell lines (NA12878, NA19239, HepG22)|Transcription|microarray synthesis|Illumina|GSE75661|XLS|
|[27259154](https://www.ncbi.nlm.nih.gov/pubmed/27259154)|[10.1016/j.cell.2016.04.048](https://doi.org/10.1016/j.cell.2016.04.048)|Ulirsch|2016|MPRA|GWAS peaks|Human cell lines (K562)|Transcription|microarray synthesis|Illumina|No|No|
|[27271655](https://www.ncbi.nlm.nih.gov/pubmed/27271655)|[10.3390/v8060155](https://doi.org/10.3390/v8060155)|Doud|2016|DMS|Hemagglutinin|Influenza|Growth|NNN PCR|Illumina|[PRJNA309339](https://www.ebi.ac.uk/ena/data/view/PRJNA309339)|TXT|
|[27374328](https://www.ncbi.nlm.nih.gov/pubmed/27374328)|[10.1016/j.cell.2016.05.070](https://doi.org/10.1016/j.cell.2016.05.070)|Gamble|2016|DMS|GFP|Yeast|FACS|NNN/VNN PCR|Illumina|No|No|
|[27391790](https://www.ncbi.nlm.nih.gov/pubmed/27391790)|[10.7554/eLife.16965](https://doi.org/10.7554/eLife.16965)|Wu|2016|DMS|GB1|mRNA display|Binding|random single nucleotide|Illumina|[PRJNA278685](https://www.ebi.ac.uk/ena/data/view/PRJNA278685)|XLS|
|[27563054](https://www.ncbi.nlm.nih.gov/pubmed/27563054)|[10.1093/molbev/msw182](https://doi.org/10.1093/molbev/msw182)|Tripathi|2016|DMS|CcdB|E.coli|Growth|NNK PCR|Illumina|No|No|
|[27681597](https://www.ncbi.nlm.nih.gov/pubmed/27681597)|[10.1074/jbc.M116.748681](https://doi.org/10.1074/jbc.M116.748681)|Harris|2016|DMS|TCR|Yeast|FACS|site-directed mutagenesis|?|No|No|
|[27699856](https://www.ncbi.nlm.nih.gov/pubmed/27699856)|[10.1002/prot.25175](https://doi.org/10.1002/prot.25175)|Kowalsky|2016|DMS|cohesin|Yeast|FACS|NNN PCR|Illlumina|No|TXT|
|[27701403](https://www.ncbi.nlm.nih.gov/pubmed/27701403)|[10.1038/nbt.3678](https://doi.org/10.1038/nbt.3678)|Ernst|2016|MPRA|H3K27ac sites|Human cell lines (K562, HepG2)|Transcription|microarray synthesis|Illumina|GSE71279|TXT|
|[27749844](https://www.ncbi.nlm.nih.gov/pubmed/27749844)|[10.1038/ng.3700](https://doi.org/10.1038/ng.3700)|Majithia|2016|DMS|PPARG|Human cells|FACS|microarray synthesis|Illumina|No|No|
|[27760319](https://www.ncbi.nlm.nih.gov/pubmed/27760319)|[10.1016/j.celrep.2016.09.061](https://doi.org/10.1016/j.celrep.2016.09.061)|Brenan|2016|DMS|Mapk1/Erk2|Human|inhibitor resistance|microarray synthesis|Illumina|No|XLS|
|[27898685](https://www.ncbi.nlm.nih.gov/pubmed/27898685)|[10.1371/journal.pgen.1006321](https://doi.org/10.1371/journal.pgen.1006321)|Qiu|2016|DMS|RNAPII trigger loop|Yeast|Growth|site-directed mutagenesis|Illumina|[PRJNA340979](https://www.ebi.ac.uk/ena/data/view/PRJNA340979)|No|
|[27959955](https://www.ncbi.nlm.nih.gov/pubmed/27959955)|[10.1371/journal.ppat.1006114](https://doi.org/10.1371/journal.ppat.1006114)|Haddox|2016|DMS|Env|HIV|Growth|NNN PCR|Illumina|[PRJNA320270](https://www.ebi.ac.uk/ena/data/view/PRJNA320270)|TXT|
|[27974464](https://www.ncbi.nlm.nih.gov/pubmed/27974464)|[10.1074/jbc.M116.764225](https://doi.org/10.1074/jbc.M116.764225)|van Rosmalen|2017|DMS|Cyclic peptide|Yeast|FACS|site-directed mutagenesis|Illumina|No|No|
|[27984726](https://www.ncbi.nlm.nih.gov/pubmed/27984726)|[10.1016/j.cell.2016.11.031](https://doi.org/10.1016/j.cell.2016.11.031)|Fernandes|2016|DMS|Tat, Rev|HIV|Growth|NNN PCR|Illumina|E-MTAB-5154|XLS|
|[28007883](https://www.ncbi.nlm.nih.gov/pubmed/28007883)|[10.1534/genetics.116.196428](https://doi.org/10.1534/genetics.116.196428)|Keskin|2017|DMS|Fis1p|Yeast|Growth|site-directed mutagenesis|Illumina|10.5061/dryad.j14r5|XLS (Counts)|
|[28009265](https://www.ncbi.nlm.nih.gov/pubmed/28009265)|[10.1016/j.cels.2016.11.004](https://doi.org/10.1016/j.cels.2016.11.004)|Kelsic|2016|DMS|infA|Bacteria|Growth|MAGE|amplicon|E-MTAB-4020|TXT|
|[28024160](https://www.ncbi.nlm.nih.gov/pubmed/28024160)|[10.1038/nmeth.4121](https://doi.org/10.1038/nmeth.4121)|Yartseva|2017|MPRA|mRNA stability|Zebrafish|Transcription|selected RNA sequences|Illumina|[SRP090954](https://www.ebi.ac.uk/ena/data/view/SRP090954)|No|
|[28035901](https://www.ncbi.nlm.nih.gov/pubmed/28035901)|[10.7554/eLife.23156](https://doi.org/10.7554/eLife.23156)|Adams|2016|DMS|scFV antibody|Yeast|Yeast display|Cassette Ligation|Illumina|[PRJNA344711](https://www.ebi.ac.uk/ena/data/view/PRJNA344711)|CSV|
|[28057863](https://www.ncbi.nlm.nih.gov/pubmed/28057863)|[10.1073/pnas.1613231114](https://doi.org/10.1073/pnas.1613231114)|Koenig|2017|DMS|IgG|Phage|Binding|NNK PCR|Illumina|No|No|
|[28137873](https://www.ncbi.nlm.nih.gov/pubmed/28137873)|[10.1073/pnas.1621150114](https://doi.org/10.1073/pnas.1621150114)|Grossman|2017|MPRA|natural and synthetic enhancers|mouse|Transcription|microarray synthesis|Illumina (barcoded)|GSE84888|No|
|[28196882](https://www.ncbi.nlm.nih.gov/pubmed/28196882)|[10.1073/pnas.1614437114](https://doi.org/10.1073/pnas.1614437114)|Klesmith|2017|DMS|TEM-1 BL, LGK|Yeast, Bacteria|FACS, Growth|NNN PCR|Illumina|No|No|
|[28204611](https://www.ncbi.nlm.nih.gov/pubmed/28204611)|[10.1093/nar/gkw942](https://doi.org/10.1093/nar/gkw942)|Maricque|2017|MPRA|genomic regions|Human cells|Transcription|microarray synthesis|Illumina|No|No|
|[28212748](https://www.ncbi.nlm.nih.gov/pubmed/28212748)|[10.1016/j.molcel.2017.01.007](https://doi.org/10.1016/j.molcel.2017.01.007)|Levo|2017|MPRA|yeast promoters|Yeast|Transcription|microarray synthesis|Illumina|GSE92300|XLS|
|[28262665](https://www.ncbi.nlm.nih.gov/pubmed/28262665)|[10.1038/ncomms14614](https://doi.org/10.1038/ncomms14614)|Chan|2017|DMS|IGPS|Yeast|Growth|NNN PCR|Illumina|No|No|
|[28288189](https://www.ncbi.nlm.nih.gov/pubmed/28288189)|[10.1371/journal.ppat.1006271  ](https://doi.org/10.1371/journal.ppat.1006271  )|Doud|2017|DMS|HA|Influenza|Antibody binding|NNN PCR|Illlumina|SAMN05789126 |TXT|
|[28335006](https://www.ncbi.nlm.nih.gov/pubmed/28335006)|[10.1093/nar/gkx183](https://doi.org/10.1093/nar/gkx183)|Matreyek|2017|DMS|GFP N-terminal codon|Human cell lines (HEK293T)|FACS|oligo synthesis|Illumina (barcoded)|[SRP095490](https://www.ebi.ac.uk/ena/data/view/SRP095490)|TXT|
|[28346537](https://www.ncbi.nlm.nih.gov/pubmed/28346537)|[10.1371/journal.ppat.1006288](https://doi.org/10.1371/journal.ppat.1006288)|Ashenberg|2017|DMS|NP|Virus|Growth|NNN PCR|Illumina|[SRP082554](https://www.ebi.ac.uk/ena/data/view/SRP082554)|TXT|
|[28585537](https://www.ncbi.nlm.nih.gov/pubmed/28585537)|[10.1038/ncomms15695](https://doi.org/10.1038/ncomms15695)|Wrenbeck|2017|DMS|amiE|E.coli|Growth|Pfunkel|Illumina|[PRJNA360623](https://www.ebi.ac.uk/ena/data/view/PRJNA360623)|TXT|
|[28618270](https://www.ncbi.nlm.nih.gov/pubmed/28618270)|[10.1016/j.chom.2017.05.011](https://doi.org/10.1016/j.chom.2017.05.011)|Wu|2017|DMS|HA RBS|Human cells|Growth|NNK PCR|amplicon|[PRJNA353496](https://www.ebi.ac.uk/ena/data/view/PRJNA353496)|XLS|
|[28652265](https://www.ncbi.nlm.nih.gov/pubmed/28652265)|[10.1158/1541-7786.MCR-17-0245](https://doi.org/10.1158/1541-7786.MCR-17-0245)|Bhagavatula|2017|DMS|TP53 synonymous|HEK293T|FACS|doped oligo synthesis|Illumina|[PRJNA384242](https://www.ebi.ac.uk/ena/data/view/PRJNA384242)|No|
|[28686159](https://www.ncbi.nlm.nih.gov/pubmed/28686159)|[10.7554/eLife.27810](https://doi.org/10.7554/eLife.27810)|Bandaru|2017|DMS|Ras|Bacteria|activity|NNS PCR|Illlumina|No|XLS|
|[28902834](https://www.ncbi.nlm.nih.gov/pubmed/28902834)|[10.1038/nature23902](https://doi.org/10.1038/nature23902)|Starr|2017|DMS|ancestral RH|Yeast|FACS|NNK PCR|Illumina|[PRJNA362734](https://www.ebi.ac.uk/ena/data/view/PRJNA362734)|No|
|[29039417](https://www.ncbi.nlm.nih.gov/pubmed/29039417)|[10.1038/nmeth.4464](https://doi.org/10.1038/nmeth.4464)|Woodsmith|2017|DMS|BBSome|yeast|Y2H|PALS (array+PCR)|simple deep sequencing|[PRJNA407860](https://www.ebi.ac.uk/ena/data/view/PRJNA407860)|XLS|
|[29078326](https://www.ncbi.nlm.nih.gov/pubmed/29078326)|[10.1073/pnas.1708268114](https://doi.org/10.1073/pnas.1708268114)|Ma|2017|DMS|BCR-ABL|Ba/F3 cells|Growth|CRISPR|Illumina|No|No|
|[29097404](https://www.ncbi.nlm.nih.gov/pubmed/29097404)|[10.1101/gr.224964.117](https://doi.org/10.1101/gr.224964.117)|Cuperus|2017|MPRA|5' UTR|yeast|Growth|random oligos|Illumina|GSE104252|XLS|
|[29203891](https://www.ncbi.nlm.nih.gov/pubmed/29203891)|[10.1038/s41598-017-17081-y](https://doi.org/10.1038/s41598-017-17081-y)|Spencer|2017|DMS|Cas9|Bacteria|Growth|error-prone PCR|Illumina|[SRP107783](https://www.ebi.ac.uk/ena/data/view/SRP107783)|XLS|
|[29225039](https://www.ncbi.nlm.nih.gov/pubmed/29225039)|[10.1016/j.molcel.2017.11.014](https://doi.org/10.1016/j.molcel.2017.11.014)|Rabani|2017|MPRA|3' UTR|Zebrafish|Transcript abundance|known UTRs|Illumina|GSE106677|XLS|
|[29242188](https://www.ncbi.nlm.nih.gov/pubmed/29242188)|[10.1101/gr.219683.116](https://doi.org/10.1101/gr.219683.116)|Ke|2017|MPRA|DHFR exon 1-5|human|splicing|microarray synthesis|Illumina|GSE105785|XLS|
|[29269382](https://www.ncbi.nlm.nih.gov/pubmed/29269382)|[10.15252/msb.20177908](https://doi.org/10.15252/msb.20177908)|Weile|2017|DMS|UBE2I, SUMO1, TPK1, CALM1-3|yeast|complementation|popcode|Barseq+TileSeq (Illumina)|[PRJNA390305](https://www.ebi.ac.uk/ena/data/view/PRJNA390305)|TXT|
|[29301959](https://www.ncbi.nlm.nih.gov/pubmed/29301959)|[10.1126/science.aao5167](https://doi.org/10.1126/science.aao5167)|Plesa|2018|DMS|PPAT|E.coli|Growth|ortholog synthesis|Illumina|[SRP126669](https://www.ebi.ac.uk/ena/data/view/SRP126669)|XLS|
|[29410437](https://www.ncbi.nlm.nih.gov/pubmed/29410437)|[10.1038/s41467-018-02980-z](https://doi.org/10.1038/s41467-018-02980-z)|Vainberg Slutskin|2018|MPRA|microRNA|K562|FACS|microarray synthesis|Illumina|[SRP128656](https://www.ebi.ac.uk/ena/data/view/SRP128656)|No|
|[29525204](https://www.ncbi.nlm.nih.gov/pubmed/29525204)|[10.1016/j.cels.2018.01.015](https://doi.org/10.1016/j.cels.2018.01.015)|Staller|2018|DMS|Gcn4|Yeast|FACS|microarray synthesis|Illumina|10.17632/rbfr6m4733.1|TXT|
|[29638215](https://www.ncbi.nlm.nih.gov/pubmed/29638215)|[10.7554/eLife.32472](https://doi.org/10.7554/eLife.32472)|Diss|2018|DMS|AP-1|Yeast|Growth|doped oligo synthesis|Illumina|GSE102901|XLS|
|[29643335](https://www.ncbi.nlm.nih.gov/pubmed/29643335)|[10.1038/s41467-018-03783-y](https://doi.org/10.1038/s41467-018-03783-y)|Hartman|2018|DMS|MS2 phage capsid|MS2|SyMAPS|NNN PCR|Illumina|No|XLS|
|[29643370](https://www.ncbi.nlm.nih.gov/pubmed/29643370)|[10.1038/s41467-018-03665-3](https://doi.org/10.1038/s41467-018-03665-3)|Doud|2018|DMS|H1 hemaglutinin|Influenza|Growth|NNN PCR|Illumina|[SAMN05789126](https://www.ebi.ac.uk/ena/data/view/SAMN05789126)|TXT|
|[29706350](https://www.ncbi.nlm.nih.gov/pubmed/29706350)|[10.1016/j.ajhg.2018.03.018](https://doi.org/10.1016/j.ajhg.2018.03.018)|Mighell|2018|DMS|PTEN|Yeast|lipid phosphatase activity|MITE|Illumina|[SRP134135](https://www.ebi.ac.uk/ena/data/view/SRP134135)|XLS|
|[29728462](https://www.ncbi.nlm.nih.gov/pubmed/29728462)|[10.1073/pnas.1722055115](https://doi.org/10.1073/pnas.1722055115)|Belliveau|2018|MPRA|lacZYA, relBE, marRAB, yebG, purT, xylE, dgoRKADT promoters|E.coli|FACS|Cassette Ligation|Illumina|[SRP121362](https://www.ebi.ac.uk/ena/data/view/SRP121362)|CSV|
|[29785012](https://www.ncbi.nlm.nih.gov/pubmed/29785012)|[10.1038/s41588-018-0122-z](https://doi.org/10.1038/s41588-018-0122-z)|Matreyek|2018|DMS|PTEN + TPMT|human|Protein stability|inverse PCR|Illumina (barcoded and subassembly)|[PRJNA428380](https://www.ebi.ac.uk/ena/data/view/PRJNA428380)|XLS|
|[29931269](https://www.ncbi.nlm.nih.gov/pubmed/29931269)|[10.1093/nar/gky550](https://doi.org/10.1093/nar/gky550)|Mason|2018|DMS|CDR|PnP hybridoma cells|FACS|CRISPR|Illumina|No|No|
|[29979965](https://www.ncbi.nlm.nih.gov/pubmed/29979965)|[10.1016/j.molcel.2018.06.012](https://doi.org/10.1016/j.molcel.2018.06.012)|Kotler|2018|DMS|TP53|HEK293T|Growth|microarray synthesis|Illumina|GSE115072|XLS|
|[30012625](https://www.ncbi.nlm.nih.gov/pubmed/30012625)|[10.1073/pnas.1803598115](https://doi.org/10.1073/pnas.1803598115)|Cantor|2018|DMS|EGFR|E.coli|FACS|NNS PCR|Illlumina|No|No|
|[30024376](https://www.ncbi.nlm.nih.gov/pubmed/30024376)|[10.7554/eLife.34300](https://doi.org/10.7554/eLife.34300)|Salinas|2018|DMS|PDZ|Bacteria|activity|NNS PCR|Illumina|No|No|
|[30037883](https://www.ncbi.nlm.nih.gov/pubmed/30037883)|[10.1242/bio.036103](https://doi.org/10.1242/bio.036103)|Mavor|2018|DMS|Ubiquitin|Yeast|Growth|NNN PCR|Illumina (barcoded)|[SRP070953](https://www.ebi.ac.uk/ena/data/view/SRP070953)|No|
|[30068600](https://www.ncbi.nlm.nih.gov/pubmed/30068600)|[10.1073/pnas.1805882115](https://doi.org/10.1073/pnas.1805882115)|Dorrity|2018|DMS|Ste12|Yeast|Mating/Invasion|doped oligo synthesis|Illumina|[PRJNA379449](https://www.ebi.ac.uk/ena/data/view/PRJNA379449)|XLS|
|[30079747](https://www.ncbi.nlm.nih.gov/pubmed/30079747)|[10.1164/rccm.201802-0337OC](https://doi.org/10.1164/rccm.201802-0337OC)|Castaldi|2019|MPRA|FAM13A locus|human|Transcription|microarray synthesis|Illumina|No|No|
|[30104379](https://www.ncbi.nlm.nih.gov/pubmed/30104379)|[10.1073/pnas.1806133115](https://doi.org/10.1073/pnas.1806133115)|Lee|2018|DMS|HA|Virus|Growth|NNN PCR|Illumina|SAMN08102609,  SAMN08102610|TXT|
|[30174293](https://www.ncbi.nlm.nih.gov/pubmed/30174293)|[10.1016/j.molcel.2018.07.033](https://doi.org/10.1016/j.molcel.2018.07.033)|Wong|2018|MPRA|Splice sites|HeLa|Transcription|?|Illumina|[SRP135892](https://www.ebi.ac.uk/ena/data/view/SRP135892)|No|
|[30188321](https://www.ncbi.nlm.nih.gov/pubmed/30188321)|[10.7554/eLife.38795](https://doi.org/10.7554/eLife.38795)|Phillips|2018|DMS|HA|Influenza|Growth|NNN PCR|Illumina|[SRP149672](https://www.ebi.ac.uk/ena/data/view/SRP149672)|TXT|
|[30209399](https://www.ncbi.nlm.nih.gov/pubmed/30209399)|[10.1038/s41586-018-0461-z](https://doi.org/10.1038/s41586-018-0461-z)|Findlay|2018|DMS|BRCA1|HAP1|Growth|microarray synthesis + CRISPR|Illumina|No|XLS|
|[30219179](https://www.ncbi.nlm.nih.gov/pubmed/30219179)|[10.1016/j.ajhg.2018.07.016](https://doi.org/10.1016/j.ajhg.2018.07.016)|Starita|2018|DMS|BRCA1|human|DNA-repair assay|NNK PCR|Illumina|GSE116427|XLS|
|[30224458](https://www.ncbi.nlm.nih.gov/pubmed/30224458)|[10.1073/pnas.1811993115](https://doi.org/10.1073/pnas.1811993115)|Blaesi|2018|DMS|RNR|Bacteria|Growth|NNS PCR|Illumina|No|No|
|[30224644](https://www.ncbi.nlm.nih.gov/pubmed/30224644)|[10.1038/s41588-018-0204-y](https://doi.org/10.1038/s41588-018-0204-y)|Giacomelli|2018|DMS|TP53|human|Growth|microarray synthesis|Illumina|No|XLS|
|[30258049](https://www.ncbi.nlm.nih.gov/pubmed/30258049)|[10.1038/s41467-018-06403-x](https://doi.org/10.1038/s41467-018-06403-x)|Naftaly|2018|DMS|APPI|Yeast|FACS|NNS PCR|Illumina|No|No|
|[30478237](https://www.ncbi.nlm.nih.gov/pubmed/30478237)|[10.15252/msb.20188371](https://doi.org/10.15252/msb.20188371)|Bassalo|2018|DMS|Lysine metabolic pathway|Bacteria|Growth|microarray synthesis|Illumina|No|XLS|
|[30503770](https://www.ncbi.nlm.nih.gov/pubmed/30503770)|[10.1016/j.molcel.2018.10.037](https://doi.org/10.1016/j.molcel.2018.10.037)|Cheung|2019|MPRA|Splice sites|human cells|FACS|microarray synthesis|Illlumina|GSE120695|No|
|[30716072](https://www.ncbi.nlm.nih.gov/pubmed/30716072)|[10.1371/journal.pcbi.1006226](https://doi.org/10.1371/journal.pcbi.1006226)|Barnes|2019|MPRA|LacI binding site|E.coli|FACS|Cassette Ligation|Illumina|[SRP146291](https://www.ebi.ac.uk/ena/data/view/SRP146291)|CSV|
|[30778069](https://www.ncbi.nlm.nih.gov/pubmed/30778069)|[10.1038/s41467-019-08777-y](https://doi.org/10.1038/s41467-019-08777-y)|Michaels|2019|MPRA|microRNA|HEK293T|polysome profiling|degenerate oligos|Illumina|[PRJNA516224](https://www.ebi.ac.uk/ena/data/view/PRJNA516224)|No|
|[30936490](https://www.ncbi.nlm.nih.gov/pubmed/30936490)|[10.1038/s41564-019-0412-y](https://doi.org/10.1038/s41564-019-0412-y)|Noda-Garcia|2019|DMS|GDH|Bacteria|Growth|NNS PCR|Illumina|No|XLS|
|[30956043](https://www.ncbi.nlm.nih.gov/pubmed/30956043)|[10.1016/j.molcel.2019.02.003](https://doi.org/10.1016/j.molcel.2019.02.003)|Ahler|2019|DMS|Src|Yeast|Growth|NNK PCR|Illumina (barcoded and subassembly)|GSE114098|XLS|
|[31267113](https://www.ncbi.nlm.nih.gov/pubmed/31267113)|[10.1038/s41587-019-0164-5](https://doi.org/10.1038/s41587-019-0164-5)|Sample|2019|MPRA|5' UTR|human cells|polysome profiling|random bases|Illumina|GSE114002|No|
|[31395865](https://www.ncbi.nlm.nih.gov/pubmed/31395865)|[10.1038/s41467-019-11526-w](https://doi.org/10.1038/s41467-019-11526-w)|Kircher|2019|MPRA|Multiple mammalian promoters and enhancers|multiple cell lines|Transcription|error-prone PCR|Illumina|GSE126550 |TXT|
|[31697803](https://www.ncbi.nlm.nih.gov/pubmed/31697803)|[10.1182/blood.2019002561  ](https://doi.org/10.1182/blood.2019002561  )|Bridgford|2020|DMS|MPL|Ba/F3 cells|Growth|NNN PCR|Illlumina|[SRR10193506](https://www.ebi.ac.uk/ena/data/view/SRR10193506)|TXT|
|[32385156](https://www.ncbi.nlm.nih.gov/pubmed/32385156)|[10.1073/pnas.1918680117 ](https://doi.org/10.1073/pnas.1918680117 )|Mehlhoff|2020|DMS|TEM-1 BL|E.coli|Growth|NNN PCR|Illlumina|PRJNA565437 |XLS|
|[32554590](https://www.ncbi.nlm.nih.gov/pubmed/32554590)|[10.1126/science.aaz5143](https://doi.org/10.1126/science.aaz5143)|Wu|2020|DMS|HA|Influenza|Growth|NNS/NNK PCR|Illlumina|PRJNA510654, PRJNA493101, PRJNA510700 |TXT|
|-|[10.1101/2020.06.17.157982](https://doi.org/10.1101/2020.06.17.157982)|Starr|2020|DMS|SARS-CoV-2 spike|yeast|Yeast display|NNS PCR|Illlumina|PRJNA639956 |TXT|
|[32144244](https://www.ncbi.nlm.nih.gov/pubmed/32144244)|[10.1038/s41467-020-15102-5](https://doi.org/10.1038/s41467-020-15102-5)|Wu|2020|DMS|HA|||||||
|[32181350](https://www.ncbi.nlm.nih.gov/pubmed/32181350)|[10.1126/sciadv.aay7505](https://doi.org/10.1126/sciadv.aay7505)|Penn|2020|DMS|rhodopsin|||||||
|[31442220](https://www.ncbi.nlm.nih.gov/pubmed/31442220)|[10.1371/journal.pcbi.1007207 ](https://doi.org/10.1371/journal.pcbi.1007207 )|Warszawski|2019|DMS|IgG|||||||
|[30977563](https://www.ncbi.nlm.nih.gov/pubmed/30977563)|[10.1002/humu.23762 ](https://doi.org/10.1002/humu.23762 )|Wan|2019|DMS(maybe)|rhodopsin|||||||
|[32152544](https://www.ncbi.nlm.nih.gov/pubmed/32152544)|[10.1038/s41589-020-0480-6 ](https://doi.org/10.1038/s41589-020-0480-6 )|Newberry|2020|DMS|alpha-synuclein|||||||
|[32175691](https://www.ncbi.nlm.nih.gov/pubmed/32175691)|[10.15252/msb.20199265 ](https://doi.org/10.15252/msb.20199265 )|Choudhury|2020|DMS|rpoB|||||||
|[32187529](https://www.ncbi.nlm.nih.gov/pubmed/32187529)|[10.1016/j.molcel.2020.02.023 ](https://doi.org/10.1016/j.molcel.2020.02.023 )|Schmid-Burgk|2020|DMS(maybe)|Cas9|||||||
|[32511321](https://www.ncbi.nlm.nih.gov/pubmed/32511321)|[10.1101/2020.03.16.994236 ](https://doi.org/10.1101/2020.03.16.994236 )|Procko|2020|DMS|ACE2|||||||
|[32094176](https://www.ncbi.nlm.nih.gov/pubmed/32094176)|[10.1073/pnas.1915680117 ](https://doi.org/10.1073/pnas.1915680117 )|Suiter|2020|DMS|NUDT15|||||||
|[32238226](https://www.ncbi.nlm.nih.gov/pubmed/32238226)|[10.1099/mgen.0.000364 ](https://doi.org/10.1099/mgen.0.000364 )|Andrews|2020|DMS|LamB|||||||
|-|[10.1101/2020.04.01.020487 ](https://doi.org/10.1101/2020.04.01.020487 )|Russ|2020|DMS(maybe)|Chorismate mutase|||||||
|[32004414](https://www.ncbi.nlm.nih.gov/pubmed/32004414)|[10.1111/cts.12758 ](https://doi.org/10.1111/cts.12758 )|Zhang|2020|DMS|CYP2C9, CYP2C19|||||||
|-|[10.1101/2020.05.01.072884 ](https://doi.org/10.1101/2020.05.01.072884 )|Newberry|2020|DMS|alpha-synuclein|||||||
|-|[10.1101/2020.05.10.087312 ](https://doi.org/10.1101/2020.05.10.087312 )|Chiasson|2020|DMS|VKOR|||||||
|-|[10.1101/2020.06.26.174375 ](https://doi.org/10.1101/2020.06.26.174375 )|Nedrud|2020|DMS|PSD95 PDZ|||||||
|[31925410](https://www.ncbi.nlm.nih.gov/pubmed/31925410)|[10.1038/s41594-019-0358-z ](https://doi.org/10.1038/s41594-019-0358-z )|Persky|2020|DMS|CDK4, CDK6|||||||
|[29813059](https://www.ncbi.nlm.nih.gov/pubmed/29813059)|[10.1371/journal.pgen.1007419 ](https://doi.org/10.1371/journal.pgen.1007419 )|Dandage|2018|DMS|GmR|||||||
|-|[10.1101/623108 ](https://doi.org/10.1101/623108 )|Jones|2020|DMS|ADRB2|||||||
|[29678950](https://www.ncbi.nlm.nih.gov/pubmed/29678950)|[10.4049/jimmunol.1800343 ](https://doi.org/10.4049/jimmunol.1800343 )|Heredia|2018|DMS|CXCR4, CCR5|||||||
|[25141179](https://www.ncbi.nlm.nih.gov/pubmed/25141179)|[10.1038/nature13695 ](https://doi.org/10.1038/nature13695 )|Findlay|2014|DMS|DBR1|||||||
|[30969963](https://www.ncbi.nlm.nih.gov/pubmed/30969963)|[10.1371/journal.pgen.1008079 ](https://doi.org/10.1371/journal.pgen.1008079 )|Pokusaeva|2019|DMS(maybe)|IGPD|||||||
|[29590010](https://www.ncbi.nlm.nih.gov/pubmed/29590010)|[10.7554/eLife.34420 ](https://doi.org/10.7554/eLife.34420 )|Haddox|2018|DMS|Env|||||||
|[27741319](https://www.ncbi.nlm.nih.gov/pubmed/27741319)|[10.1371/journal.pone.0164296 ](https://doi.org/10.1371/journal.pone.0164296 )|Gaiotto|2016|DMS|HA|||||||
|[28585908](https://www.ncbi.nlm.nih.gov/pubmed/28585908)|[10.1080/19420862.2017.1337618 ](https://doi.org/10.1080/19420862.2017.1337618 )|Koenig|2017|DMS|IgG heavy chain|||||||
|[26088137](https://www.ncbi.nlm.nih.gov/pubmed/26088137)|[10.1074/jbc.M115.662783 ](https://doi.org/10.1074/jbc.M115.662783 )|Koenig|2015|DMS|IgG CDR|||||||
|[30721031](https://www.ncbi.nlm.nih.gov/pubmed/30721031)|[10.1021/acssynbio.8b00486 ](https://doi.org/10.1021/acssynbio.8b00486 )|Wrenbeck|2019|DMS|Polyketide synthase|||||||
|[31400199](https://www.ncbi.nlm.nih.gov/pubmed/31400199)|[10.1093/molbev/msz184 ](https://doi.org/10.1093/molbev/msz184 )|Faber|2019|DMS|AmiE|||||||
|[30894475](https://www.ncbi.nlm.nih.gov/pubmed/30894475)|[10.1128/JVI.00219-19 ](https://doi.org/10.1128/JVI.00219-19 )|Heredia|2019|DMS|Env|||||||
|[31019050](https://www.ncbi.nlm.nih.gov/pubmed/31019050)|[10.1128/JVI.00161-19 ](https://doi.org/10.1128/JVI.00161-19 )|Hom|2019|DMS|matrix protein|||||||
|[31038123](https://www.ncbi.nlm.nih.gov/pubmed/31038123)|[10.7554/eLife.45079 ](https://doi.org/10.7554/eLife.45079 )|Soh|2019|DMS|PB2|||||||
|[31808666](https://www.ncbi.nlm.nih.gov/pubmed/31808666)|[10.1021/acschembio.9b00669 ](https://doi.org/10.1021/acschembio.9b00669 )|Zinkus-Boltz|2019|DMS|RAF|||||||
|[31511387](https://www.ncbi.nlm.nih.gov/pubmed/31511387)|[10.1128/JVI.01291-19 ](https://doi.org/10.1128/JVI.01291-19 )|Sourisseau|2019|DMS|Zika envelope|||||||
|[30761651](https://www.ncbi.nlm.nih.gov/pubmed/30761651)|[10.1002/jmr.2778 ](https://doi.org/10.1002/jmr.2778 )|Wollacott|2019|DMS|Proliferation-inducing ligand|||||||
|[32510322](https://www.ncbi.nlm.nih.gov/pubmed/32510322)|[10.7554/eLife.56707 ](https://doi.org/10.7554/eLife.56707 )|Chen|2020|DMS|VIM-2 lactamase|||||||
|[28579254](https://www.ncbi.nlm.nih.gov/pubmed/28579254)|[10.1016/j.chom.2017.05.003 ](https://doi.org/10.1016/j.chom.2017.05.003 )|Dingens|2017|DMS|Env|||||||
|[31325330](https://www.ncbi.nlm.nih.gov/pubmed/31325330)|[10.1002/prot.25786 ](https://doi.org/10.1002/prot.25786 )|Warszawski|2020|DMS|basigin|||||||
|[29466705](https://www.ncbi.nlm.nih.gov/pubmed/29466705)|[10.1016/j.jmb.2018.02.009 ](https://doi.org/10.1016/j.jmb.2018.02.009 )|Canale|2018|DMS|HA|||||||
|[24887409](https://www.ncbi.nlm.nih.gov/pubmed/24887409)|[10.1371/journal.pone.0097817 ](https://doi.org/10.1371/journal.pone.0097817 )|Shin|2014|DMS|flavin mononucleotide binding fluorescent protein |||||||
|[30709739](https://www.ncbi.nlm.nih.gov/pubmed/30709739)|[10.1016/j.immuni.2018.12.017 ](https://doi.org/10.1016/j.immuni.2018.12.017 )|Dingens|2019|DMS|Env|||||||
|[29912470](https://www.ncbi.nlm.nih.gov/pubmed/29912470)|[10.1093/nar/gky255 ](https://doi.org/10.1093/nar/gky255 )|Atkinson|2018|DMS|adenylate kinase|||||||
|[29663315](https://www.ncbi.nlm.nih.gov/pubmed/29663315)|[10.1002/bit.26706 ](https://doi.org/10.1002/bit.26706 )|Medina-Cucurella|2018|DMS|canine nerve growth factor|||||||
|[31081325](https://www.ncbi.nlm.nih.gov/pubmed/31081325)|[10.1021/acssynbio.9b00104 ](https://doi.org/10.1021/acssynbio.9b00104 )|Nikoomanzar|2019|DMS|Kod DNA polymerase|||||||
|[29979580](https://www.ncbi.nlm.nih.gov/pubmed/29979580)|[10.1021/acssynbio.8b00121 ](https://doi.org/10.1021/acssynbio.8b00121 )|Scott|2018|DMS|tetracycline inactivating enzyme|||||||
|[30886357](https://www.ncbi.nlm.nih.gov/pubmed/30886357)|[10.1038/s41564-019-0399-4 ](https://doi.org/10.1038/s41564-019-0399-4 )|Setoh|2019|DMS|Zika envelope|||||||
|[31242389](https://www.ncbi.nlm.nih.gov/pubmed/31242389)|[10.1021/acs.molpharmaceut.9b00418 ](https://doi.org/10.1021/acs.molpharmaceut.9b00418 )|Klesmith|2019|DMS|CD19|||||||
|||||||||||||
