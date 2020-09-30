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
## Classifier:  MULTILAYER PERCEPTRON
### Word Representation: TFIDF

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
### Word Representation: TFIDF

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
### Word Representation: TFIDF

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
### Word Representation: TFIDF

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

## Classifier:  DECISION TREE
### Word Representation: TFIDF + SCOVACLIS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 4.7 | 3.6 | 4.1 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 12.8 | 10.1 | 11.3 | 178 |
| Bariatric medicine | 4.0 | 5.3 | 4.5 | 19 |
| Dermatology | 54.5 | 54.3 | 54.4 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 16.9 | 9.8 | 12.4 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 51.6 | 47.9 | 49.7 | 1101 |
| Geriatrics | 30.7 | 29.7 | 30.2 | 3223 |
| Cardiology | 62.1 | 62.2 | 62.1 | 2817 |
| Endocrinology | 50.8 | 48.4 | 49.6 | 1268 |
| Gastroenterology | 60.7 | 57.7 | 59.1 | 1764 |
| Hematology | 49.8 | 48.4 | 49.1 | 1109 |
| Infectious disease medicine | 4.8 | 2.9 | 3.6 | 68 |
| Medical oncology | 69.4 | 69.1 | 69.3 | 4035 |
| Nephrology | 60.9 | 57.3 | 59.1 | 953 |
| Pulmonary medicine | 2.6 | 1.6 | 2.0 | 125 |
| Rheumatology | 29.2 | 23.5 | 26.0 | 238 |
| Internal medicine | 7.8 | 6.4 | 7.0 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 63.4 | 60.4 | 61.9 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 37.9 | 38.1 | 38.0 | 3836 |
| Neonatology | 23.9 | 20.8 | 22.2 | 534 |
| Perinatology | 43.0 | 39.4 | 41.1 | 538 |
| Pediatrics | 9.0 | 7.9 | 8.4 | 431 |
| Rehabilitation | 4.2 | 3.1 | 3.6 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 10.2 | 13.5 | 11.6 | 37 |
| Epidemiology | 5.3 | 3.6 | 4.2 | 253 |
| Preventive medicine | 16.0 | 12.6 | 14.1 | 1824 |
| Nuclear medicine | 17.2 | 14.1 | 15.5 | 142 |
| Radiology | 1.1 | 1.0 | 1.0 | 200 |
| Gynecology | 31.3 | 29.6 | 30.4 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 34.9 | 32.9 | 33.8 | 2547 |
| Neurosurgery | 6.8 | 5.7 | 6.2 | 228 |
| Obstetrics | 46.1 | 39.8 | 42.7 | 470 |
| Ophthalmology | 45.8 | 40.1 | 42.8 | 673 |
| Orthopedics | 14.9 | 11.2 | 12.8 | 134 |
| Otolaryngology | 38.9 | 38.7 | 38.8 | 573 |
| Surgery plastic | 2.0 | 1.1 | 1.5 | 87 |
| Thoracic surgery | 23.2 | 21.1 | 22.1 | 407 |
| Traumatology | 34.7 | 32.3 | 33.5 | 814 |
| Urology | 65.2 | 62.3 | 63.7 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 0.0 | 0.0 | 0.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 46.2 | 43.5 | 44.8 | 39293 |
| macro avg | 23.4 | 21.7 | 22.5 | 39293 |
| weighted avg | 45.3 | 43.5 | 44.3 | 39293 |
| Immunochemistry | 0.0 | 0.0 | 0.0 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 0.0 | 0.0 | 0.0 | 178 |
| Bariatric medicine | 0.0 | 0.0 | 0.0 | 19 |
| Dermatology | 84.0 | 13.3 | 23.0 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 90.9 | 9.8 | 17.7 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 77.4 | 10.3 | 18.1 | 1101 |
| Geriatrics | 45.5 | 6.7 | 11.7 | 3223 |
| Cardiology | 88.4 | 28.8 | 43.5 | 2817 |
| Endocrinology | 93.7 | 8.2 | 15.1 | 1268 |
| Gastroenterology | 92.1 | 23.0 | 36.8 | 1764 |
| Hematology | 89.4 | 8.4 | 15.3 | 1109 |
| Infectious disease medicine | 33.3 | 1.5 | 2.8 | 68 |
| Medical oncology | 87.8 | 47.9 | 62.0 | 4035 |
| Nephrology | 90.6 | 22.1 | 35.6 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 96.8 | 12.6 | 22.3 | 238 |
| Internal medicine | 30.0 | 0.5 | 0.9 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 88.0 | 30.0 | 44.8 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 52.6 | 16.6 | 25.3 | 3836 |
| Neonatology | 92.0 | 8.6 | 15.8 | 534 |
| Perinatology | 90.5 | 12.5 | 21.9 | 538 |
| Pediatrics | 12.5 | 0.2 | 0.5 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 0.0 | 0.0 | 0.0 | 37 |
| Epidemiology | 0.0 | 0.0 | 0.0 | 253 |
| Preventive medicine | 41.5 | 0.9 | 1.8 | 1824 |
| Nuclear medicine | 33.3 | 0.7 | 1.4 | 142 |
| Radiology | 25.0 | 0.5 | 1.0 | 200 |
| Gynecology | 75.0 | 1.5 | 2.9 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 69.3 | 7.2 | 13.0 | 2547 |
| Neurosurgery | 0.0 | 0.0 | 0.0 | 228 |
| Obstetrics | 93.8 | 12.8 | 22.5 | 470 |
| Ophthalmology | 95.0 | 5.6 | 10.7 | 673 |
| Orthopedics | 0.0 | 0.0 | 0.0 | 134 |
| Otolaryngology | 86.5 | 5.6 | 10.5 | 573 |
| Surgery plastic | 0.0 | 0.0 | 0.0 | 87 |
| Thoracic surgery | 40.0 | 0.5 | 1.0 | 407 |
| Traumatology | 87.0 | 7.4 | 13.6 | 814 |
| Urology | 92.6 | 26.9 | 41.7 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 0.0 | 0.0 | 0.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 80.0 | 17.5 | 28.7 | 39293 |
| macro avg | 42.4 | 7.1 | 11.4 | 39293 |
| weighted avg | 71.8 | 17.5 | 26.4 | 39293 |
| Immunochemistry | 33.3 | 1.3 | 2.6 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 34.6 | 5.1 | 8.8 | 178 |
| Bariatric medicine | 75.0 | 15.8 | 26.1 | 19 |
| Dermatology | 83.4 | 46.3 | 59.6 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 89.7 | 25.5 | 39.7 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 81.5 | 45.3 | 58.3 | 1101 |
| Geriatrics | 44.1 | 21.1 | 28.5 | 3223 |
| Cardiology | 86.0 | 59.9 | 70.6 | 2817 |
| Endocrinology | 86.1 | 40.6 | 55.2 | 1268 |
| Gastroenterology | 86.0 | 55.8 | 67.7 | 1764 |
| Hematology | 86.6 | 42.4 | 56.9 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 72.8 | 74.9 | 73.8 | 4035 |
| Nephrology | 86.4 | 51.2 | 64.3 | 953 |
| Pulmonary medicine | 18.2 | 1.6 | 2.9 | 125 |
| Rheumatology | 84.5 | 36.6 | 51.0 | 238 |
| Internal medicine | 24.5 | 2.0 | 3.7 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 76.2 | 63.9 | 69.5 | 3156 |
| Palliative medicine | 100.0 | 4.2 | 8.0 | 24 |
| Pathology | 45.8 | 45.7 | 45.7 | 3836 |
| Neonatology | 75.9 | 24.2 | 36.6 | 534 |
| Perinatology | 82.6 | 28.3 | 42.1 | 538 |
| Pediatrics | 41.7 | 2.3 | 4.4 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 25.0 | 2.7 | 4.9 | 37 |
| Epidemiology | 64.7 | 4.3 | 8.1 | 253 |
| Preventive medicine | 37.1 | 5.2 | 9.1 | 1824 |
| Nuclear medicine | 59.0 | 25.4 | 35.5 | 142 |
| Radiology | 50.0 | 6.0 | 10.7 | 200 |
| Gynecology | 77.2 | 24.6 | 37.3 | 399 |
| Reproductive medicine | 75.0 | 14.3 | 24.0 | 21 |
| General surgery | 51.5 | 32.5 | 39.8 | 2547 |
| Neurosurgery | 62.1 | 7.9 | 14.0 | 228 |
| Obstetrics | 83.7 | 29.6 | 43.7 | 470 |
| Ophthalmology | 89.4 | 37.7 | 53.1 | 673 |
| Orthopedics | 77.3 | 12.7 | 21.8 | 134 |
| Otolaryngology | 78.0 | 32.1 | 45.5 | 573 |
| Surgery plastic | 57.1 | 4.6 | 8.5 | 87 |
| Thoracic surgery | 72.8 | 20.4 | 31.9 | 407 |
| Traumatology | 77.4 | 29.0 | 42.2 | 814 |
| Urology | 77.5 | 63.6 | 69.9 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 100.0 | 27.6 | 43.2 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 69.3 | 42.6 | 52.7 | 39293 |
| macro avg | 54.8 | 22.1 | 29.1 | 39293 |
| weighted avg | 67.3 | 42.6 | 50.0 | 39293 |

