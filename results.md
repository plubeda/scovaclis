#
To perform the experiments, we used 75% of the case reports for training 475 (41,159 documents) and the rest for blind testing (13,720 documents). You must consider that it is a multi-label classification, so each document can belong to more than one specialty.

## Classifier:  MULTILAYER PERCEPTRON
## Word Representation: TFIDF

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 31.7 | 8.5 | 13.4 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 34.6 | 25.3 | 29.2 | 178 |
| Bariatric medicine | 83.3 | 26.3 | 40.0 | 19 |
| Dermatology | 86.9 | 68.7 | 76.7 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 87.9 | 28.4 | 43.0 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 78.6 | 65.6 | 71.5 | 1101 |
| Geriatrics | 48.9 | 38.4 | 43.0 | 3223 |
| Cardiology | 88.7 | 76.6 | 82.2 | 2817 |
| Endocrinology | 88.2 | 66.4 | 75.8 | 1268 |
| Gastroenterology | 86.7 | 75.7 | 80.8 | 1764 |
| Hematology | 88.6 | 64.0 | 74.3 | 1109 |
| Infectious disease medicine | 11.1 | 1.5 | 2.6 | 68 |
| Medical oncology | 91.5 | 80.9 | 85.8 | 4035 |
| Nephrology | 84.0 | 71.6 | 77.3 | 953 |
| Pulmonary medicine | 15.4 | 3.2 | 5.3 | 125 |
| Rheumatology | 83.7 | 47.5 | 60.6 | 238 |
| Internal medicine | 24.4 | 9.0 | 13.2 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 89.4 | 74.3 | 81.1 | 3156 |
| Palliative medicine | 100.0 | 4.2 | 8.0 | 24 |
| Pathology | 55.2 | 45.6 | 49.9 | 3836 |
| Neonatology | 66.1 | 47.0 | 54.9 | 534 |
| Perinatology | 79.1 | 57.6 | 66.7 | 538 |
| Pediatrics | 27.4 | 13.2 | 17.8 | 431 |
| Rehabilitation | 50.0 | 9.4 | 15.8 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 33.3 | 3.0 | 5.6 | 33 |
| Psychiatry | 33.3 | 8.1 | 13.0 | 37 |
| Epidemiology | 38.5 | 13.8 | 20.3 | 253 |
| Preventive medicine | 38.4 | 21.5 | 27.6 | 1824 |
| Nuclear medicine | 75.0 | 42.3 | 54.1 | 142 |
| Radiology | 49.3 | 17.5 | 25.8 | 200 |
| Gynecology | 70.6 | 44.6 | 54.7 | 399 |
| Reproductive medicine | 75.0 | 14.3 | 24.0 | 21 |
| General surgery | 63.2 | 41.2 | 49.9 | 2547 |
| Neurosurgery | 42.0 | 16.2 | 23.4 | 228 |
| Obstetrics | 87.1 | 59.1 | 70.5 | 470 |
| Ophthalmology | 88.8 | 56.6 | 69.1 | 673 |
| Orthopedics | 52.3 | 17.2 | 25.8 | 134 |
| Otolaryngology | 81.2 | 51.1 | 62.7 | 573 |
| Surgery plastic | 53.8 | 16.1 | 24.8 | 87 |
| Thoracic surgery | 67.4 | 37.1 | 47.9 | 407 |
| Traumatology | 76.8 | 53.2 | 62.8 | 814 |
| Urology | 86.8 | 74.1 | 79.9 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 90.9 | 34.5 | 50.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 75.1 | 56.3 | 64.3 | 39293 |
| macro avg | 56.3 | 33.4 | 40.0 | 39293 |
| weighted avg | 72.6 | 56.3 | 62.9 | 39293 |

