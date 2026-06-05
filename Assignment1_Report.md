# Assignment 1 Report - Git Branching and Collaboration

## GitHub Network Graph

<img width="837" height="494" alt="Network graph" src="https://github.com/user-attachments/assets/fdfabc27-5397-4fb3-b813-829952ed6a7c" />


## Branch Protection Rules
<img width="891" height="314" alt="Branch protection" src="https://github.com/user-attachments/assets/75ac0f9e-f6b1-4e39-aa45-1d93c42ae1a1" />


## Git Log

969e254 (HEAD -> develop, origin/develop) Merge pull request #5 from cloudbadger44/feature/update-readme
|
| *   8208b94 Merge branch 'develop' into feature/update-readme
| |
| |/
|/|
| b0cfb7b Add course code and date to README
| e70447b Add author name and student ID to README
28e212f Merge pull request #4 from cloudbadger44/feature/add-code-of-conduct
|
| * 7b7c356 Add enforcement guidelines section to Code of Conduct
| * ee10e10 Add Code of Conduct using Contributor Covenant template
14741f0 Merge pull request #3 from cloudbadger44/feature/add-dockerignore
|
| * f5f68f3 Add IDE and OS file exclusions to .dockerignore
| * ee453dc Add .dockerignore with Python project exclusions
596a2e1 Merge pull request #2 from cloudbadger44/feature/add-readme-details
|
| * e79b27a Add license section to README
| * f362b55 Add project description and prerequisites to README
de28228 Update README with project details and setup instructions
9f597a3 Initial commit
## Reflection: Merge Conflict Challenges
The most challenging part of resolving merge conflicts was understanding
the conflict markers and knowing which changes to keep. When two branches
edit the same lines of a file, Git cannot automatically decide which version
is correct. I learned that carefully reading both versions and manually
combining them is essential. I also found it important to always pull the
latest changes from develop before starting a new branch to minimize
the chance of conflicts occurring.
