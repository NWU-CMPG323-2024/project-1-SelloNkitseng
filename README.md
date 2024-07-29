[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/h7CYPb85)

# Project Overview

This repository serves as the main hub for my projects. Below is a detailed guide on which Repository it uses, documentation, branching strategy, .gitignore usage, and handling of credentials and sensitive information.

# Repositories

1. CMPG-323-Overview--30776538: This repository is used for Project 1.
2. CMPG-323-Overview--30776538: This repository is used for Project 2.
3. CMPG-323-Overview--30776538: This repository is used for Project 3.
4. CMPG-323-Overview--30776538: This repository is used for Project 4.
5. CMPG-323-Overview--30776538: This repository is used for Project 5.


# Documentation

A comprehensive lean technical document can be found: 
https://github.com/NWU-CMPG323-2024/project-1-SelloNkitseng/blob/main/Lean%20Technical%20Documentation%20Template%201.0.docx  

Burndown chart can be found:


# Branching Strategy

I follow a consistent branching strategy to streamline the development process:

1. **Main Branch**: The main branch is the stable branch containing the production-ready code. 
2. **Develop Branch**: The develop branch is used for integrating new features before they are merged into the main branch.
3. **Feature Branches**: Feature branches are created from the develop branch for new features or significant updates. 
4. **Bugfix Branches**: Bugfix branches are created from the develop branch for addressing bugs. 
5. **Hotfix Branches**: Hotfix branches are created from the main branch for urgent fixes. 

# .gitignore Usage
Each project repository includes a `.gitignore` file to exclude unnecessary files from being tracked in version control. This typically includes:

- Log files
- Temporary files and directories
- Build output directories
- Environment configuration files

Proper use of `.gitignore` ensures a clean and efficient repository.
Storage of Credentials and Sensitive Information

To protect sensitive information, we adhere to the following practices:
1. **Environment Variables**: Store credentials and sensitive information in environment variables. This keeps them out of the codebase.
2. **Configuration Files**: Use configuration files that are excluded from version control (listed in `.gitignore`) to manage sensitive information locally.
3. **Secrets Management Services**: Utilize secrets management services (e.g., AWS Secrets Manager, HashiCorp Vault) for securely storing and accessing sensitive data.

