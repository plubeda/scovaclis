# Spanish Core Vocabulary About Clinical Specialties

This project is structured as follows:

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
- included_snomed:
 
 
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

#### 7. ICD-analysis-terms file
Basic analysis of SCOVACLIS using ICD-10

