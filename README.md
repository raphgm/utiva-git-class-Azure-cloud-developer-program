## utiva-git-class-Azure-cloud-developer-program
###  Training to introduce the cohort on how to push from their local environment to github
Downloaded Gitbash (https://git-scm.com/downloads)
## configure  gitbash
git config --global user.name "name"  
git config --global user.email "email"  
## Work with the configured environment
mkdir website  
cd website 
git init
touch index.html
## Clone your github repo
git remote add origin <url>    
this should be the url from your created repo(use https) 
## Push to GitHub
git add index.html  
git commit -m "Create index.html"  
git push origin master  
