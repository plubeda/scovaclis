# SCOVACLIS (Spanish Core Vocabulary About Clinical Specialties)

### Background
Controlled vocabularies are fundamental resources for information extraction from clinical texts using natural language processing (NLP). Standard language resources available in the healthcare domain such as the UMLS metathesaurus or SNOMED CT are widely used for this purpose, but with limitations such as lexical ambiguity of clinical terms. However, most of them are unambiguous within text limited to a given clinical specialty. This is one rationale besides others to classify clinical text by the clinical specialty to which they belong.

### Results
This paper addresses this limitation by proposing and applying a method that automatically extracts Spanish medical terms classified and weighted per sub-domain, using Spanish MEDLINE titles and abstracts as input. The hypothesis is biomedical NLP tasks benefit from collections of domain terms that are specific to clinical subdomains. We use PubMed queries that generate sub-domain specific corpora from Spanish titles and abstracts, from which token n-grams are collected and metrics of relevance, discriminatory power, and broadness per sub-domain are computed. The generated term set, called Spanish core vocabulary about clinical specialties (SCOVACLIS), was made available to the scientific community and used in a text classification problem obtaining improvements of 6 percentage points in the F-measure compared to the baseline using Multilayer Perceptron, thus demonstrating the hypothesis that a specialized term set improves NLP tasks.

###  Conclusion
The creation and validation of SCOVACLIS support the hypothesis that specific term sets reduce the level of ambiguity when compared to a specialty-independent and broad-scope vocabulary.

## GitHub Structure
#### 1. Terminology folder:

Folder containing a file for each medical specialty.

These files contain the terms chosen for a specific medical specialty and their metrics.

Example of specialty geriatrics:

| # | Term| Ndeᵗᵢ| Ndeᶜᵗ| Ndᶜᵗeᵗᵢ| Eᵗ| LPM| TGM| LRM| included_snomed |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ruido cardíaco normal | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | True |
| 2 | corazón humano | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | False |
| 3 | solución polarizante | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | False |
| 4 | localización inferior | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | False |
| 5 | caso de pericarditis | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | False |
| 6 | caso de coartación | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | False |
| 7 | hipertensión arterial producida | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | False |
| 8 | curva de presión | 3 | 0 | 27313 | 1 | 1.0001098 | 1.0 | 1.0001098 | True |


- Ndeᵗᵢ: Number of documents in the specialty that have the term t.
- Ndeᶜᵗ: Number of documents in the OTHER specialities that have t.
- Ndᶜᵗeᵗᵢ: Number of documents in the specialty that do NOT have t.
- Eᵗ: The number of specialties that contain the termt t.
- Local Precision Measure (LPM): a specialty-level measure that represents the capacity of a term to specifically characterise the specialty. Terms with high values in text of a given specialty are those that never or rarely occur in texts belonging to other specialties.
- Term Global Measure (TGM): a corpus measure that quantifies the concentration of a term along all specialties.
- Local Relevance Measure (LRM): It represents the capacity of a term to describe the specialty. Terms with high values are those with high frequency in the specialty, compared to other terms in the specialty, and compared to the frequency in other specialties.  
- included_snomed: True = the term is found in SNOMED-CT, False = the term is not found in SNOMED-CT
 
 
#### 2. Binary-confusion-matrix file:
Binary confusion matrix for each speciality.

#### 3. Detailed-classifiers file
Implementation details and parameters of the systems used

#### 4. Detailed-results file
Detailed results

#### 5. Distribution-of-labels file
Distribution of labels in training and testing.

#### 6. Example-filters-pubmed file
Examples of queries and filtering in Pubmed.

# Authors
- Pilar López-Úbeda
Universidad de Jaén, Campus Las Lagunillas, s/n, 23071, Jaén, Spain
plubeda@ujaen.es

- Alexandra Pomares-Quimbaya
Pontificia Universidad Javeriana, Cra. 7 No 40-62, Bogotá, 110231, Colombia

- Manuel Carlos Díaz-Galiano
Universidad de Jaén, Campus Las Lagunillas, s/n, 23071, Jaén, Spain

- Stefan Schulz 
Medical University of Graz, Auenbruggerpl No 2, 8036, Graz, Austria


# Citing

If you use SCOVACLIS in your research, please cite: [Collecting specialty-related medical terms: Development and evaluation of a resource for Spanish] (https://link.springer.com/article/10.1186/s12911-021-01495-w).
```
@article{lopez2021collecting,
  title={Collecting specialty-related medical terms: Development and evaluation of a resource for Spanish},
  author={L{\'o}pez-{\'U}beda, Pilar and Pomares-Quimbaya, Alexandra and D{\'\i}az-Galiano, Manuel Carlos and Schulz, Stefan},
  journal={BMC Medical Informatics and Decision Making},
  volume={21},
  number={1},
  pages={1--17},
  year={2021},
  publisher={Springer}
}
```
#### 7. ICD-analysis-terms file
Basic analysis of SCOVACLIS using ICD-10

