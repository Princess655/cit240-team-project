\# CIT 240 GitHub Collaboration Workflow



\## Project Description



This document explains the Git and GitHub collaboration process followed by our five-member group for the CIT 240 Team Project.



\## Group Members and Responsibilities



\- Member A: Princess Mae V. Linobo - Homepage (index.html)

\- Member B: Pia Mae Dagum - Team Profile (team.md)

\- Member C: Imee Grace Gascon - Setup Instructions (README.md)

\- Member D: Ilykca Bim Cayanan - Collaboration Workflow (workflow.md)

\- Member E: Jan Owenz Labarosa - Testing Report (testing.md)



\## Step 1: Clone the Repository



Each member uses a separate project folder and clones the shared repository using Git Bash.



&#x20;   git clone https://github.com/Princess655/cit240-team-project.git

&#x20;   cd cit240-team-project



\## Step 2: Update the Main Branch



Before making changes, each member updates their local repository.



&#x20;   git switch main

&#x20;   git pull --ff-only origin main



\## Step 3: Create a Feature Branch



Each member creates a branch for their assigned task instead of editing main directly.



&#x20;   git switch -c feature/collaboration-notes



\## Step 4: Edit the Assigned File



Each member creates or updates their assigned file using a text editor and saves the changes.



\## Step 5: Stage and Commit Changes



Members check their changes and create a meaningful commit.



&#x20;   git status

&#x20;   git add workflow.md

&#x20;   git commit -m "Add GitHub collaboration workflow"



\## Step 6: Push Changes to GitHub



Members push their feature branches to the shared repository using their own GitHub accounts.



&#x20;   git push -u origin feature/collaboration-notes



\## Step 7: Create a Pull Request



1\. Open the shared GitHub repository.

2\. Click Compare \& pull request.

3\. Set base to main and compare to the feature branch.

4\. Add a title and description of the changes.

5\. Click Create pull request.

6\. Request the assigned reviewer.



\## Step 8: Review the Pull Request



1\. The reviewer opens the pull request.

2\. Click Files changed and inspect the changes.

3\. Leave a meaningful review comment.

4\. Approve the pull request if the changes are correct, or request changes if needed.

5\. Submit the review.



\## Step 9: Merge the Pull Request



After approval, the repository owner checks for conflicts, clicks Merge pull request, and confirms the merge into main.



\## Step 10: Synchronize the Repository



After merging, members update their local copies.



&#x20;   git switch main

&#x20;   git pull --ff-only origin main

&#x20;   git status



\## Shared Laptop Guidelines



Our group uses one laptop and one Windows account. To maintain accurate contributions:



\- Each member uses a separate local project folder.

\- Each member configures their own local Git username and commit email.

\- Each member signs in to their own GitHub account for authentication and reviews.

\- Each member works on their assigned feature branch.

\- Members review another member's pull request using their own GitHub account.

\- The repository owner merges approved pull requests.



\## Conclusion



Git and GitHub help our group organize project files, track contributions, review changes, and collaborate effectively.

