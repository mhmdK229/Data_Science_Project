# Data_Science_Project
Classifying snacks into categories using three tabular datasets and one image dataset.

This project aims to classify food items into categories by using a diverse dataset that includes structured information (e.g., brand, ingredients, nutritional content) and unstructured data, such as product descriptions and images. Techniques applied include text preprocessing, custom feature engineering, and image feature extraction using ResNet18.

To capture the contextual nuances in textual data, BERT was fine-tuned as a deep learning model to enhance classification performance. However, traditional models like XGBoost outperformed BERT in this context, as XGBoost could better leverage structured features in the data. The final model combined structured and unstructured features within an ensemble of XGBoost models, achieving high classification accuracy and showcasing the benefits of model tuning and ensemble learning in handling complex datasets effectively.
