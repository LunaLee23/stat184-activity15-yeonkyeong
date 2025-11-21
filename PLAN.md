# Project and Repository Plan

This document describes my plan for both:
1. The STAT 184 project work (Activity 14 and Activity 15), and
2. Setting up and maintaining this GitHub repository.

The plan is organized by **Goals**, **Needs**, and **Steps**.

---

## 1. Project Plan (Activity 14 & 15)

### 1.1 Goals

- Demonstrate that I can use GitHub and version control (branches, issues, pull requests).
- Keep a clear record of my STAT 184 Activity 14 report and source code.
- Produce a clean, reproducible Quarto document and PDF for Activity 14.
- Meet all of the grading rubric requirements for Activity 15.

### 1.2 Needs

- Access to Canvas and the STAT 184 data files used in Activity 14.
- Software: R, RStudio (or Posit), Quarto, and GitHub Desktop.
- Time to revise the Activity 14 analysis if needed.
- A stable internet connection to push commits and update the repo.

### 1.3 Steps

1. Review the Activity 14 instructions and rubric.
2. Finish and check the Activity 14 Quarto (`Activity14.qmd`) and PDF report.
3. Save final versions of the Activity 14 files in this repository.
4. Update the README so that it explains what the project is and how it is organized.
5. Use this repository as evidence of my GitHub and version control skills for Activity 15.

---

## 2. Repository Setup & Maintenance Plan

### 2.1 Goals

- Keep the `main` branch clean and up to date for grading.
- Use a development branch (`dev`) for making changes before they are merged into `main`.
- Use GitHub Issues and Pull Requests to document important work.
- Make meaningful commits with clear messages instead of one large commit.

### 2.2 Needs

- A GitHub repository with public visibility.
- At least two branches: `main` and `dev`.
- A basic understanding of git workflows (commit, push, pull request, merge).
- Clear naming conventions for files and commits.

### 2.3 Steps

1. **Create and publish the repo**
   - Create the repository on GitHub and clone it using GitHub Desktop.
   - Create a `dev` branch from `main`.

2. **Track tasks with Issues**
   - Open Issues for tasks such as “Add Activity 14 PDF and QMD files”
     and “Update README with overview and plan”.
   - Apply appropriate labels (for example, `documentation`).

3. **Develop on the `dev` branch**
   - Make changes (edit files, add new files) on the `dev` branch.
   - Commit frequently with meaningful messages that describe the changes.

4. **Use Pull Requests to merge changes**
   - Open a Pull Request from `dev` into `main`.
   - In the PR description, link and close the related Issues (e.g., `Closes #2`, `Closes #3`).
   - After reviewing the changes, merge the PR into `main`.

5. **Maintain the repository**
   - Keep the README and PLAN documents up to date if the project changes.
   - Use additional Issues and Pull Requests if future updates are needed.
   - Regularly check that the `main` branch builds the report correctly and contains
     the latest versions of all important files.
