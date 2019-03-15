# Homwork-Belly-Button-Biodiversity

The objective for this project was to build an interactive web application to explore the Belly Button Biodiversity Data Set and deploy on Heroku.

here is the link to the app
https://tranquil-ocean-27189.herokuapp.com/ 

added dependencies : 
conda deactivate/
conda create -n plotly_env python=3.6/
conda activate plotly_env/
pip install gunicorn/
pip install psycopg2/
pip install flask/
pip install pandas/
pip install flask-sqlalchemy/
pip freeze > requirements.txt (or) pip install -r requirements.txt/
sh run.sh/
echo "web: gunicorn app:app" > Procfile/
git add Procfile/
web: gunicorn app:app

