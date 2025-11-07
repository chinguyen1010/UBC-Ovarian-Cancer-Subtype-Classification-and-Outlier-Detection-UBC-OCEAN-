# UBC-Ovarian-Cancer-Subtype-Classification-and-Outlier-Detection-UBC-OCEAN-
Navigating Ovarian Cancer: Unveiling Common Histotypes and Unearthing Rare Variants


Overview:

The goal of the UBC Ovarian Cancer subtypE clAssification and outlier detectioN (UBC-OCEAN) competition is to classify ovarian cancer subtypes. You will build a model trained on the world's most extensive ovarian cancer dataset of histopathology images obtained from more than 20 medical centers.

Your work will help enhance the applicability and accessibility of accurate ovarian cancer diagnoses.

This competition is hosted by the Artificial Intelligence in Medicine (AIM) Lab at the University of British Columbia. Established in 2019 under the guidance of Dr. Ali Bashashati, the AIM Lab specializes in the convergence of computational science, engineering, and biomedicine. Our primary goal is to advance the development of machine learning algorithms and software solutions that integrate various omics and imaging data sources. We are dedicated to uncovering new biological insights and identifying biomarkers that can enhance treatment selection strategies for cancer.


Description:

Ovarian carcinoma is the most lethal cancer of the female reproductive system. There are five common subtypes of ovarian cancer: high-grade serous carcinoma, clear-cell ovarian carcinoma, endometrioid, low-grade serous, and mucinous carcinoma. Additionally, there are several rare subtypes ("Outliers"). These are all characterized by distinct cellular morphologies, etiologies, molecular and genetic profiles, and clinical attributes. Subtype-specific treatment approaches are gaining prominence, though first requires subtype identification, a process that could be improved with data science.

Currently, ovarian cancer diagnosis relies on pathologists to assess subtypes. However, this presents several challenges, including disagreements between observers and the reproducibility of diagnostics. Furthermore, underserved communities often lack access to specialist pathologists, and even well-developed communities face a shortage of pathologists with expertise in gynecologic malignancies.

Deep learning models have exhibited remarkable proficiency in analyzing histopathology images. Yet challenges still exist, such as the need for a significant amount of training data, ideally from a single source. Technical, ethical, and financial constraints, as well as confidentiality concerns, make training a challenge. In this competition, you will have access to the most extensive and diverse ovarian cancer dataset of histopathology images from more than 20 centers across four continents.

<img width="760" height="605" alt="Screenshot 2025-11-06 at 11 29 08 PM" src="https://github.com/user-attachments/assets/88819059-3971-4a32-b815-3683e0d52a79" />



Competition host University of British Columbia (UBC) is a global center for teaching, learning, and research, consistently ranked among the top 20 public universities in the world. UBC embraces innovation and transforms ideas into action. Since 1915, UBC has been opening doors of opportunity for people with the curiosity, drive, and vision to shape a better world. Joining UBC is the BC Cancer, part of the Provincial Health Services Authority and its world-renowned Ovarian Cancer Research (OVCARE) team whose discoveries have led to progressive prevention strategies and improved diagnostics and treatments. BC Cancer provides a comprehensive cancer control program for the people of British Columbia in partnership with regional health authorities. We have also partnered with the Ovarian Tumour Tissue Analysis (OTTA) consortium, an international multidisciplinary network of investigators from more than 65 international teams across the globe. Finally, the OCEAN challenge is made possible through a generous donation from TD Bank Group through the BC Cancer Foundation.

Your work could yield improved accuracy in identifying ovarian cancer subtypes. Better classification would enable clinicians to formulate personalized treatment strategies regardless of geographic location. This targeted approach has the potential to enhance treatment efficacy, reduce adverse effects, and ultimately contribute to better patient outcomes for those diagnosed with this deadly cancer.


Evaluation
Submissions are evaluated using balanced accuracy.

Submission File
For each image_id in the test set you must predict a class for the label variable. The file should contain a header and have the following format:

image_id,label

2,CC

5,EC

6,HGSC

etc.

<img width="776" height="454" alt="Screenshot 2025-11-06 at 11 30 14 PM" src="https://github.com/user-attachments/assets/03dabbb6-8411-49c9-9cc7-e673d6d07c13" />

The organizers of the challenge extend their gratitude to the following institutions for their invaluable contribution to the data for this competition.

<img width="882" height="111" alt="image" src="https://github.com/user-attachments/assets/b3b702dc-bdfc-449a-be25-d5262e2bfd98" />


Citation:

Asadi-Aghbolaghi, M., Farahani, H., Zhang, A., Akbari, A., Kim, S., Chow, A., Dane, S., OCEAN Challenge Consortium, OTTA Consortium, Huntsman, D. G., Gilks, C. B., Ramus, S., Köbel, M., Karnezis, A. N., Bashashati, A., and Machine Learning-Driven Histotype Diagnosis of Ovarian Carcinoma: Insights from the OCEAN AI Challenge. medRxiv2024. https://doi.org/10.1101/2024.04.19.24306099. UBC Ovarian Cancer Subtype Classification and Outlier Detection (UBC-OCEAN). https://kaggle.com/competitions/UBC-OCEAN, 2023. Kaggle.
