# microBioRust

##What does microBioRust aim to do?
This is a Rust crate package aimed at microbiology and optimised for functions that are much more common and needed in microbial bioinformatics research.

##What will not be covered by microBioRust?
Workflows and pipelines for end-to-end bioinformatics solutions - microBioRust is a set of tools.

###Why would microbes have different requirements for bioinformatics, genetics and genomics studies?
Bacteria are arguably the best studied microbes, their DNA and genes are quite different to ours. a microbiology specific parser would be optimised to handle features in these genomes.  the genomes are far shorter and many thousands of them are sequenced, meaning processing thousands of small text files is a requirement.  we have quite a bit of functional information for the genes and many thousands of genomes are available and stored in alternative formats which all need parsing.  this is where Rust can really shine compared to existing tools in other languages.  we do not want to duplicate where tools already exist, e.g. fasta parsing in rust-bio.

##Why call it microBioRust?
The reason is to bridge across fields.  other languages are out there such as biopython, biojulia, bioC++, bioruby, biojava, bioperl, bioconductor [R programming language] - contains many different libraries.

##What is Microbiology?
Microbiology is the study of microscopic organisms, also known as microbes.  they are usually too small to see.
The idea behind this field of biology is an old one, back from when these small organisms were not understood and were all thought to be related based on their size.
Microbes can include Viruses, Bacteria, Archaea (like Bacteria but distinct, often live in extreme environments), and small Eukaryotes such as yeasts and fungi.
other microbes include several things you may not have heard that much about, like slime molds, phage, prions, algae and protists.

Insects are **ot** microbes, however, some definitions of microbiology would include the honey mushroom of Oregon, *Armillaria osytoyae* described as the largest/second largest organism on earth!

##What training do I have?
I have come over from python and R - self taught.  It would be good to have some help

##what about pyo3 to create python-available functionality?
I am definitely considering this

