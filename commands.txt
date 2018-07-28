#Setup Username and Email
git config --global user.name "Haris Ali Khan"
git config --global user.email harisalikhan13@gmail.com

#Add remote origin
git remote add origin git@bitbucket.org:haris989/flaskapp-codewithharry.com.git

#Stage your changes commit and push
git add -A

#Commit your changes
git commit -m "commit message"

#Push your changes
git push -u origin master