## Classifier:  MULTILAYER PERCEPTRON
### Word Representation: TFIDF + SCOVACLIS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 33.8 | 10.3 | 15.8 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 40.5 | 25.3 | 31.1 | 178 |
| Bariatric medicine | 85.7 | 31.6 | 46.2 | 19 |
| Dermatology | 85.9 | 68.8 | 76.4 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 84.2 | 31.4 | 45.7 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 80.7 | 67.2 | 73.3 | 1101 |
| Geriatrics | 46.8 | 42.3 | 44.5 | 3223 |
| Cardiology | 86.6 | 79.0 | 82.6 | 2817 |
| Endocrinology | 87.3 | 68.1 | 76.5 | 1268 |
| Gastroenterology | 90.2 | 73.8 | 81.1 | 1764 |
| Hematology | 88.6 | 64.7 | 74.8 | 1109 |
| Infectious disease medicine | 28.6 | 5.9 | 9.8 | 68 |
| Medical oncology | 91.3 | 81.0 | 85.9 | 4035 |
| Nephrology | 84.6 | 70.1 | 76.6 | 953 |
| Pulmonary medicine | 14.3 | 4.0 | 6.2 | 125 |
| Rheumatology | 82.4 | 49.2 | 61.6 | 238 |
| Internal medicine | 21.3 | 10.6 | 14.1 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 87.4 | 77.5 | 82.2 | 3156 |
| Palliative medicine | 50.0 | 4.2 | 7.7 | 24 |
| Pathology | 55.0 | 45.4 | 49.8 | 3836 |
| Neonatology | 65.9 | 47.0 | 54.9 | 534 |
| Perinatology | 80.1 | 57.6 | 67.0 | 538 |
| Pediatrics | 29.9 | 14.8 | 19.8 | 431 |
| Rehabilitation | 50.0 | 7.8 | 13.5 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 50.0 | 9.1 | 15.4 | 33 |
| Psychiatry | 47.4 | 24.3 | 32.1 | 37 |
| Epidemiology | 41.2 | 13.8 | 20.7 | 253 |
| Preventive medicine | 42.9 | 19.6 | 26.9 | 1824 |
| Nuclear medicine | 66.0 | 45.1 | 53.6 | 142 |
| Radiology | 43.9 | 18.0 | 25.5 | 200 |
| Gynecology | 79.3 | 45.1 | 57.5 | 399 |
| Reproductive medicine | 60.0 | 14.3 | 23.1 | 21 |
| General surgery | 64.2 | 41.4 | 50.4 | 2547 |
| Neurosurgery | 45.6 | 15.8 | 23.5 | 228 |
| Obstetrics | 88.0 | 60.9 | 71.9 | 470 |
| Ophthalmology | 87.3 | 60.3 | 71.4 | 673 |
| Orthopedics | 53.4 | 23.1 | 32.3 | 134 |
| Otolaryngology | 80.4 | 53.6 | 64.3 | 573 |
| Surgery plastic | 58.6 | 19.5 | 29.3 | 87 |
| Thoracic surgery | 66.8 | 37.1 | 47.7 | 407 |
| Traumatology | 75.0 | 56.1 | 64.2 | 814 |
| Urology | 85.3 | 76.2 | 80.5 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 100.0 | 37.9 | 55.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 74.7 | 57.4 | 64.9 | 39293 |
| macro avg | 56.3 | 34.9 | 41.5 | 39293 |
| weighted avg | 72.5 | 57.4 | 63.5 | 39293 |

