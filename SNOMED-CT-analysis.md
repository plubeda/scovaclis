### Analysis of SCOVACLIST terms using SNOMED-CT

We analyze the characteristics of the terms that were not found in SNOMED-CT to recognize possible noise terms in our vocabulary. The detailed results are 
presented below and show that many of the SCOVACLIS terms with high value on the Et  measure are found in 
SNOMED-CT. A high Et means that the term was found in several specialties. 90% of the terms found between 38 and 52 specialties are included in SNOMED-CT. 
On the contrary, only 15% of the terms found between 1 and 13 specialties are included in SNOMED-CT. This corroborates that SNOMED-CT is a resource that, 
in Spanish, emphasizes covering the terms that are generally used in the field, but does often lack coverage of very specific concepts of a specialty and 
their synonyms. This seems interesting, because SCOVACLIS could be used for adding more content when an NLP task requires these specific and complementary 
terms. The manual analysis of the terms yields that some of the not found terms are related terms to formal ones (e.g. *filled breast* instead of 
*breast implant* in *Surgery plastic*), and  others are more specialized than the contained in SNOMED-CT (e.g. *toracoabdominal wall* in *Thoracic Specialty* 
and  *kayakista* in *Sports Medicine*). Lastly, we found that specialties with a broad lexical nature, such as preventive medicine 
and general practice, include apparently not-so-relevant terms. However, they are useful for improving classification performance, as illustrated in the 
classification experiment in the paper.


Hematology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.27%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.2%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 73.43%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.2%

Cardiology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 12.87%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 54.38%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.67%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

General practice

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.01%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 60.91%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 80.51%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 94.26%

Rehabilitation

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 17.04%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 59.03%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 77.98%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.25%

Ophthalmology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 18.6%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 59.54%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.24%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.09%

Pathology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 17.09%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 58.2%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.98%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

Bariatric medicine

	Percentile [ 0 - 25 ] (Et >= 2.0 and < 14.25 ) -> 12.26%

	Percentile [ 25 - 50 ] (Et >= 14.25 and < 26.5 ) -> 54.17%

	Percentile [ 50 - 75 ] (Et >= 26.5 and < 38.75 ) -> 74.04%

	Percentile [ 75 - 100 ] (Et >= 38.75 and < 52.0 ) -> 89.19%

Thoracic surgery

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.31%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 57.11%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 73.76%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.01%

Neurosurgery

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.53%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 57.46%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.95%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.08%

Community psychiatry

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 11.8%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 56.59%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 77.63%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

Anesthesiology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.69%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 62.41%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 79.47%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 89.72%

Orthopedics

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 19.4%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.93%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 73.62%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 88.83%

Gynecology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.0%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 54.85%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.81%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.09%

Military medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 10.27%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 58.72%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 79.25%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 94.05%

Preventive medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 11.18%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.77%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.7%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

Family practice

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 10.89%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 54.97%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 77.09%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.6%

Epidemiology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.03%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.92%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.84%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.11%

General surgery

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.37%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 56.56%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.76%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

Rheumatology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.29%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.54%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 73.35%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 89.72%

Internal medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.11%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 57.33%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.82%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.13%

Neonatology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.83%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 58.02%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.98%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.06%

Genetics medical

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 18.24%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 57.99%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.42%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.11%

Urology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.15%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.33%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.14%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.1%

Nephrology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.37%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.49%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.41%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.01%

Surgery plastic

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 21.57%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 63.53%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.47%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.15%

Reproductive medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.48%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 58.31%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.26%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.56%

Gastroenterology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.11%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 53.08%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 73.97%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.1%

Perinatology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.01%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 58.2%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 76.0%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.16%

Specialties surgical

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.4%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 52.46%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 77.12%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.91%

Radiology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 19.33%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 65.05%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 78.0%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.05%

Palliative medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.62%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 60.34%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.98%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 92.03%

Traumatology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 18.19%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 58.49%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.1%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.22%

Venereology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 12.99%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 52.86%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.2%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.18%

Geriatrics

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.31%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 56.91%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.04%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.1%

Physical and rehabilitation medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 18.86%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 72.38%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 84.31%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.94%

Infectious disease medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.37%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 57.25%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 76.59%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.23%

Tropical medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.85%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 61.1%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 80.4%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 91.18%

Pulmonary medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.81%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.85%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.46%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.65%

Dermatology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 17.63%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 56.68%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.11%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.11%

Otolaryngology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.58%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 56.03%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.34%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.23%

Nuclear medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.97%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 63.17%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 81.69%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 91.19%

Forensic medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 12.8%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 53.94%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 81.06%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 93.65%

Pediatrics

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 16.62%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 59.32%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 76.2%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.17%

Immunochemistry

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 15.39%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 59.02%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.74%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.29%

Neurology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 14.78%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.68%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.6%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

Psychiatry

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.65%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 54.6%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.25%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 89.75%

Allergy and immunology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 19.15%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 55.99%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 78.45%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 89.32%

Endocrinology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.82%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 54.11%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 73.52%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.07%

Obstetrics

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.67%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 57.51%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 75.79%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.34%

Medical oncology

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 13.55%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 54.58%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 74.53%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 90.12%

Sports medicine

	Percentile [ 0 - 25 ] (Et >= 1.0 and < 13.5 ) -> 20.1%

	Percentile [ 25 - 50 ] (Et >= 13.5 and < 26.0 ) -> 69.84%

	Percentile [ 50 - 75 ] (Et >= 26.0 and < 38.5 ) -> 84.81%

	Percentile [ 75 - 100 ] (Et >= 38.5 and < 52.0 ) -> 92.51%

