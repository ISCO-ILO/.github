# ISCO Community of Practice (CoP)

Welcome to the ISCO Community of Practice! This space is dedicated to sharing resources, methodologies, and practical insights on automated and assisted coding of occupational information. Below, you'll find details about our activities, including events, objectives, and resources.

---

## **First Webinar of the CoP on Auto/Assisted Coding of Occupations**

### **Date and Time**
- **Date**: December 2, 2024  
- **Time**: 14:00 - 17:30 CET  
- **Mode**: Online  

### **Objectives**
This webinar aims to:
- **Share Knowledge**: Presentations by experts from different countries on their auto-coding systems, methodologies, and lessons learned.
- **Encourage Learning and Collaboration**: Facilitate discussions among participants interested in implementing auto-coding tools.

### **Agenda**

| Time          | Event                                      | Presenter/Moderator                                             |
|---------------|--------------------------------------------|-----------------------------------------------------------------|
| **14:00-14:15** | Opening Remarks                          | Lara Badre, ILO Department of Statistics                       |
| **Session 1** | Moderator: Ng Bin Shen Lucas, Singapore Ministry of Manpower | |
| **14:15-14:35** | Brazil: Automatic Brazilian Classification of Occupations (CBO) Updating ([Presentation Slides](link-to-brazil-slides)) | Enádio da Silva Barbosa, Brazilian Ministry of Labor           |
| **14:35-14:55** | Mexico: AI as a Complementary Methodology for Coding Tasks ([Presentation Slides](link-to-mexico-slides)) | Jose Alejandro Ruiz Sanchez and Jael Pérez Sánchez, INEGI      |
| **14:55-15:15** | Singapore: Adaptable Framework to Automate the Classification of Occupation Codes ([Presentation Slides](link-to-singapore-slides)) | Ng Bin Shen Lucas, Singapore                                   |
| **15:15-15:35** | Discussions                              |                                                                 |
| **15:35-15:45** | Break                                    |                                                                 |
| **Session 2** | Moderator: Shutong Ding, ILO Department of Statistics | |
| **15:45-16:05** | Ecuador: Coding Occupations in the Population and Housing Census ([Presentation Slides](link-to-ecuador-slides)) | Diana Méndez and Victor Espinoza, INEC                         |
| **16:05-16:25** | USA: Autocoding in the Occupational Employment and Wage Statistics Program ([Presentation Slides](link-to-usa-slides)) | Samuel Fincher, U.S. Bureau of Labor Statistics               |
| **16:25-16:45** | ILO: Cross-Mapping Job Titles and Indexes to ISCO-08 ([Presentation Slides](link-to-ilo-slides)) | Shutong Ding, ILO                                              |
| **16:45-17:05** | Discussions                              |                                                                 |
| **17:05-17:15** | Closing Remarks                          | Lara Badre, ILO Department of Statistics                       |

### **Abstracts**

#### **Brazil**
**Presenter**: Enádio da Silva Barbosa, Master in AI, Federal Labor Auditor - Brazilian Ministry of Labor
**Title**: Automatic Brazilian Classification of Occupations (CBO) Updating  
**Abstract**: This project applies Natural Language Processing (NLP) to assist in the process of updating the Brazilian Classification of Occupations (CBO). The CBO contains the coding of occupations that are mainly used for administrative records in Brazil. Today, the updating process occurs through the analysis of different databases searches carried out manually. The whole process is very time-consuming, resulting in overall low response time. Updating the CBO is relevant for society to understand the evolution of occupations. A faster updating process will allow the government to improve public policies, mitigating negative aspects of technological changes and promoting more assertive qualification and requalification actions. This project uses data normalization and vectorization, cosine similarity, TF-IDF cosine similarity and hugging face cosine similarity techniques. Making it possible to assist the analyst and help speed up the analysis process, reducing response time. To achieve this, we intend to use different databases and NLP to allow the model to learn and suggest matches for existing occupations and suggest new ones.

#### **Mexico**
**Presenters**: Jose Alejandro Ruiz Sanchez, Investigador (A) B and Jael Pérez Sánchez, Deputy Director of Classification Standardization and Coding Strategies - Dirección General De Integración Análisis E Investigación (INEGI)
**Title**: Artificial Intelligence as A Complementary Methodology For Coding Tasks  
**Abstract**: Coding tasks in household surveys and census (e.g., National Survey of Occupation and Employment, National Survey of Household Income and Expenditure, Census of Population and Housing) at INEGI are carried out through deterministic computational algorithms and manual processes. For the variables of Occupation and Economic Activity, manual coding represents approximately 20% of the total records. However, this method requires a considerable amount of resources, both human and temporal.
In this context, INEGI has been developing various projects aimed at evaluating the implementation of artificial intelligence algorithms in productive coding processes. The results indicate that it would be possible to reduce the manual workload by 50% without compromising the quality requirements.

