# DVC

# Initialize Git
git init

# Initialize Dvc 
dvc init

#Add repo to store the data
dvc remote add -d local ..\..\remote\

# Add the data to the repo
dvc add diabetes.csv

# Push the data to repo
dvc push

# Create tag
git tag v1.0

# Push Tag
git push --tag

# To switch to specific tag
git checkout v1.0

# To pull the tag
dvc pull
