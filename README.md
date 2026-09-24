# Datacom Task 2 – GitHub Actions Demo

This repository was created as part of the **Datacom Cloud Support Job Simulation on Forage**, for **Task 2: Introduction to GitHub Actions**.

## Purpose

The purpose of this task is to demonstrate a basic understanding of **CI/CD** and GitHub Actions by creating and running a simple workflow.

## What This Workflow Does

The GitHub Actions workflow is triggered automatically whenever code is pushed to the repository.

It:

* Prints a welcome message
* Displays the event that triggered the workflow
* Shows the operating system used by the GitHub runner
* Checks out the repository code
* Confirms that the repository was successfully cloned
* Confirms that the workflow is ready to run additional steps

## Workflow File

The workflow configuration is located at:

```text
.github/workflows/github-actions-demo.yml
```

## Result

After the workflow is pushed to GitHub, it runs automatically. The workflow run, progress, and logs can be viewed from the **Actions** tab of the repository.

## Reflection

This task gave me practical experience with GitHub Actions and helped me understand how CI/CD workflows can be triggered automatically by repository events such as a push.

It also helped me become more familiar with YAML workflow files, GitHub-hosted runners, and the basic structure of a GitHub Actions workflow.
