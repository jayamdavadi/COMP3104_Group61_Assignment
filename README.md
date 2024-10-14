# COMP3104_Group61_Assignment

## Group Members
- Leader: Jay Amdavdi (101435982) - [GitHub](https://github.com/jayamdavadi)  
- Member 2: Abhishek Kamat (101422675) - [GitHub](https://github.com/Abhishek-k)  
- Member 3: Tisha Chuahan (101478303) - [GitHub](https://github.com/thisistisha)  
- Member 4: Sifatpreet Kaur (101447665) - [GitHub](https://github.com/sifat1308)  
- Member 5: Avni Patel (101438174) - [GitHub](https://github.com/avni2107)  
- Member 6: Amaan Vohra (101436093) - [GitHub](https://github.com/Amaan7985)  

## Project Description
This repository contains the group assignment for the COMP 3104 DevOps course at George Brown College.
The project demonstrates collaborative Git workflows, branch management, and 
the implementation of continuous integration/continuous delivery (CI/CD) pipelines using GitHub Actions.

Each team member works on their assigned tasks in individual branches and 
integrates their changes into the `main` branch via pull requests.
The CI/CD pipeline automatically tests and validates the code 
to ensure that it meets the project's quality standards before merging.


## Setup Instructions
To set up and run the project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/jayamdavadi/COMP3104_Group61_Assignment.git
2. Switch to your branch: Each group member should work on their respective branch.
   git checkout 101435982-Jay
3. Install dependencies: If the project uses dependencies (e.g., for Node.js):
   npm install
4. Run tests: If tests are defined:
   npm test
5. Push your changes: After making changes, stage, commit, and push them to your branch:
   git add .
   git commit -m "Commit message"
   git push origin 101435982-Jay

## CI/CD Pipeline
The project utilizes GitHub Actions for continuous integration and delivery. 
The CI pipeline is triggered on push or pull request events to the main branch. 
It performs the following actions:
-Checks out the repository code.
-Installs dependencies (if applicable).
-Runs automated tests to ensure the code is working as expected.
-Builds the project (if applicable).

The workflow configuration file can be found in:
   .github/workflows/ci.yml

## Branching Strategy
Each group member works on their own branch, named using the format STUDENTID-Name(Ex-101435982-Jay).
After completing their tasks and making the necessary commits (at least 10 per member),
they will open a pull request (PR) to merge their changes into the main branch.

The group follows these branching conventions to ensure:

-Individual workspaces for each member, minimizing conflicts.
-Pull requests are used to review and merge code.
-Regular syncing between branches to keep the repository updated and avoid conflicts.
