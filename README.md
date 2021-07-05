# Install Flask 
py -m pip install Flask

# Create the app.py
touch app.py
# Create the env.py
touch env.py

# Ensure that env.py is added to .gitignore

# Deploying to Heroku
## Create the requirements.txt file
py -m pip freeze --local > requirements.txt

## Create the Procfile
echo web: python app.py > Procfile