#### **Singapore**
**Presenter**: Ng Bin Shen Lucas, Lead Data Scientist- Manpower Research and Statistics Department, Singapore 
**Title**: Adaptable Framework to Automate the Classification of Occupation Codes  
**Abstract**: Having an occupation classification system is crucial for governments to make well-informed decisions about the labor market, enabling them to shape economic policies, education and training pathways, workforce development through reskilling and upskilling more effectively. Many countries rely on the International Standard Classification of Occupations (ISCO) as a backbone and reference for their country’s occupation coding. To address inconsistencies and subjective judgment in manual coding, we developed a framework, allowing you to develop your own occupation classifier that is localised to your own context. Our proposed framework leverages on novel data preprocessing techniques, synthetic data generation, open-source embeddings and a custom neural network architecture. This ensures consistency and provides a scalable solution to meet the demands of rapidly changing job markets.

#### **Ecuador**
**Presenters**: Diana Méndez, Machine learning developer (previously statistical classification specialist) and Victor Espinoza, Software Developer- Instituto Nacional de Estadística y Censos (INEC)
**Title**: Coding occupations in the Population and Housing Census of Ecuador using machine learning techniques  
**Abstract**: Statistical offices carry out a process called coding to convert textual responses into numerical codes. Traditionally, coding has been done manually by trained individuals. Manual coding usually takes a long time for execution and supervision due to the variety and volume of textual responses. In order to improve and automate the coding of occupations for the 2022 Census of Ecuador, we developed and implemented classification models using natural language processing and machine learning techniques.
We tested XGBoost, Feedforward Neural Networks (FNN), and LSTM algorithms for classifying occupations. The best performing model, considering accuracy and processing time, was the FNN. As result, we obtained a model with an accuracy of 87.82%. In practice, a user-friendly web system was deployed using the designed model. Approximately 5.4 million cases were coded in about 6.9 hours. Subsequently, codes with low predictive probabilities were identified, and these were coded using other methods.

#### **USA**
**Presenter**: Samuel Fincher, Branch Chief, Occupational Analytics and Classification, Occupational Employment and Wage Statistics - U.S. Bureau of Labor Statistics
**Title**: Autocoding in the U.S. Occupational Employment and Wage Statistics (OEWS) Program  
**Abstract**: This presentation will cover methods of occupational autocoding used in the OEWS program at the U.S. Bureau of Labor Statistics. OEWS data collection and input fields play a large role in the autocoding process. This presentation will provide information related to model selection, model training, and validation techniques. In addition, steps used to ensure quality SOC code application will also be discussed.

#### **ILO**
**Presenter**: Shutong Ding, Statistical Knowledge Management Officer - ILO Department of Statistics  
**Title**: Cross-Mapping Job Titles and Indexes between National Occupational Classifications and ISCO-08  
**Abstract**: The ILO is exploring technological advancements and new data sources for potential future modernization of the revision of ISCO and ensure its accuracy and relevance. This includes leveraging natural language processing (NLP) and machine learning techniques to analyze and classify emerging job titles and occupations found in online job advertisements (OJAs) and recently updated National Occupational Classifications (NOCs). This presentation introduces a comprehensive framework for mapping NOC occupational and index titles to ISCO-08, supporting consistent “coding” of NOC entries to ISCO and identifying necessary amendments for ISCO's revision.
To facilitate extensive analysis of recently updated NOCs across different languages and volumes, the latest LLMs and vector search are being tested to enable automated mapping. While this project is still ongoing, the presentation will discuss the technical strategies used and the challenges encountered, sharing insights from the learning process.

---

## **Resources**
- [Presentation Slides](#) (Coming Soon)
- [Related Links](https://ilostat.ilo.org/methods/concepts-and-definitions/classification-occupation/)    

---

## **Contact Information**
- **Lara Badre**: [badre@ilo.org](mailto:badre@ilo.org)  
- **Shutong Ding**: [ding@ilo.org](mailto:ding@ilo.org)  
