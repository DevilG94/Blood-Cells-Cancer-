#                   Blood Cells Cancer (Acute Lymphoblastic Leukemia) Detection with Pretrained Models using Attention Mechanism

Most blood cancers, also called hematologic cancers, start in the bone marrow, where blood cells are produced. Blood cancers occur when abnormal blood cells grow out of control, interfering with the function of normal blood cells, which fight off infection and produce new blood cells.

## Types of Blood Cancer: -
The three main types of blood and bone marrow cancer are Leukemia, Lymphoma and Myeloma.
•	Leukemia  This is the most common blood cancer in the United States and the most common cancer among children and teenagers. The five-year survival rate has quadrupled over the past 40 years. Types of Leukemia include Acute Lymphoblastic Leukemia (ALL), Acute Myeloid Leukemia(AML), Chronic Lymphocytic Leukemia (CLL) and Chronic Myelogenous Leukemia (CML).
•	Lymphoma  This is the cancer of your lymphatic system, which includes your bone marrow. The survival rate has doubled over the past 40 years. Types of lymphoma include Hodgkin lymphoma, non-Hodgkin lymphoma, Waldenstrom macroglobulinemia, follicular lymphoma, B-cell lymphoma and cutaneous T-cell lymphoma.
•	Myeloma  This is the cancer that starts in your bone marrow and affects your plasma cells. Multiple myeloma is the most common myeloma type. More than half of people diagnosed with Myeloma are alive five years after diagnosis. Other types of myeloma include Plasmacytoma and Amyloidosis.

## Causes of Blood cancer: -
Researchers know blood cancer happens when blood cell DNA changes or mutates, but they aren’t sure why this happens. Your DNA tells cells what to do. In blood cancer, DNA tells blood cells when to grow, when to divide or multiply and/or when to die.
When DNA gives your cells new instructions, your body develops abnormal blood cells that grow and multiply faster than normal and sometimes live longer than normal. When that happens, normal blood cells become lost in an ever-growing horde of abnormal cells that crowd your normal cells and monopolize space in your bone marrow.
Eventually, your bone marrow produces fewer normal cells. That means there aren’t enough normal cells available to do their essential tasks: carrying oxygen through your body, fighting infection and controlling bleeding. Here’s how genetic change may cause the three blood cancer types:
•	Leukemia: Researchers think leukemia happens when a combination of environmental and genetic factors triggers DNA changes. In this case, researchers think changes in chromosomes may trigger DNA changes. Chromosomes are strands of DNA. When cells divide and make two new cells, they copy these DNA strands. Sometimes, genes from one chromosome switch to another chromosome. In leukemia, this switch may affect a set of genes that help cells grow and another set of genes that suppress tumors. Researchers believe exposure to high levels of radiation or certain chemicals plays a role in the genetic changes that cause leukemia.
•	Lymphoma: Lymphoma happens when there’s a change in genes in white blood cells, called lymphocytes, that causes them to multiply uncontrollably. In addition, abnormal lymphocytes don’t die when normal lymphocytes die. Again, researchers don’t know what triggers the genetic change, but research shows certain infections or having a depressed immune system may be factors.
•	Myeloma: In this case, plasma cells in your bone marrow get new genetic instructions that make them multiply. Researchers are investigating potential links between myeloma and chromosomal change that affect genes that control plasma cell growth.

## Symptoms of Blood cancer: -
Blood cancer symptoms vary based on blood cancer type, but there some symptoms all three have in common:
•	Fatigue: This is feeling so tired you can’t manage your daily activities. You may also feel weak.
•	Persistent fever: A fever is a sign your body is fighting infection or responding to abnormal cancer cells.
•	Drenching night sweats: This is sweating that comes on suddenly while you’re sleeping, disturbing your sleep and drenching your bedding and clothes.
•	Unusual bleeding or bruising: Everyone has bumps, bruises and injuries that make us bleed. Unusual bleeding or bruising is bleeding that doesn’t stop and bruises that don’t heal after two weeks.
•	Unexpected or unexplained weight loss: Unexpected weight loss of 10 pounds over a six- to 12-month period is considered unexplained weight loss.
•	Frequent infections: Frequent infections may be a sign something is affecting your immune system.
•	Swollen lymph nodes or an enlarged liver or spleen: These symptoms may be signs of leukemia or lymphoma.
•	Bone pain: Myeloma and leukemia may cause bone pain or tender spots on your bones.
Many blood cancer symptoms are similar to other less serious illnesses’ symptoms. Having any of these symptoms doesn’t mean you have blood cancer. But you should contact your healthcare provider when you notice symptoms or changes in your body that last more than a few weeks.
#                                                                            PROJECT OVERVIEW
In this project it is explored that the Blood Cells Cancer (ALL) dataset for Acute Lymphoblastic Leukemia (ALL) detection.
The dataset, which contains 3242 Peripheral Blood Smear (PBS) images from 89 (Eighty Nine) patients, aims to improve the Accuracy of ALL (Acute Lymphoblastic Leukemia) diagnosis using non-invasive image analysis techniques. It includes two main categories – Benign and Malignant, with the Malignant category further divided into Early Pre-B, Pre-B and Pro-B subtypes.
The diagnosis of ALL (Acute Lymphoblastic Leukemia) is a complex and expensive process.
Using PBS images for initial screening has become increasingly important, but manual diagnosis is prone to errors du to the non-specific nature of ALL signs. This project aimed to develop a Machine Learning model to assist in more accurate and efficient ALL diagnosis, mitigating human error.

## Key Highlights of Project: -
(1)	Data: -
•	3242 PBS Images of Blood cells from 89 patients suspected of ALL (Acute Lymphoblastic Leukemia)
•	Images were captured using a Zesiss camera at 100x magnification and saved as JPG files.
(2)	Modeling: -
•	In this project explored InceptionV3, Xception and MobileNet architectures, all enhanced with Attention Mechanisms.
•	These models showed strong performance in multi-class classification tasks, with Xception and MobileNet achieving 92% and 98% Accuracy.
•	InceptionV3 achieved 97% Accuracy, showing strong Precision & Recall.
Results: -
## Performance Metrics: After training and evaluating both models, I achieved promising results –
### 1)	InceptionV3  Precision: [0.93, 0.99, 0.97, 0.99]; Recall: [0.99, 0.99, 1.00, 0.90]; F1-Score: [0.96, 0.99, 0.98, 0.94]; Accuracy = 97%
### 2)	Xception  Precision: [0.94, 0.85, 0.91, 1.00]; Recall: [0.96, 0.99, 1.00, 0.71]; F1-Score: [0.95, 0.92, 0.95, 0.83]; Accuracy = 92%
### 3)	MobileNet  Precision: [1.00, 0.96, 0.99, 0.99]; Recall: [1.00, 0.99, 0.99, 0.96]; F1-Score: [1.00, 0.97, 0.99, 0.97]; Accuracy = 92%
Models performed exceptionally well Precision, Recall and F1-Score achieving results as high as 0.99 or 99% in some classes.
The attention mechanism significantly boosted the model’s ability to distinguish between 
Malignant and Benign Cells, improving overall diagnostic Accuracy

## Tech Stack: -
•	TensorFlow and Keras for model building and training.
•	Attention Mechanisms to enhance feature extraction and model accuracy
•	Data Preprocessing and Augmentation for better generalization

## Conclusion: -
This project has provided valuable insights into the potential of Machine Learning in Medical diagnostics and I’m excited about the feature possibilities for AI-driven solutions in Healthcare.
