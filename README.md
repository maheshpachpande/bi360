## create the vitual environment
- conda create -n bi360 python=3.9 -y
- conda activate bi360

## create the requirements.txt file and enter the name of libraries
- pip install - r requirements.txt

## create and first commit in GitHub
echo "# bi360" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/maheshpachpande/bi360.git
git push -u origin main

## or push an existing repository from the command line
git remote add origin https://github.com/maheshpachpande/bi360.git
git branch -M main
git push -u origin main

## create the SQL connection ipynb file
## setting up the SQL connection