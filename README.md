# smart-text-analysis-dj
System Analysis and Design Project - Buali Sina university
## <a href="https://docs.google.com/document/d/1FNOPGcMwcgWNx5GGXCWIE0_kgJKzGjx4ChPE7sT29m4/edit?usp=sharing"> Project Report link </a>
## this project have to main AI parts :
1. sentiment analysis (Persian and english support) 
2. text summarization (Persian and english support) : this Phase is based on Bart model that is a Seq-to-Seq Pre-training model for Natural Language Generation, Translation, and Comprehension . our dataset is cnn_dailymail .
3. Web based Facial Authentication system 
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
