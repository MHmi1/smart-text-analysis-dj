# smart-text-analysis-dj
System Analysis and Design Project - Buali Sina university
## <a href="https://docs.google.com/document/d/1FNOPGcMwcgWNx5GGXCWIE0_kgJKzGjx4ChPE7sT29m4/edit?usp=sharing"> Project Report link </a>

##✅ Project Overview

This project encompasses four main AI components:

1. ✅ **Sentiment Analysis** (Supports Persian and English):
   - **Model:** LSTM Neural Network 
   - **Dataset:** IMDB 50K Movie Reviews
   - **Description:** Implements a CNN-based model to classify sentiments in movie reviews, supporting both Persian and English languages.

2.✅ **Text Summarization** (Supports Persian and English):
   - **Model:** BART (Bidirectional and Auto-Regressive Transformers)
   - **Dataset:** CNN/DailyMail
   - **Description:** Utilizes the BART sequence-to-sequence pre-training model for generating concise summaries of lengthy texts in both Persian and English.

3.✅ **Image Retrieval System**:
   - **Model:** VGG16 Deep Neural Network
   - **Description:** Employs the VGG16 model to extract features from images, facilitating efficient image retrieval based on content similarity.

4.✅ **Spam SMS/Email Detection**:
   - **Model:** Ensemble Learning combining:
     - Multinomial Naive Bayes (`MultinomialNB()`)
     - Linear Support Vector Classification (`LinearSVC()`)
     - Decision Tree Classifier (`DecisionTreeClassifier()`)
   - **Accuracy:** Achieved 98.5% accuracy
   - **Description:** Detects spam messages by leveraging an ensemble of classifiers to enhance detection accuracy.

downlaod model :
<p><a href="https://drive.google.com/file/d/13QmMsfNwvm6U4asXd6gurvSkl3nbuIEL/view?usp=drive_link"> english sentiment analysis model link (imdb dataset)</a>  </p>
<p><a href="https://drive.google.com/file/d/1T3IXeqAld5d6xq1Qq6DMsqXkvNzviYFc/view?usp=sharing"> persian sentiment analysis model link (digikala dataset) </a>  </p>
<p><a href="https://drive.google.com/file/d/10EZapoHN0lJ2MTZDTI6qS04ta0h0P9Bx/view?usp=sharing"> english text summarization model link (cnn-dailymail dataset) </a>  <p><a href="https://drive.google.com/file/d/1sESyT11mTa2pI4PT4vMqVufeC1NE2s45/view?usp=sharing"> english spam detection model link  </a>

<a href="https://www.aparat.com/v/zliNs" > AI part technical report video</a> 

## Charts
plots of persian sentiment analysis model 
<img src="https://s8.uupload.ir/files/per-sen-model-chart_0jbt.png" width="750" height="330" > 

plots of english sentiment analysis model 
<img src="https://s8.uupload.ir/files/sen-ana-en-plt_n12z.png" width="750" height="330" > 

## image retrieval output result :
<img src="https://s8.uupload.ir/files/run_prj_b8n.png" >
## Installation

```bash
    $ cd smart-text-analysis
    $ python -m venv venv
    $ source venv/Scripts/activate
    (venv) pip install -r requirements.txt
    (venv) python manage.py makemigrations
    (venv) python manage.py migrate
    (venv) python manage.py runserver
```
