# COMP2156_Group40_Assignment

## Group Members 
- **Leader:** Faiz Ahmed (101464866) - [GitHub](https://github.com/FA-student01)
- **Member 2:** Faisal Malik (______) - [GitHub](https://github.com/faisalmalik0014)
- **Member 3:** Het Nikeshkumar Patel (101416709) - [GitHub](https://github.com/hett0909)
- **Member 4:** Jashanpreet Kaur (______) - [GitHub](https://github.com/Jashan0511)
- **Member 5:** SUJAN BK(101464863) - [GitHub](https://github.com/funsujan)


## Project Description
This repository hosts the group assignment for the COMP2156 DevOps course, focusing on collaborative Git workflows, branching strategies, and CI/CD integration.

## Instructions
   1) Clone the repository using git clone <repository-url>.
   2) Switch to your branch using git checkout STUDENTID-Name (e.g., git checkout 101416709-Het).
   3) Install any dependencies listed in the project files.

### CI/CD Pipeline
- **CI Tool**: GitHub Actions
- **Workflow**: Triggered on `push` or `pull_request`. Checks if the required files (`gb.txt`, `devops.txt`, `sdlc.txt`) exist.
- **Test**: The workflow runs a test to ensure that these files are present. If any file is missing, it will return an error.

### Branching Strategy
- **Main Branch**: Stable version. All work should be done in feature branches.
- **Feature Branches**: Use `STUDENTID` format (e.g., `101416709-Het`).
- **Pull Requests**: Create pull requests for merging feature branches into `main` after completion.  