## Classifier:  DECISION TREE
### Word Representation: SCOVACLIS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 3.7 | 3.1 | 3.4 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 7.0 | 9.0 | 7.9 | 178 |
| Bariatric medicine | 9.5 | 10.5 | 10.0 | 19 |
| Dermatology | 50.9 | 51.0 | 51.0 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 17.4 | 7.8 | 10.8 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 45.6 | 47.3 | 46.5 | 1101 |
| Geriatrics | 30.2 | 30.5 | 30.4 | 3223 |
| Cardiology | 58.7 | 59.7 | 59.2 | 2817 |
| Endocrinology | 46.7 | 45.7 | 46.2 | 1268 |
| Gastroenterology | 56.1 | 55.7 | 55.9 | 1764 |
| Hematology | 45.6 | 47.6 | 46.6 | 1109 |
| Infectious disease medicine | 5.1 | 4.4 | 4.7 | 68 |
| Medical oncology | 67.5 | 67.8 | 67.7 | 4035 |
| Nephrology | 55.2 | 57.5 | 56.3 | 953 |
| Pulmonary medicine | 2.3 | 2.4 | 2.4 | 125 |
| Rheumatology | 19.0 | 21.8 | 20.4 | 238 |
| Internal medicine | 6.9 | 6.4 | 6.6 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 60.2 | 58.8 | 59.5 | 3156 |
| Palliative medicine | 6.2 | 8.3 | 7.1 | 24 |
| Pathology | 36.0 | 37.8 | 36.9 | 3836 |
| Neonatology | 24.2 | 23.6 | 23.9 | 534 |
| Perinatology | 39.3 | 41.3 | 40.3 | 538 |
| Pediatrics | 7.1 | 8.4 | 7.7 | 431 |
| Rehabilitation | 2.6 | 3.1 | 2.8 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 3.7 | 3.0 | 3.3 | 33 |
| Psychiatry | 6.9 | 10.8 | 8.4 | 37 |
| Epidemiology | 4.3 | 3.6 | 3.9 | 253 |
| Preventive medicine | 16.6 | 15.7 | 16.1 | 1824 |
| Nuclear medicine | 15.4 | 16.9 | 16.1 | 142 |
| Radiology | 1.5 | 2.0 | 1.7 | 200 |
| Gynecology | 26.3 | 28.1 | 27.2 | 399 |
| Reproductive medicine | 5.3 | 4.8 | 5.0 | 21 |
| General surgery | 33.2 | 33.6 | 33.4 | 2547 |
| Neurosurgery | 10.0 | 10.5 | 10.3 | 228 |
| Obstetrics | 40.8 | 41.5 | 41.1 | 470 |
| Ophthalmology | 38.5 | 41.3 | 39.8 | 673 |
| Orthopedics | 13.3 | 15.7 | 14.4 | 134 |
| Otolaryngology | 36.0 | 38.4 | 37.2 | 573 |
| Surgery plastic | 10.1 | 10.3 | 10.2 | 87 |
| Thoracic surgery | 21.8 | 22.4 | 22.1 | 407 |
| Traumatology | 30.5 | 31.0 | 30.8 | 814 |
| Urology | 62.9 | 62.0 | 62.5 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 7.4 | 6.9 | 7.1 | 29 |
| Tropical medicine | 5.0 | 4.5 | 4.8 | 22 |
| micro avg | 42.6 | 43.1 | 42.8 | 39293 |
| macro avg | 22.3 | 22.6 | 22.4 | 39293 |
| weighted avg | 42.7 | 43.1 | 42.9 | 39293 |
| Immunochemistry | 0.0 | 0.0 | 0.0 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 50.0 | 0.6 | 1.1 | 178 |
| Bariatric medicine | 0.0 | 0.0 | 0.0 | 19 |
| Dermatology | 78.3 | 42.3 | 54.9 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 66.7 | 2.0 | 3.8 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 78.4 | 32.7 | 46.2 | 1101 |
| Geriatrics | 45.2 | 9.1 | 15.2 | 3223 |
| Cardiology | 82.6 | 55.0 | 66.0 | 2817 |
| Endocrinology | 82.4 | 32.2 | 46.3 | 1268 |
| Gastroenterology | 86.5 | 49.0 | 62.6 | 1764 |
| Hematology | 81.7 | 28.2 | 42.0 | 1109 |
| Infectious disease medicine | 33.3 | 1.5 | 2.8 | 68 |
| Medical oncology | 82.9 | 67.1 | 74.1 | 4035 |
| Nephrology | 79.1 | 51.3 | 62.3 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 85.7 | 5.0 | 9.5 | 238 |
| Internal medicine | 20.0 | 0.8 | 1.5 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 80.7 | 58.4 | 67.8 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 50.2 | 22.9 | 31.5 | 3836 |
| Neonatology | 77.5 | 10.3 | 18.2 | 534 |
| Perinatology | 80.6 | 26.2 | 39.6 | 538 |
| Pediatrics | 25.0 | 0.7 | 1.4 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 100.0 | 2.7 | 5.3 | 37 |
| Epidemiology | 0.0 | 0.0 | 0.0 | 253 |
| Preventive medicine | 32.9 | 1.4 | 2.6 | 1824 |
| Nuclear medicine | 0.0 | 0.0 | 0.0 | 142 |
| Radiology | 0.0 | 0.0 | 0.0 | 200 |
| Gynecology | 71.0 | 11.0 | 19.1 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 66.0 | 18.2 | 28.5 | 2547 |
| Neurosurgery | 40.0 | 0.9 | 1.7 | 228 |
| Obstetrics | 86.8 | 28.1 | 42.4 | 470 |
| Ophthalmology | 83.2 | 19.2 | 31.2 | 673 |
| Orthopedics | 20.0 | 0.7 | 1.4 | 134 |
| Otolaryngology | 75.5 | 12.4 | 21.3 | 573 |
| Surgery plastic | 0.0 | 0.0 | 0.0 | 87 |
| Thoracic surgery | 75.0 | 6.6 | 12.2 | 407 |
| Traumatology | 78.0 | 17.0 | 27.9 | 814 |
| Urology | 83.5 | 57.1 | 67.8 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 0.0 | 0.0 | 0.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 76.0 | 32.6 | 45.6 | 39293 |
| macro avg | 42.3 | 13.6 | 18.5 | 39293 |
| weighted avg | 67.2 | 32.6 | 41.4 | 39293 |
| Immunochemistry | 36.4 | 1.8 | 3.4 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 34.8 | 4.5 | 8.0 | 178 |
| Bariatric medicine | 71.4 | 26.3 | 38.5 | 19 |
| Dermatology | 76.8 | 47.9 | 59.0 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 82.8 | 23.5 | 36.6 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 77.2 | 45.1 | 57.0 | 1101 |
| Geriatrics | 37.8 | 20.9 | 26.9 | 3223 |
| Cardiology | 80.9 | 62.5 | 70.5 | 2817 |
| Endocrinology | 80.2 | 45.7 | 58.2 | 1268 |
| Gastroenterology | 83.2 | 61.7 | 70.8 | 1764 |
| Hematology | 81.1 | 44.5 | 57.5 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 78.6 | 70.0 | 74.1 | 4035 |
| Nephrology | 81.2 | 54.6 | 65.3 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 77.6 | 31.9 | 45.2 | 238 |
| Internal medicine | 17.6 | 1.4 | 2.6 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 79.6 | 63.1 | 70.4 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 47.2 | 38.8 | 42.6 | 3836 |
| Neonatology | 66.0 | 25.1 | 36.4 | 534 |
| Perinatology | 68.3 | 35.3 | 46.6 | 538 |
| Pediatrics | 23.3 | 2.3 | 4.2 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 25.0 | 5.4 | 8.9 | 37 |
| Epidemiology | 43.5 | 4.0 | 7.2 | 253 |
| Preventive medicine | 22.1 | 4.4 | 7.4 | 1824 |
| Nuclear medicine | 60.4 | 22.5 | 32.8 | 142 |
| Radiology | 100.0 | 1.5 | 3.0 | 200 |
| Gynecology | 73.7 | 30.8 | 43.5 | 399 |
| Reproductive medicine | 60.0 | 14.3 | 23.1 | 21 |
| General surgery | 57.2 | 29.1 | 38.5 | 2547 |
| Neurosurgery | 44.7 | 7.5 | 12.8 | 228 |
| Obstetrics | 73.6 | 36.8 | 49.1 | 470 |
| Ophthalmology | 81.4 | 39.1 | 52.8 | 673 |
| Orthopedics | 75.9 | 16.4 | 27.0 | 134 |
| Otolaryngology | 79.6 | 34.7 | 48.4 | 573 |
| Surgery plastic | 66.7 | 2.3 | 4.4 | 87 |
| Thoracic surgery | 65.0 | 21.9 | 32.7 | 407 |
| Traumatology | 71.3 | 31.8 | 44.0 | 814 |
| Urology | 83.7 | 62.1 | 71.3 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 100.0 | 20.7 | 34.3 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 69.4 | 42.1 | 52.4 | 39293 |
| macro avg | 50.0 | 22.4 | 29.0 | 39293 |
| weighted avg | 65.1 | 42.1 | 49.8 | 39293 |

