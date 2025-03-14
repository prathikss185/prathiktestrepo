To execute all the 12 steps mentioned above using the provided source repository (https://github.com/prathikss185/prathiktestrepo.git), here's a detailed guide step by step. I'll assume you already have Git installed and GitHub access. If not, you can download Git from here, and you'll need a GitHub account.
Step 1: Fork the Repository
1.	Go to the repository on GitHub: prathiktestrepo.
2.	In the top-right corner of the repository page, click the Fork button.
3.	This will create a fork of the repository under your GitHub account.
________________________________________
Step 2: Clone the Repository to Your Local Machine
1.	After forking, you'll be redirected to your forked repository on GitHub.
2.	On the main page of your forked repository, click the green Code button.
3.	Copy the URL provided (either HTTPS or SSH based on your preference). The HTTPS URL will look like this:
4.	https://github.com/YOUR_USERNAME/prathiktestrepo.git
5.	Open your terminal/command prompt and run the following command to clone your forked repository to your local machine:
6.	git clone https://github.com/YOUR_USERNAME/prathiktestrepo.git
7.	Navigate into the cloned repository folder:
8.	cd prathiktestrepo
________________________________________
Step 3: Create a Branch for the Feature
1.	Before making any changes, create a new branch for the feature you're going to work on (e.g., feature/login): 
2.	git checkout -b feature/login
3.	This command creates a new branch and switches to it, so all changes will be tracked separately from the main branch.
________________________________________
Step 4: Make Changes and Commit Them
1.	Now, open the repository folder in your preferred code editor and make changes for your feature. Let's assume you added some basic code for the login functionality (e.g., a simple login page or feature).
2.	After making changes, check the status of the files:
3.	git status
4.	Add the modified files to the staging area:
5.	git add .
This stages all the changes made to the files.
6.	Commit the changes with a descriptive message:
7.	git commit -m "Added basic login functionality"
________________________________________
Step 5: Pull the Latest Changes from the Original Repository
1.	If others have made changes to the original repository (before you push), you should pull those changes to stay updated.
2.	First, you need to add the original repository as a remote to fetch updates from it: 
3.	git remote add upstream https://github.com/prathikss185/prathiktestrepo.git
4.	Now, pull the latest changes from the original repository: 
5.	git pull upstream main
6.	If there are any merge conflicts, you'll need to resolve them manually before proceeding.
________________________________________
Step 6: Push Your Changes to GitHub
1.	Push the changes you've committed on your local branch (feature/login) to your forked repository on GitHub: 
2.	git push origin feature/login
________________________________________
Step 7: Create a Pull Request (PR)
1.	Go to your forked repository on GitHub (e.g., https://github.com/YOUR_USERNAME/prathiktestrepo).
2.	You’ll see a notification offering to Compare & pull request. Click it.
3.	GitHub will show a comparison between your feature/login branch and the original repository’s main branch.
4.	Write a brief description of what you've done (e.g., "Implemented login feature").
5.	Click Create pull request to submit your changes for review.
________________________________________
Step 8: Review and Discuss the Pull Request
1.	If the repository owner or collaborators review your pull request, they may leave comments, such as suggesting changes or reporting bugs.
2.	In the Conversation tab, they might leave a comment like "There’s an issue with the login form validation. Can you fix that?"
3.	Make the requested changes in your local branch and then commit them:
4.	git add .
5.	git commit -m "Fixed login validation issue"
6.	git push origin feature/login
7.	The pull request will automatically update with the new changes.
________________________________________
Step 9: Merge the Pull Request
1.	Once the pull request is reviewed and approved, the repository owner (or you, if you have write access) will merge it into the main branch.
2.	To merge the pull request, click on Merge pull request and then confirm it by clicking Confirm merge.
________________________________________
Step 10: Create a Release
1.	Once the changes are merged into the main branch, you can create a Release.
2.	Go to the Releases tab of the original repository.
3.	Click Draft a new release.
4.	Choose a version tag (e.g., v1.0), and write a changelog summary (e.g., "Added login feature").
5.	Click Publish release.
________________________________________
Step 11: Update the README File
1.	Open the README.md file of your forked repository.
2.	Add any information about the new feature (e.g., "This project now includes a login feature").
3.	After updating, commit the changes to the README: 
4.	git add README.md
5.	git commit -m "Updated README to include login feature details"
6.	git push origin feature/login
________________________________________
Step 12: Collaborators and Contributors
1.	If you want to add collaborators to your repository for future development, go to your repository's Settings on GitHub.
2.	In the left sidebar, click Collaborators & teams.
3.	You can then search for users by their GitHub username and grant them access as collaborators.
________________________________________
Summary of Commands:
•	Clone repo: git clone https://github.com/YOUR_USERNAME/prathiktestrepo.git
•	Create branch: git checkout -b feature/login
•	Commit changes: git commit -m "Added basic login functionality"
•	Pull updates: git pull upstream main
•	Push changes: git push origin feature/login
•	Create PR: Create a pull request on GitHub.
•	Merge PR: Merge the pull request in GitHub after review.
•	Create release: Draft and publish a release in the GitHub repository.
•	Update README: Modify the README file and push changes.
•	Add collaborators: Add collaborators through GitHub's settings page.
________________________________________
That’s it! You've successfully walked through all 12 steps for using Git and GitHub. Let me know if you need any further assistance with any of the steps!