## Classifier:  DECISION TREE
## Word Representation: TFIDF

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 6.6 | 3.6 | 4.6 | 224 |
| Allergy and immunology | 16.7 | 14.3 | 15.4 | 7 |
| Anesthesiology | 15.0 | 6.7 | 9.3 | 178 |
| Bariatric medicine | 0.0 | 0.0 | 0.0 | 19 |
| Dermatology | 48.9 | 37.7 | 42.6 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 28.8 | 16.7 | 21.1 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 37.3 | 38.5 | 37.9 | 1101 |
| Geriatrics | 32.5 | 27.4 | 29.7 | 3223 |
| Cardiology | 63.9 | 51.0 | 56.7 | 2817 |
| Endocrinology | 62.2 | 40.9 | 49.4 | 1268 |
| Gastroenterology | 59.8 | 49.2 | 54.0 | 1764 |
| Hematology | 49.6 | 37.1 | 42.4 | 1109 |
| Infectious disease medicine | 10.0 | 2.9 | 4.5 | 68 |
| Medical oncology | 70.0 | 66.6 | 68.3 | 4035 |
| Nephrology | 71.6 | 57.4 | 63.7 | 953 |
| Pulmonary medicine | 6.1 | 4.8 | 5.4 | 125 |
| Rheumatology | 44.4 | 28.2 | 34.4 | 238 |
| Internal medicine | 10.9 | 6.2 | 7.9 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 53.3 | 48.8 | 51.0 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 39.3 | 38.7 | 39.0 | 3836 |
| Neonatology | 46.5 | 30.1 | 36.6 | 534 |
| Perinatology | 53.8 | 35.3 | 42.6 | 538 |
| Pediatrics | 10.2 | 7.2 | 8.4 | 431 |
| Rehabilitation | 3.8 | 3.1 | 3.4 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 0.0 | 0.0 | 0.0 | 37 |
| Epidemiology | 11.5 | 5.5 | 7.5 | 253 |
| Preventive medicine | 19.9 | 12.7 | 15.5 | 1824 |
| Nuclear medicine | 15.9 | 9.9 | 12.2 | 142 |
| Radiology | 6.0 | 5.5 | 5.8 | 200 |
| Gynecology | 35.5 | 22.3 | 27.4 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 36.4 | 23.8 | 28.8 | 2547 |
| Neurosurgery | 17.9 | 7.5 | 10.5 | 228 |
| Obstetrics | 55.7 | 33.4 | 41.8 | 470 |
| Ophthalmology | 41.6 | 28.5 | 33.8 | 673 |
| Orthopedics | 14.3 | 7.5 | 9.8 | 134 |
| Otolaryngology | 34.2 | 26.5 | 29.9 | 573 |
| Surgery plastic | 9.1 | 2.3 | 3.7 | 87 |
| Thoracic surgery | 32.4 | 16.2 | 21.6 | 407 |
| Traumatology | 36.0 | 21.3 | 26.7 | 814 |
| Urology | 66.7 | 57.1 | 61.5 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 85.7 | 20.7 | 33.3 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 47.9 | 38.1 | 42.4 | 39293 |
| macro avg | 28.1 | 19.7 | 22.7 | 39293 |
| weighted avg | 46.5 | 38.1 | 41.6 | 39293 |

## Classifier:  RANDOM FOREST
## Word Representation: TFIDF

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 0.0 | 0.0 | 0.0 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 100.0 | 0.6 | 1.1 | 178 |
| Bariatric medicine | 0.0 | 0.0 | 0.0 | 19 |
| Dermatology | 88.0 | 25.3 | 39.3 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 87.5 | 13.7 | 23.7 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 88.4 | 19.4 | 31.9 | 1101 |
| Geriatrics | 49.8 | 10.1 | 16.8 | 3223 |
| Cardiology | 93.7 | 37.8 | 53.8 | 2817 |
| Endocrinology | 96.4 | 25.2 | 40.0 | 1268 |
| Gastroenterology | 93.9 | 37.0 | 53.1 | 1764 |
| Hematology | 94.4 | 22.6 | 36.5 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 87.5 | 57.9 | 69.7 | 4035 |
| Nephrology | 87.6 | 37.1 | 52.2 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 93.7 | 24.8 | 39.2 | 238 |
| Internal medicine | 25.0 | 0.9 | 1.8 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 90.2 | 34.5 | 49.9 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 54.0 | 24.1 | 33.3 | 3836 |
| Neonatology | 90.1 | 17.0 | 28.7 | 534 |
| Perinatology | 93.4 | 21.0 | 34.3 | 538 |
| Pediatrics | 35.7 | 1.2 | 2.2 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 0.0 | 0.0 | 0.0 | 37 |
| Epidemiology | 37.5 | 1.2 | 2.3 | 253 |
| Preventive medicine | 43.8 | 2.1 | 4.1 | 1824 |
| Nuclear medicine | 31.2 | 3.5 | 6.3 | 142 |
| Radiology | 77.8 | 3.5 | 6.7 | 200 |
| Gynecology | 94.1 | 8.0 | 14.8 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 69.5 | 10.6 | 18.3 | 2547 |
| Neurosurgery | 33.3 | 0.4 | 0.9 | 228 |
| Obstetrics | 94.3 | 21.3 | 34.7 | 470 |
| Ophthalmology | 97.6 | 12.0 | 21.4 | 673 |
| Orthopedics | 0.0 | 0.0 | 0.0 | 134 |
| Otolaryngology | 91.2 | 12.7 | 22.4 | 573 |
| Surgery plastic | 0.0 | 0.0 | 0.0 | 87 |
| Thoracic surgery | 85.7 | 1.5 | 2.9 | 407 |
| Traumatology | 90.4 | 10.4 | 18.7 | 814 |
| Urology | 91.9 | 40.3 | 56.1 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 0.0 | 0.0 | 0.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 81.7 | 25.1 | 38.4 | 39293 |
| macro avg | 48.5 | 11.4 | 17.1 | 39293 |
| weighted avg | 75.7 | 25.1 | 35.7 | 39293 |