## Classifier:  MULTILAYER PERCEPTRON
### Word Representation: SCOVACLIS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 0.0 | 0.0 | 0.0 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 46.4 | 7.3 | 12.6 | 178 |
| Bariatric medicine | 53.8 | 36.8 | 43.8 | 19 |
| Dermatology | 77.0 | 55.3 | 64.4 | 1776 |
| Forensic medicine | 100.0 | 100.0 | 100.0 | 1 |
| Family practice | 90.6 | 28.4 | 43.3 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 75.3 | 58.5 | 65.8 | 1101 |
| Geriatrics | 49.0 | 6.8 | 11.9 | 3223 |
| Cardiology | 81.1 | 67.6 | 73.7 | 2817 |
| Endocrinology | 76.3 | 57.8 | 65.8 | 1268 |
| Gastroenterology | 80.8 | 67.0 | 73.3 | 1764 |
| Hematology | 76.4 | 54.8 | 63.8 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 81.6 | 73.9 | 77.6 | 4035 |
| Nephrology | 78.0 | 62.1 | 69.2 | 953 |
| Pulmonary medicine | 50.0 | 1.6 | 3.1 | 125 |
| Rheumatology | 71.4 | 29.4 | 41.7 | 238 |
| Internal medicine | 0.0 | 0.0 | 0.0 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 82.5 | 65.5 | 73.0 | 3156 |
| Palliative medicine | 50.0 | 8.3 | 14.3 | 24 |
| Pathology | 57.8 | 26.5 | 36.3 | 3836 |
| Neonatology | 69.7 | 26.2 | 38.1 | 534 |
| Perinatology | 69.0 | 43.1 | 53.1 | 538 |
| Pediatrics | 21.4 | 0.7 | 1.3 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 25.0 | 3.0 | 5.4 | 33 |
| Psychiatry | 37.5 | 8.1 | 13.3 | 37 |
| Epidemiology | 20.0 | 0.4 | 0.8 | 253 |
| Preventive medicine | 59.5 | 1.2 | 2.4 | 1824 |
| Nuclear medicine | 61.0 | 35.2 | 44.6 | 142 |
| Radiology | 0.0 | 0.0 | 0.0 | 200 |
| Gynecology | 71.6 | 36.1 | 48.0 | 399 |
| Reproductive medicine | 44.4 | 19.0 | 26.7 | 21 |
| General surgery | 69.6 | 29.1 | 41.1 | 2547 |
| Neurosurgery | 53.8 | 9.2 | 15.7 | 228 |
| Obstetrics | 72.0 | 44.3 | 54.8 | 470 |
| Ophthalmology | 71.1 | 52.3 | 60.3 | 673 |
| Orthopedics | 60.0 | 22.4 | 32.6 | 134 |
| Otolaryngology | 67.4 | 48.7 | 56.5 | 573 |
| Surgery plastic | 52.2 | 13.8 | 21.8 | 87 |
| Thoracic surgery | 65.9 | 27.0 | 38.3 | 407 |
| Traumatology | 68.9 | 37.0 | 48.1 | 814 |
| Urology | 82.6 | 67.0 | 74.0 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 90.9 | 34.5 | 50.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 75.8 | 43.5 | 55.3 | 39293 |
| macro avg | 50.9 | 27.9 | 33.8 | 39293 |
| weighted avg | 68.3 | 43.5 | 50.6 | 39293 |

