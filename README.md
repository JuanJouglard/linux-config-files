# Initialize an empty Git repository
git init

# Add the remote repository
git remote add origin git@github.com:JuanJouglard/linux-config-files.git

# Fetch the data for the specific branch you want
git fetch origin home

# Checkout the branch into the current directory
git checkout -b home origin/home

# Pull the latest changes from the remote branch
git pull origin home
