# Diminutives_CNN_Model 
*A machine learning project aimed at training a model to generate diminutive forms of given nouns.*

A detailed description of the successive stages of joint work on the project, together with the achieved results and conclusions are included in the files **“INL-Projekt-Deminutywy.pdf”** both in Polish and English

---
Brief description:

The project aimed to train a model to generate diminutives for Polish nouns. To accomplish this task, we employed a generative neural network, opting for the T5 model due to its suitability for the task. The specific architecture of the T5 model was selected through trial and error methods, with all models utilized available on the Hugging Face website and compatible with T5. Additionally, Simple Transformers were utilized in the process. Throughout the project, challenges arose, including issues with Polish characters and limited RAM memory in Google Colab. Despite these obstacles, the model achieved an accuracy of over 40% and an F1 score of over 25% when tested on data without Polish characters. However, when considering Polish characters, the accuracy dropped to approximately 33% with an F1 score of around 20%. Moving forward, improvements could be sought by increasing the number of epochs and fine-tuning the learning rate for better results.