## Classifier:  KNEIGHBORS
## Word Representation: TFIDF

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 25.0 | 0.4 | 0.9 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 53.3 | 4.5 | 8.3 | 178 |
| Bariatric medicine | 100.0 | 5.3 | 10.0 | 19 |
| Dermatology | 86.3 | 36.6 | 51.4 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 100.0 | 20.6 | 34.1 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 86.4 | 37.5 | 52.3 | 1101 |
| Geriatrics | 50.9 | 18.2 | 26.8 | 3223 |
| Cardiology | 87.7 | 46.4 | 60.7 | 2817 |
| Endocrinology | 89.8 | 36.0 | 51.4 | 1268 |
| Gastroenterology | 87.1 | 40.6 | 55.4 | 1764 |
| Hematology | 92.2 | 34.3 | 50.0 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 63.8 | 74.7 | 68.8 | 4035 |
| Nephrology | 87.9 | 36.6 | 51.7 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 96.3 | 32.4 | 48.4 | 238 |
| Internal medicine | 19.6 | 1.6 | 2.9 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 66.5 | 62.6 | 64.5 | 3156 |
| Palliative medicine | 100.0 | 4.2 | 8.0 | 24 |
| Pathology | 42.3 | 54.5 | 47.6 | 3836 |
| Neonatology | 81.7 | 19.3 | 31.2 | 534 |
| Perinatology | 86.5 | 24.9 | 38.7 | 538 |
| Pediatrics | 60.0 | 1.4 | 2.7 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 0.0 | 0.0 | 0.0 | 37 |
| Epidemiology | 60.0 | 1.2 | 2.3 | 253 |
| Preventive medicine | 48.8 | 4.4 | 8.1 | 1824 |
| Nuclear medicine | 46.3 | 26.8 | 33.9 | 142 |
| Radiology | 43.5 | 10.0 | 16.3 | 200 |
| Gynecology | 81.3 | 18.5 | 30.2 | 399 |
| Reproductive medicine | 75.0 | 14.3 | 24.0 | 21 |
| General surgery | 43.1 | 34.0 | 38.0 | 2547 |
| Neurosurgery | 61.5 | 3.5 | 6.6 | 228 |
| Obstetrics | 84.9 | 25.1 | 38.8 | 470 |
| Ophthalmology | 91.8 | 23.3 | 37.2 | 673 |
| Orthopedics | 75.0 | 2.2 | 4.3 | 134 |
| Otolaryngology | 80.2 | 27.6 | 41.0 | 573 |
| Surgery plastic | 0.0 | 0.0 | 0.0 | 87 |
| Thoracic surgery | 73.8 | 11.1 | 19.2 | 407 |
| Traumatology | 82.1 | 21.4 | 33.9 | 814 |
| Urology | 64.3 | 62.0 | 63.1 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 85.7 | 20.7 | 33.3 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 63.3 | 39.0 | 48.2 | 39293 |
| macro avg | 53.8 | 18.5 | 24.6 | 39293 |
| weighted avg | 66.3 | 39.0 | 45.0 | 39293 |

