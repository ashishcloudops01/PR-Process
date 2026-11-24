# PR-Process
How PR created and approve and merge by the lead/manager in organization.


Step 1: Clone the repository
https://github.com/ashishcloudops01/PR-Process.git
cd PR-Process

Step 2: Check existing branches
git branch

Step 3: Create a feature branch
git checkout -b feature/add-homepage

Step 4: Create a sample file in local and save 

Step 5: Check changes
git status

Step 6: Add and commit changes
git add index.html
git commit -m "first commmit"

Step 7: Push the feature branch to GitHub
git push -u origin feature/add-homepage


Developer – Create Pull Request

On GitHub:
1. Open the devops-demo repository.
2. Click Pull requests.
3. Click New pull request.
4. Select the branches:
   - Base: main
   - Compare: feature/add-homepage
5. Click Create pull request.
6. Add the title: Added homepage.
7. Add description: Created a new homepage using HTML.
8. Assign the Team Lead as reviewer.
9. Click Create pull request.

Team Lead/Manager – Review and approve PR
Now log in using the Team Lead account.
1. Open the repository.
2. Click Pull requests.
3. Open the developer's PR.
4. Click Files changed.
5. Review the HTML code.
6. Click Review changes.
7. Select Approve.
8. Add a comment: Code reviewed and approved.
9. Click Submit review.


Team Lead/Manager – Merge the PR
After approval:
1. Open the PR.
2. Scroll down to the merge section.
3. Click Merge pull request.
4. Click Confirm merge.
5. Verify that the PR status shows Merged.


Real-time GitHub workflow
1. Developer creates feature branch
   
   git checkout -b feature/login
2. Developer writes code
   
   Modifies application files.
3. Developer commits changes
   
   git add . → git commit
4. Developer pushes code
   
   git push origin feature/login
5. Developer creates Pull Request
   
   feature/login → main
6. Team Lead reviews code
   
   Checks Files changed and provides feedback.
7. Team Lead approves PR
   
   Selects Approve.
8. Team Lead merges PR
   
   Merges changes into main.
9. Developer pulls latest code
   git pull origin main

