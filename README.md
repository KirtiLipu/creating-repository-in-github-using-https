#creating-repository-in-github-using-https

mkdir creating-repository-in-github-using-https
cd creating-repository-in-github-using-https
echo "# creating-repository-in-github-using-https" >> README.md (Optional, Any file can create)
git init
git add README.md
git commit -m "first commit"
git branch -M main

#Creating a GitHub repository
	Go to github.com and log into your account
	Click on the New button to create a new repository

#Adding a remote repository using the HTTPS URL
#Copy the HTTPS URL from the newly created repository
#Open the Terminal on the local machine and use the following command to add a remote repository:
	   git remote add origin <Your HTTPS_URL>
#Replace HTTPS_URL with the copied URL
	Execute the git remote -v command to check remote repository

#Pushing the changes in the local repository to GitHub
git push -u origin main
