# Workflow for a .NET project

## Setup

1. Rename the **github-folder** directory to **.github**.
2. Keep the prompt files inside the **.github/prompts** folder.

## Feature workflow

Use this process for every feature or ticket:

1. Read the ticket and capture the requirement clearly. Example: **Add customer search by email**.
2. Open only the **00-feature-workflow.prompt.md** file.
3. Paste the requirement into the prompt, for example:
   - Requirement: **Add customer search by email**
4. Follow the workflow defined in **00-feature-workflow.prompt.md** to complete the implementation.

## Output files per feature

Each step in the workflow will generate a result file and save it in the feature folder (under a subfolder like **feat-0001**).