## Classifier:  DECISION TREE
### Word Representation: TFIDF + SCOVACLIS - STOPWORDS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 5.4 | 4.5 | 4.9 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 8.8 | 7.3 | 8.0 | 178 |
| Bariatric medicine | 30.0 | 15.8 | 20.7 | 19 |
| Dermatology | 56.2 | 52.3 | 54.2 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 10.0 | 6.9 | 8.1 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 52.9 | 48.8 | 50.8 | 1101 |
| Geriatrics | 30.2 | 29.4 | 29.8 | 3223 |
| Cardiology | 62.9 | 62.1 | 62.5 | 2817 |
| Endocrinology | 52.0 | 47.8 | 49.8 | 1268 |
| Gastroenterology | 61.1 | 58.9 | 60.0 | 1764 |
| Hematology | 54.6 | 48.4 | 51.3 | 1109 |
| Infectious disease medicine | 3.9 | 2.9 | 3.4 | 68 |
| Medical oncology | 69.3 | 70.6 | 69.9 | 4035 |
| Nephrology | 58.2 | 55.7 | 56.9 | 953 |
| Pulmonary medicine | 3.1 | 2.4 | 2.7 | 125 |
| Rheumatology | 21.1 | 16.8 | 18.7 | 238 |
| Internal medicine | 7.9 | 6.4 | 7.1 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 62.9 | 61.5 | 62.2 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 38.7 | 39.8 | 39.2 | 3836 |
| Neonatology | 23.8 | 20.2 | 21.9 | 534 |
| Perinatology | 43.5 | 40.1 | 41.8 | 538 |
| Pediatrics | 7.9 | 7.2 | 7.5 | 431 |
| Rehabilitation | 3.2 | 3.1 | 3.2 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 3.8 | 3.0 | 3.4 | 33 |
| Psychiatry | 8.8 | 8.1 | 8.5 | 37 |
| Epidemiology | 13.2 | 7.9 | 9.9 | 253 |
| Preventive medicine | 16.8 | 14.5 | 15.6 | 1824 |
| Nuclear medicine | 15.8 | 13.4 | 14.5 | 142 |
| Radiology | 4.2 | 4.0 | 4.1 | 200 |
| Gynecology | 37.3 | 29.8 | 33.1 | 399 |
| Reproductive medicine | 4.2 | 4.8 | 4.4 | 21 |
| General surgery | 35.2 | 32.2 | 33.6 | 2547 |
| Neurosurgery | 10.6 | 8.8 | 9.6 | 228 |
| Obstetrics | 48.6 | 43.2 | 45.7 | 470 |
| Ophthalmology | 41.8 | 39.2 | 40.5 | 673 |
| Orthopedics | 17.3 | 13.4 | 15.1 | 134 |
| Otolaryngology | 38.3 | 36.3 | 37.3 | 573 |
| Surgery plastic | 15.0 | 10.3 | 12.2 | 87 |
| Thoracic surgery | 26.3 | 25.1 | 25.7 | 407 |
| Traumatology | 31.8 | 29.6 | 30.7 | 814 |
| Urology | 64.4 | 62.6 | 63.5 | 1708 |
| Specialties surgical | 7.7 | 20.0 | 11.1 | 5 |
| Sports medicine | 7.4 | 6.9 | 7.1 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 46.4 | 43.9 | 45.1 | 39293 |
| macro avg | 24.8 | 22.8 | 23.6 | 39293 |
| weighted avg | 45.6 | 43.9 | 44.7 | 39293 |
| Immunochemistry | 0.0 | 0.0 | 0.0 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 0.0 | 0.0 | 0.0 | 178 |
| Bariatric medicine | 0.0 | 0.0 | 0.0 | 19 |
| Dermatology | 85.2 | 15.9 | 26.9 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 92.0 | 22.5 | 36.2 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 90.2 | 10.1 | 18.1 | 1101 |
| Geriatrics | 45.5 | 6.9 | 12.0 | 3223 |
| Cardiology | 88.5 | 28.5 | 43.1 | 2817 |
| Endocrinology | 93.2 | 9.8 | 17.7 | 1268 |
| Gastroenterology | 93.7 | 23.4 | 37.5 | 1764 |
| Hematology | 94.9 | 11.8 | 21.0 | 1109 |
| Infectious disease medicine | 50.0 | 1.5 | 2.9 | 68 |
| Medical oncology | 86.9 | 52.0 | 65.1 | 4035 |
| Nephrology | 87.1 | 29.1 | 43.6 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 94.1 | 13.4 | 23.5 | 238 |
| Internal medicine | 10.0 | 0.2 | 0.3 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 86.1 | 31.9 | 46.6 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 54.3 | 19.1 | 28.2 | 3836 |
| Neonatology | 95.0 | 7.1 | 13.2 | 534 |
| Perinatology | 93.8 | 13.9 | 24.3 | 538 |
| Pediatrics | 40.0 | 0.5 | 0.9 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 0.0 | 0.0 | 0.0 | 37 |
| Epidemiology | 0.0 | 0.0 | 0.0 | 253 |
| Preventive medicine | 52.8 | 1.5 | 3.0 | 1824 |
| Nuclear medicine | 75.0 | 2.1 | 4.1 | 142 |
| Radiology | 0.0 | 0.0 | 0.0 | 200 |
| Gynecology | 78.6 | 2.8 | 5.3 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 72.7 | 7.3 | 13.3 | 2547 |
| Neurosurgery | 0.0 | 0.0 | 0.0 | 228 |
| Obstetrics | 94.6 | 14.9 | 25.7 | 470 |
| Ophthalmology | 96.6 | 4.2 | 8.0 | 673 |
| Orthopedics | 0.0 | 0.0 | 0.0 | 134 |
| Otolaryngology | 86.4 | 6.6 | 12.3 | 573 |
| Surgery plastic | 0.0 | 0.0 | 0.0 | 87 |
| Thoracic surgery | 60.0 | 0.7 | 1.5 | 407 |
| Traumatology | 88.1 | 6.4 | 11.9 | 814 |
| Urology | 92.7 | 31.2 | 46.7 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 0.0 | 0.0 | 0.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 80.3 | 18.9 | 30.6 | 39293 |
| macro avg | 44.4 | 7.8 | 12.4 | 39293 |
| weighted avg | 73.4 | 18.9 | 28.1 | 39293 |
| Immunochemistry | 33.3 | 1.3 | 2.6 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 35.7 | 5.6 | 9.7 | 178 |
| Bariatric medicine | 60.0 | 15.8 | 25.0 | 19 |
| Dermatology | 82.4 | 46.1 | 59.1 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 89.3 | 24.5 | 38.5 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 81.5 | 44.5 | 57.6 | 1101 |
| Geriatrics | 44.8 | 21.3 | 28.8 | 3223 |
| Cardiology | 86.8 | 59.5 | 70.6 | 2817 |
| Endocrinology | 87.6 | 41.7 | 56.5 | 1268 |
| Gastroenterology | 85.8 | 56.0 | 67.7 | 1764 |
| Hematology | 87.7 | 42.5 | 57.2 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 72.6 | 75.3 | 73.9 | 4035 |
| Nephrology | 85.4 | 51.5 | 64.3 | 953 |
| Pulmonary medicine | 20.0 | 1.6 | 3.0 | 125 |
| Rheumatology | 83.7 | 36.6 | 50.9 | 238 |
| Internal medicine | 20.0 | 1.6 | 2.9 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 75.1 | 64.5 | 69.4 | 3156 |
| Palliative medicine | 50.0 | 4.2 | 7.7 | 24 |
| Pathology | 45.4 | 46.5 | 45.9 | 3836 |
| Neonatology | 76.3 | 25.3 | 38.0 | 534 |
| Perinatology | 82.1 | 29.0 | 42.9 | 538 |
| Pediatrics | 37.5 | 1.4 | 2.7 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 20.0 | 2.7 | 4.8 | 37 |
| Epidemiology | 78.6 | 4.3 | 8.2 | 253 |
| Preventive medicine | 33.5 | 4.8 | 8.3 | 1824 |
| Nuclear medicine | 62.5 | 24.6 | 35.4 | 142 |
| Radiology | 44.4 | 6.0 | 10.6 | 200 |
| Gynecology | 77.7 | 25.3 | 38.2 | 399 |
| Reproductive medicine | 60.0 | 14.3 | 23.1 | 21 |
| General surgery | 50.4 | 32.4 | 39.5 | 2547 |
| Neurosurgery | 69.2 | 7.9 | 14.2 | 228 |
| Obstetrics | 81.2 | 29.4 | 43.1 | 470 |
| Ophthalmology | 89.5 | 36.8 | 52.2 | 673 |
| Orthopedics | 78.9 | 11.2 | 19.6 | 134 |
| Otolaryngology | 79.0 | 32.8 | 46.4 | 573 |
| Surgery plastic | 50.0 | 3.4 | 6.5 | 87 |
| Thoracic surgery | 71.7 | 19.9 | 31.2 | 407 |
| Traumatology | 77.5 | 29.1 | 42.3 | 814 |
| Urology | 76.4 | 63.8 | 69.5 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 100.0 | 27.6 | 43.2 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 68.9 | 42.7 | 52.7 | 39293 |
| macro avg | 53.1 | 22.0 | 28.9 | 39293 |
| weighted avg | 66.9 | 42.7 | 49.9 | 39293 |

