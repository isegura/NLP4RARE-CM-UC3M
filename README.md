# NLP4RARE-CM-UC3M
This repository contains the dataset RareDis, which is described in detail in the paper:

Martínez-deMiguel, C., Segura-Bedmar, I., Chacón-Solano, E., & Guerrero-Aspizua, S. (2022). The RareDis corpus: a corpus annotated with rare diseases, their signs and symptoms. Journal of Biomedical Informatics, 125, 103961.

The RareDis corpus contains more than 5,000 rare diseases and almost 6,000 clinical manifestations are annotated. 
The entities (disease, rare disease, symptom, sign and anaphor) and the relationships (produces, is a, is acron, is synon, increases risk of, anaphora) were annotated. 
The previous paper describes the selection of 1,041 texts to be included in the corpus, the annotation process and the annotation guidelines. 
The RareDis corpus consists of texts taken from the rare disease database (https://rarediseases.org/rare-diseases/), created and maintained by the National Organisation for Rare Diseases (NORD). This database contains detailed information about more than 1,200 rare diseases. For each rare disease, the database provides a text organised in the following sections: general discussion, signs and symptoms, causes, affected populations, related disorders, diagnosis, standard therapies, investigational therapies, NORD member organisations and other organisations. We used the seven first sections of each text. To download all the information related to rare diseases, we performed web scraping. This is the process of extracting data from a website by using an automated program. To do this, we developed a Python script based on the use of the Beautiful Soup library, obtaining a total of 1,041 English texts. To obtain these texts, please send an email to isegura@inf.uc3m.es, and she will help you to get them. 

The Inter Annotator Agreement evaluation shows a relatively high agreement (F1-measure equal to 83.5% under exact match criteria for the entities and equal to 81.3% for the relations). This corpus is of high quality, supposing a significant step for the field since there is a scarcity of available corpus annotated with rare diseases. This could open the door to further NLP applications, which would facilitate the diagnosis and treatment of these rare diseases and, therefore, would improve dramatically the quality of life of these patients.

Please, if you use this dataset, remember to cite our papers: 

Martínez-deMiguel, C., Segura-Bedmar, I., Chacón-Solano, E., & Guerrero-Aspizua, S. (2022). The RareDis corpus: a corpus annotated with rare diseases, their signs and symptoms. Journal of Biomedical Informatics, 125, 103961.

Segura-Bedmar, I., Camino-Perdones, D., & Guerrero-Aspizua, S. (2022). Exploring deep learning methods for recognizing rare diseases and their clinical manifestations from texts. BMC bioinformatics, 23(1), 263.

