Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)

My name is Daniil
===============================================================================================================================

ML Engineer
-----------

I'm a beginner Machine Learning Engineer passionate about building and training deep learning models.

I’m actively exploring modern approaches in computer vision, NLP, and generative models.

I have hands-on experience developing and tuning neural networks in \*\*Python\*\* using

TensorFlow, Keras, PyTorch, OpenCV, scikit-learn, and XGBoost.

I’ve worked on several pet projects, including image classification, text analysis,

and implementing a RAG (Retrieval-Augmented Generation) architecture.

I’m looking for opportunities to apply my skills to real-world problems and grow in the fields of

machine learning and MLOps.

* 🌍  I'm based in Russia, Ulyanovsk
* ✉️  You can contact me at [daniilkarcev767580@gmail.com](mailto:daniilkarcev767580@gmail.com) and [Telegram](https://t.me/DanKrzv)
* 🧠  I'm currently learning I’m currently learning new skills in machine learning and deep learning.


### Socials

<p align="left"> <a href="https://www.github.com/DKartsev" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" alt="GitHub" title="GitHub" /> </picture> </a></p>
### Badges

<b>My GitHub Stats</b>

<a href="http://www.github.com/DKartsev"><img src="https://github-readme-stats.vercel.app/api?username=DKartsev&show_icons=true&hide=&count_private=true&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&show_icons=true" alt="DKartsev's GitHub stats" /></a>



## 📝 My Learning Projects

### 🖼 Computer Vision

#### 🐶 Classification of Dog Breeds using EfficientNetV2B0
A deep learning project for **classifying dog breeds** using the **pre-trained EfficientNetV2B0** model.  
- Dataset: **Stanford Dogs Dataset** (120 dog breeds)  
- Training strategy:  
  1. Train top layers with the base model frozen  
  2. Fine-tune top layers after unfreezing for higher accuracy  
- Implemented in **Google Colab** using **Keras 3.10**

#### 🐱 Cat and Dog Image Classification Using MobileNet
A CNN project for **classifying images of cats and dogs** using the **pre-trained MobileNet** model.  
- Dataset: split into training, validation, and test sets  
- Techniques: **image augmentation** to improve generalization  
- Achieves **high accuracy** and performs well on new data  

#### 🕶 Glasses Overlay with Focus Blur
A computer vision project for **overlaying glasses on faces with background blur**.  
- Face and eye detection using **OpenCV**  
- Creates a **mask for the face** and blurs background while keeping eyes in focus  
- Overlays glasses with **semi-transparent lenses**  
- Visualizes the final result in **Google Colab**

#### ✍ Handwritten Letters Classification
Recognition of **handwritten English letters (A–Z)** using a fully connected neural network.  
- Dataset: 28×28 pixel images of handwritten letters  
- Implemented in **Keras**  
- Evaluated accuracy on test set

---

### 📝 Natural Language Processing (NLP)

#### 🎬 IMDB Movie Reviews Classifier
A text classification project for **binary sentiment analysis** (positive/negative) on IMDB reviews.  
- Uses **transformers** (RoBERTa/BERT/DeBERTa) with **Trainer** API  
- Includes **data preparation, tokenization, training with early stopping, evaluation, checkpointing, and exporting predictions**  
- Easy to switch model parameters (e.g., `deberta-v3-small`) for experiments  

#### 📰 Fake News Detector
ML project to detect **fake vs real news**.  
- Text processing using **TF-IDF**  
- Classification with **PassiveAggressiveClassifier**  
- Comparison of different models, visualization of metrics  
- Achieved **accuracy >90%**  
- Dataset: **Twitter Sentiment Dataset** (`text`, `label`)  
- Technologies: Python, pandas, scikit-learn, matplotlib, seaborn

#### 🤖 RAG Service Architecture Implementation
Implementation of **Retrieval-Augmented Generation (RAG)** for text generation.  
- Retrieval: searches relevant information in a knowledge base  
- Augmented: supplements context for LLM  
- Generation: produces answers based on retrieved data  
- Benefits: accuracy, freshness, transparency, and controllable knowledge

---

### ⚡ Other / ML Applications

#### 🧪 Parkinson's XGBoost Classifier
A **binary classification project** for predicting Parkinson's disease based on biomedical voice features.  
- Data from **UCI Machine Learning Repository**  
- Steps: data loading, preprocessing, normalization, train-test split  
- Model: **XGBoost**  
- Evaluated performance with accuracy and metrics

#### 🎯 TestQuizBot
Telegram **quiz bot** with intelligent interface and scoring system.  
- 10 engaging questions with multiple choices  
- Score calculation and participant statistics  
- Ability to retake quizzes  
- Interactive and adaptive inline buttons with emojis  