## Classifier:  MULTILAYER PERCEPTRON
### Word Representation: TFIDF + SCOVACLIS - STOPWORDS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 34.4 | 9.4 | 14.7 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 38.7 | 27.0 | 31.8 | 178 |
| Bariatric medicine | 87.5 | 36.8 | 51.9 | 19 |
| Dermatology | 84.8 | 69.7 | 76.5 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 81.0 | 33.3 | 47.2 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 81.1 | 66.8 | 73.3 | 1101 |
| Geriatrics | 48.9 | 37.3 | 42.3 | 3223 |
| Cardiology | 89.1 | 76.7 | 82.4 | 2817 |
| Endocrinology | 87.2 | 67.9 | 76.4 | 1268 |
| Gastroenterology | 89.3 | 74.0 | 80.9 | 1764 |
| Hematology | 90.1 | 63.4 | 74.4 | 1109 |
| Infectious disease medicine | 41.2 | 10.3 | 16.5 | 68 |
| Medical oncology | 90.3 | 82.2 | 86.1 | 4035 |
| Nephrology | 84.1 | 71.5 | 77.3 | 953 |
| Pulmonary medicine | 14.8 | 3.2 | 5.3 | 125 |
| Rheumatology | 83.0 | 49.2 | 61.7 | 238 |
| Internal medicine | 23.1 | 9.2 | 13.1 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 88.4 | 76.8 | 82.2 | 3156 |
| Palliative medicine | 66.7 | 8.3 | 14.8 | 24 |
| Pathology | 53.1 | 50.0 | 51.5 | 3836 |
| Neonatology | 67.3 | 46.3 | 54.8 | 534 |
| Perinatology | 78.7 | 59.9 | 68.0 | 538 |
| Pediatrics | 30.2 | 13.5 | 18.6 | 431 |
| Rehabilitation | 40.0 | 6.2 | 10.8 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 50.0 | 6.1 | 10.8 | 33 |
| Psychiatry | 52.9 | 24.3 | 33.3 | 37 |
| Epidemiology | 41.4 | 11.5 | 18.0 | 253 |
| Preventive medicine | 41.7 | 19.9 | 26.9 | 1824 |
| Nuclear medicine | 70.2 | 46.5 | 55.9 | 142 |
| Radiology | 47.9 | 17.0 | 25.1 | 200 |
| Gynecology | 75.7 | 47.6 | 58.5 | 399 |
| Reproductive medicine | 42.9 | 14.3 | 21.4 | 21 |
| General surgery | 59.1 | 45.4 | 51.4 | 2547 |
| Neurosurgery | 44.2 | 18.4 | 26.0 | 228 |
| Obstetrics | 85.7 | 62.6 | 72.3 | 470 |
| Ophthalmology | 86.8 | 61.7 | 72.1 | 673 |
| Orthopedics | 52.3 | 25.4 | 34.2 | 134 |
| Otolaryngology | 79.6 | 54.6 | 64.8 | 573 |
| Surgery plastic | 55.2 | 18.4 | 27.6 | 87 |
| Thoracic surgery | 67.7 | 36.1 | 47.1 | 407 |
| Traumatology | 76.2 | 56.1 | 64.6 | 814 |
| Urology | 85.8 | 75.5 | 80.3 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 100.0 | 37.9 | 55.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 74.5 | 57.7 | 65.0 | 39293 |
| macro avg | 56.3 | 35.3 | 41.8 | 39293 |
| weighted avg | 72.2 | 57.7 | 63.6 | 39293 |

