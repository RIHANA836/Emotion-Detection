## Decoding Emotions: Deep Learning for Malayalam Text Analysis  
As part of my BTech academics, I developed a project that classifies Malayalam social media comments by emotion. The project involves text preprocessing, NLP techniques, and machine learning models. The dataset was manually collected from various social media platforms, and the models were trained to achieve accurate emotion detection.

---

#### Overview
This project focuses on building a deep learning model to detect emotions in Malayalam text from social media comments. Malayalam, being a low-resource language, poses unique challenges for building efficient emotion detection models. The project delves into understanding nuanced emotions such as happiness, sadness, sarcasm, and abuse from social media comments. The work aims to address the challenges of emotion detection in low-resource languages by employing advanced Natural Language Processing (NLP) techniques.
Key highlights include:
- Categorizing emotions into primary categories (Happy, Sad, Neutral) and detailed categories (Affection, Sarcasm, Abusive, etc.).
- Exploring traditional machine learning and deep learning models for emotion detection.
  
#### Objective  
The primary goal of this project is to develop a deep learning-based system capable of detecting emotions in Malayalam comments, advancing beyond traditional sentiment analysis. The study focuses on:  
1. Building a dataset of Malayalam text.  
2. Categorizing emotions into both broad (Happy, Sad, Neutral) and detailed classes (Abuse, Affection, Sarcasm, etc.).  
3. Evaluating various machine learning and deep learning models for emotion detection.  

#### Methodology  
##### Data Collection and Preprocessing  
- Collected **10,000 comments** from social media platforms like YouTube, Facebook, and Instagram.  
- Cleaned the data by removing English characters, digits, and special symbols.  
- Labeled emotions using a majority voting approach from three annotators.  
- Split the dataset into 80% training and 20% testing data.  

##### Feature Extraction  
- **Word2Vec** embeddings to capture semantic meaning.  
- **TF-IDF** vectorization for Naive Bayes and SVM models.  

##### Model Development  
- Implemented three models:  
  - **Naive Bayes**: Accuracy - 54%  
  - **SVM**: Accuracy - 54.5%  
  - **LSTM**: Accuracy - 59.5%  
- Conducted classification for:  
  1. Primary emotions: Happy, Sad, Neutral.  
  2. Ten specific emotions: Affection, Anger, Sarcasm, etc.  

##### Model Assessment  
- Emphasized the importance of feature representation techniques.  
- Used **BERT** for initial experiments, achieving an accuracy of 87% on a small sample.  

#### Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
  - `TensorFlow`, `Keras` for deep learning.  
  - `scikit-learn` for machine learning models.  
  - `NumPy`, `Pandas` for data manipulation.  
  - `Matplotlib`, `Seaborn` for visualization.  
- **Feature Extraction**: Word2Vec, TF-IDF  

#### Results  
1. **BERT** achieved the highest accuracy of **87%** with five emotions on a small dataset.  
2. **LSTM with Word2Vec** embeddings showed the best performance among traditional models, with an accuracy of **59.5%**.  
3. Simplifying classification into three primary emotions improved accuracy compared to ten detailed emotions.  
4. Results underscore the need for better resources and tools for low-resource languages like Malayalam.  

#### Conclusion  
This project demonstrates the feasibility and challenges of emotion detection in Malayalam text, especially with limited linguistic resources. By leveraging deep learning and feature extraction techniques, it contributes to advancing regional language processing and sets the stage for future improvements in NLP for low-resource languages.  

#### Acknowledgments  
- Project Guide: Ms. Abeera VP
- Team Members: Farsana P I, Natha M Iqbal, Rihana Iqbal, Shirin A S
- Special thanks to all researchers and contributors to the field of NLP and emotion detection.





