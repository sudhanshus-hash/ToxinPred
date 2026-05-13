# ToxinPred: In Silico Approach for Predicting Toxicity of Peptides and Proteins

ToxinPred is a computational tool developed to predict, design, and scan toxic peptides and proteins. The server helps identify whether a peptide is toxic or non-toxic, supports the design of peptide analogues with reduced or enhanced toxicity, and allows scanning of protein sequences to detect toxic regions.

This resource is useful for peptide/protein-based drug discovery because toxicity is one of the major limitations in developing therapeutic peptides and proteins.

Web Server: (https://webs.iiitd.edu.in/raghava/toxinpred/)



## Citation

Gupta, S., Kapoor, P., Chaudhary, K., Gautam, A., Kumar, R., Open Source Drug Discovery Consortium, and Raghava, G. P. S. In Silico Approach for Predicting Toxicity of Peptides and Proteins. PLOS ONE, 8(9), e73957, 2013.

https://doi.org/10.1371/journal.pone.0073957

This tool and dataset is also available on Zenodo at https://doi.org/10.5281/zenodo.20151860


## About the Research

Peptide and protein-based therapeutics have gained major importance because of their high specificity, biological activity, lower production cost, and better penetration compared to many small molecules. However, toxicity, immunogenicity, and stability remain major concerns in peptide-based drug development.

ToxinPred was developed to predict the toxicity of peptides and proteins before experimental synthesis, helping researchers save time and cost during therapeutic peptide design.

Data Compilation: Toxic peptides of 35 or fewer residues were collected from multiple toxin-related databases, including ATDB, DBETH, BTXpred, NTXpred, ArachnoServer, ConoServer, and Swiss-Prot. Non-toxic peptides were obtained from Swiss-Prot and TrEMBL.

Methodology: ToxinPred uses machine learning-based models, mainly Support Vector Machine models, trained on peptide sequence features such as amino acid composition, dipeptide composition, binary profile patterns, toxic motifs, and quantitative matrices.



## Key Features

### 1. High-Performance Toxicity Prediction

Predictive Modeling: Allows users to submit peptide sequences and predict whether they are likely to be toxic or non-toxic.

Accuracy: The dipeptide composition-based model achieved 94.50% accuracy with MCC 0.88 and AUC 0.98 on the main dataset.

Hybrid Model: A hybrid model combining motif information with dipeptide composition achieved 98.41% accuracy with MCC 0.96 and AUC 0.99.



### 2. Scanning and Design Modules

Peptide Designing: The design module generates all possible single-mutant analogues of a submitted peptide and predicts whether each mutant is toxic or non-toxic.

Protein Scanning: Users can submit full-length protein sequences to identify potentially toxic regions using overlapping peptide scanning.

Batch Submission: Users can submit multiple peptide sequences together for virtual screening and toxicity prediction.



### 3. Integrated Web-Bench

Motif Scanning: The server allows users to scan peptide or protein sequences for toxic motifs identified from known toxic peptides.

QMS Calculator: The Quantitative Matrix Score calculator helps users optimize peptides for desired toxicity by identifying residues that may increase or decrease toxicity.

Physicochemical Analysis: ToxinPred also provides useful peptide property information to help users compare and select peptide analogues.



## Applications

Therapeutic Peptide Design: ToxinPred can help researchers design peptide-based drugs with reduced toxicity.

Protein Toxicity Analysis: The tool can identify toxic regions within larger protein sequences.

Drug Discovery: ToxinPred supports virtual screening of peptides before experimental validation.

Peptide Optimization: The design and QMS modules can help modify peptide sequences to increase or decrease toxicity depending on the research goal.

Toxin Biology: The tool can assist in studying sequence patterns, motifs, and residue preferences associated with toxic peptides.



## Contact and Authors

Prof. Gajendra P. S. Raghava  
Corresponding Author  

Email: raghava@imtech.res.in  

Bioinformatics Centre  
CSIR-Institute of Microbial Technology  
Chandigarh, India  



## Support

ToxinPred was developed with financial support from the Council of Scientific and Industrial Research, Government of India.
