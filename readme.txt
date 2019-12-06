# Clone your repositorie 
git clone git@github.com:[Your_Account]/[Your_Repo].git

# Go in your repo folder
cd [Your_Repo].git

# Remove git files with the commits history
rm -rf .git

# Create a repo localy with the unique commit
git init
git add .
git commit -m "[Name_Of_Your_Commit]"

# Push to Github with your unique commit to your branch master
git remote add origin git@github.com:[Your_Account]/[Your_Repo].git
git push -u --force origin master