## Classifier:  DECISION TREE
### Word Representation: SCOVACLIST - STOPWORDS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 4.3 | 4.0 | 4.2 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 3.3 | 3.9 | 3.6 | 178 |
| Bariatric medicine | 14.3 | 10.5 | 12.1 | 19 |
| Dermatology | 51.7 | 51.3 | 51.5 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 13.4 | 8.8 | 10.7 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 47.9 | 47.2 | 47.6 | 1101 |
| Geriatrics | 30.2 | 30.3 | 30.3 | 3223 |
| Cardiology | 59.6 | 60.0 | 59.8 | 2817 |
| Endocrinology | 49.2 | 47.6 | 48.4 | 1268 |
| Gastroenterology | 58.7 | 57.1 | 57.9 | 1764 |
| Hematology | 47.5 | 46.4 | 47.0 | 1109 |
| Infectious disease medicine | 4.1 | 4.4 | 4.2 | 68 |
| Medical oncology | 68.1 | 67.8 | 67.9 | 4035 |
| Nephrology | 53.8 | 55.5 | 54.6 | 953 |
| Pulmonary medicine | 2.9 | 3.2 | 3.1 | 125 |
| Rheumatology | 21.2 | 21.0 | 21.1 | 238 |
| Internal medicine | 6.5 | 6.4 | 6.4 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 61.8 | 60.3 | 61.1 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 37.4 | 37.8 | 37.6 | 3836 |
| Neonatology | 22.5 | 22.7 | 22.6 | 534 |
| Perinatology | 38.8 | 39.4 | 39.1 | 538 |
| Pediatrics | 7.0 | 7.2 | 7.1 | 431 |
| Rehabilitation | 4.6 | 6.2 | 5.3 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 7.0 | 8.1 | 7.5 | 37 |
| Epidemiology | 6.1 | 4.7 | 5.3 | 253 |
| Preventive medicine | 17.2 | 17.2 | 17.2 | 1824 |
| Nuclear medicine | 11.0 | 12.0 | 11.4 | 142 |
| Radiology | 2.5 | 3.0 | 2.7 | 200 |
| Gynecology | 29.9 | 30.3 | 30.1 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 31.7 | 33.3 | 32.5 | 2547 |
| Neurosurgery | 12.1 | 13.6 | 12.8 | 228 |
| Obstetrics | 43.2 | 42.3 | 42.7 | 470 |
| Ophthalmology | 40.3 | 41.0 | 40.6 | 673 |
| Orthopedics | 8.9 | 8.2 | 8.5 | 134 |
| Otolaryngology | 32.7 | 36.3 | 34.4 | 573 |
| Surgery plastic | 7.9 | 5.7 | 6.7 | 87 |
| Thoracic surgery | 21.0 | 23.3 | 22.1 | 407 |
| Traumatology | 30.4 | 29.6 | 30.0 | 814 |
| Urology | 60.9 | 60.5 | 60.7 | 1708 |
| Specialties surgical | 7.7 | 20.0 | 11.1 | 5 |
| Sports medicine | 10.3 | 10.3 | 10.3 | 29 |
| Tropical medicine | 4.8 | 4.5 | 4.7 | 22 |
| micro avg | 43.1 | 43.1 | 43.1 | 39293 |
| macro avg | 22.5 | 22.4 | 22.4 | 39293 |
| weighted avg | 43.3 | 43.1 | 43.2 | 39293 |
| Immunochemistry | 0.0 | 0.0 | 0.0 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 0.0 | 0.0 | 0.0 | 178 |
| Bariatric medicine | 0.0 | 0.0 | 0.0 | 19 |
| Dermatology | 81.9 | 40.3 | 54.0 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 55.6 | 4.9 | 9.0 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 80.4 | 34.2 | 48.0 | 1101 |
| Geriatrics | 42.5 | 8.4 | 14.0 | 3223 |
| Cardiology | 83.3 | 55.8 | 66.8 | 2817 |
| Endocrinology | 81.7 | 35.5 | 49.5 | 1268 |
| Gastroenterology | 84.7 | 51.0 | 63.7 | 1764 |
| Hematology | 82.1 | 30.7 | 44.6 | 1109 |
| Infectious disease medicine | 50.0 | 1.5 | 2.9 | 68 |
| Medical oncology | 84.1 | 66.0 | 74.0 | 4035 |
| Nephrology | 80.9 | 52.0 | 63.3 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 84.2 | 6.7 | 12.5 | 238 |
| Internal medicine | 10.5 | 0.3 | 0.6 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 82.2 | 58.9 | 68.6 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 51.9 | 23.0 | 31.9 | 3836 |
| Neonatology | 70.8 | 6.4 | 11.7 | 534 |
| Perinatology | 82.9 | 24.3 | 37.6 | 538 |
| Pediatrics | 25.0 | 0.9 | 1.8 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 0.0 | 0.0 | 0.0 | 37 |
| Epidemiology | 0.0 | 0.0 | 0.0 | 253 |
| Preventive medicine | 30.2 | 1.6 | 3.0 | 1824 |
| Nuclear medicine | 100.0 | 2.8 | 5.5 | 142 |
| Radiology | 0.0 | 0.0 | 0.0 | 200 |
| Gynecology | 76.9 | 10.0 | 17.7 | 399 |
| Reproductive medicine | 0.0 | 0.0 | 0.0 | 21 |
| General surgery | 62.5 | 16.8 | 26.5 | 2547 |
| Neurosurgery | 75.0 | 1.3 | 2.6 | 228 |
| Obstetrics | 83.0 | 24.9 | 38.3 | 470 |
| Ophthalmology | 86.8 | 20.5 | 33.2 | 673 |
| Orthopedics | 0.0 | 0.0 | 0.0 | 134 |
| Otolaryngology | 73.3 | 16.8 | 27.3 | 573 |
| Surgery plastic | 0.0 | 0.0 | 0.0 | 87 |
| Thoracic surgery | 48.3 | 3.4 | 6.4 | 407 |
| Traumatology | 77.1 | 12.4 | 21.4 | 814 |
| Urology | 85.0 | 58.7 | 69.4 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 0.0 | 0.0 | 0.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 76.8 | 32.6 | 45.8 | 39293 |
| macro avg | 41.1 | 13.7 | 18.6 | 39293 |
| weighted avg | 67.0 | 32.6 | 41.5 | 39293 |
| Immunochemistry | 50.0 | 2.2 | 4.3 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 31.0 | 5.1 | 8.7 | 178 |
| Bariatric medicine | 80.0 | 21.1 | 33.3 | 19 |
| Dermatology | 78.6 | 48.9 | 60.3 | 1776 |
| Forensic medicine | 0.0 | 0.0 | 0.0 | 1 |
| Family practice | 80.6 | 24.5 | 37.6 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 77.9 | 44.2 | 56.4 | 1101 |
| Geriatrics | 38.4 | 21.8 | 27.9 | 3223 |
| Cardiology | 81.0 | 63.2 | 71.0 | 2817 |
| Endocrinology | 80.5 | 46.1 | 58.6 | 1268 |
| Gastroenterology | 81.6 | 62.2 | 70.6 | 1764 |
| Hematology | 81.9 | 46.5 | 59.3 | 1109 |
| Infectious disease medicine | 0.0 | 0.0 | 0.0 | 68 |
| Medical oncology | 80.0 | 69.9 | 74.6 | 4035 |
| Nephrology | 79.0 | 55.8 | 65.4 | 953 |
| Pulmonary medicine | 0.0 | 0.0 | 0.0 | 125 |
| Rheumatology | 79.6 | 31.1 | 44.7 | 238 |
| Internal medicine | 15.6 | 0.8 | 1.5 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 80.5 | 63.0 | 70.6 | 3156 |
| Palliative medicine | 0.0 | 0.0 | 0.0 | 24 |
| Pathology | 47.4 | 36.5 | 41.2 | 3836 |
| Neonatology | 65.0 | 26.8 | 37.9 | 534 |
| Perinatology | 72.0 | 36.8 | 48.7 | 538 |
| Pediatrics | 33.3 | 2.8 | 5.1 | 431 |
| Rehabilitation | 0.0 | 0.0 | 0.0 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 42.9 | 8.1 | 13.6 | 37 |
| Epidemiology | 50.0 | 3.6 | 6.6 | 253 |
| Preventive medicine | 19.2 | 5.8 | 8.9 | 1824 |
| Nuclear medicine | 72.5 | 20.4 | 31.9 | 142 |
| Radiology | 100.0 | 1.5 | 3.0 | 200 |
| Gynecology | 68.0 | 29.3 | 41.0 | 399 |
| Reproductive medicine | 80.0 | 19.0 | 30.8 | 21 |
| General surgery | 57.7 | 29.4 | 39.0 | 2547 |
| Neurosurgery | 52.9 | 7.9 | 13.7 | 228 |
| Obstetrics | 74.3 | 38.7 | 50.9 | 470 |
| Ophthalmology | 78.2 | 41.2 | 53.9 | 673 |
| Orthopedics | 71.4 | 14.9 | 24.7 | 134 |
| Otolaryngology | 77.6 | 35.1 | 48.3 | 573 |
| Surgery plastic | 75.0 | 3.4 | 6.6 | 87 |
| Thoracic surgery | 62.3 | 21.1 | 31.6 | 407 |
| Traumatology | 70.6 | 29.9 | 42.0 | 814 |
| Urology | 82.9 | 62.5 | 71.3 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 100.0 | 20.7 | 34.3 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 69.5 | 42.3 | 52.6 | 39293 |
| macro avg | 51.6 | 22.6 | 29.3 | 39293 |
| weighted avg | 65.4 | 42.3 | 50.1 | 39293 |

