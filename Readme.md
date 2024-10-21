sequence of github

1.
Open Terminal and navigate to your project directory:

bash
Copy code
cd /path/to/your/project

2.
Initialize a Git Repository (if not already done):

bash
Copy code
git init

3.
Add Files to Staging Area:

bash
Copy code
git add index.html style.css
Or to add all files:

bash
Copy code
git add .

4.
Commit the Changes:

bash
Copy code
git commit -m "Add index.html and style.css"

5.
Connect to Your GitHub Repository:

bash
Copy code
git remote add origin git@github.com:username/repository.git

6.
Push Changes to GitHub:

bash
Copy code
git push -u origin master
(Use main instead of master if your default branch is named main.)


after this we can also git push   to push anything to github