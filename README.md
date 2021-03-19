# CMPT733_DataVoyagers

The 733project directory contains the entire project with its dashboard in Django framework. 
Instruction to run the dashboard are:

Install all the libraries as mentioned in requirements.txt

1. python -m pip install Django //install django
2. Download project_dashboard from gitlab and open it in cmd
3. python manage.py createsuperuser //create superuser
4. python manage.py migrate // migrate to server
4. python manage.py runserver //run the server

Indvidual functionalities are contained within :

1. web_scraping directory - It contains code for scraping of websites.
2. analysis_code - It contains code for article similarity, summary generation, EDA, sentiment analysis, tag generation (LDA-BBC), wordcloud and classification (Random Forest and Support Vector )

All the above files are .ipynb and can be executed directly into jupyter notebook.