## Classifier:  MULTILAYER PERCEPTRON
### Word Representation: SCOVACLIST - STOPWORDS

| Specialty | Precision (%) | Recall (%) | F1 (%) | # docs. |
| --- | --- | --- | --- | --- |
| Immunochemistry | 20.0 | 1.3 | 2.5 | 224 |
| Allergy and immunology | 0.0 | 0.0 | 0.0 | 7 |
| Anesthesiology | 34.8 | 4.5 | 8.0 | 178 |
| Bariatric medicine | 53.8 | 36.8 | 43.8 | 19 |
| Dermatology | 75.4 | 56.4 | 64.5 | 1776 |
| Forensic medicine | 100.0 | 100.0 | 100.0 | 1 |
| Family practice | 89.3 | 24.5 | 38.5 | 102 |
| General practice | 0.0 | 0.0 | 0.0 | 1 |
| Genetics medical | 76.4 | 55.6 | 64.4 | 1101 |
| Geriatrics | 47.0 | 6.1 | 10.8 | 3223 |
| Cardiology | 81.3 | 64.4 | 71.9 | 2817 |
| Endocrinology | 77.7 | 58.1 | 66.5 | 1268 |
| Gastroenterology | 83.9 | 64.3 | 72.8 | 1764 |
| Hematology | 77.6 | 54.6 | 64.1 | 1109 |
| Infectious disease medicine | 50.0 | 1.5 | 2.9 | 68 |
| Medical oncology | 81.8 | 75.3 | 78.4 | 4035 |
| Nephrology | 77.3 | 63.0 | 69.4 | 953 |
| Pulmonary medicine | 20.0 | 0.8 | 1.5 | 125 |
| Rheumatology | 74.2 | 30.3 | 43.0 | 238 |
| Internal medicine | 20.0 | 0.2 | 0.3 | 643 |
| Military medicine | 0.0 | 0.0 | 0.0 | 0 |
| Neurology | 80.5 | 67.6 | 73.5 | 3156 |
| Palliative medicine | 25.0 | 4.2 | 7.1 | 24 |
| Pathology | 57.6 | 28.5 | 38.1 | 3836 |
| Neonatology | 66.1 | 28.5 | 39.8 | 534 |
| Perinatology | 68.8 | 40.9 | 51.3 | 538 |
| Pediatrics | 100.0 | 0.5 | 0.9 | 431 |
| Rehabilitation | 50.0 | 4.7 | 8.6 | 64 |
| Physical and rehabilitation medicine | 0.0 | 0.0 | 0.0 | 3 |
| Community psychiatry | 0.0 | 0.0 | 0.0 | 33 |
| Psychiatry | 33.3 | 8.1 | 13.0 | 37 |
| Epidemiology | 25.0 | 0.8 | 1.5 | 253 |
| Preventive medicine | 53.7 | 1.6 | 3.1 | 1824 |
| Nuclear medicine | 60.9 | 27.5 | 37.9 | 142 |
| Radiology | 0.0 | 0.0 | 0.0 | 200 |
| Gynecology | 67.4 | 39.3 | 49.7 | 399 |
| Reproductive medicine | 42.9 | 14.3 | 21.4 | 21 |
| General surgery | 68.4 | 27.5 | 39.2 | 2547 |
| Neurosurgery | 41.7 | 8.8 | 14.5 | 228 |
| Obstetrics | 75.9 | 48.3 | 59.0 | 470 |
| Ophthalmology | 74.2 | 48.3 | 58.5 | 673 |
| Orthopedics | 67.6 | 17.2 | 27.4 | 134 |
| Otolaryngology | 68.5 | 48.9 | 57.0 | 573 |
| Surgery plastic | 70.6 | 13.8 | 23.1 | 87 |
| Thoracic surgery | 75.0 | 21.4 | 33.3 | 407 |
| Traumatology | 67.2 | 38.8 | 49.2 | 814 |
| Urology | 82.0 | 66.9 | 73.7 | 1708 |
| Specialties surgical | 0.0 | 0.0 | 0.0 | 5 |
| Sports medicine | 90.9 | 34.5 | 50.0 | 29 |
| Tropical medicine | 0.0 | 0.0 | 0.0 | 22 |
| micro avg | 75.6 | 43.5 | 55.2 | 39293 |
| macro avg | 53.7 | 27.4 | 33.4 | 39293 |
| weighted avg | 69.1 | 43.5 | 50.6 | 39293 |
