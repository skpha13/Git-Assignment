# Collaborative GitHub Workflow Project

## Project Overview
This project demonstrates a collaborative workflow using GitHub, where team members work together on a shared repository. The steps include setting up the repository, developing features in separate branches, creating and reviewing pull requests, merging branches, creating conflicts, and resolving them.

## Repository Setup

1. One team member creates a new repository on GitHub and adds the other as a collaborator.
2. Clone the repository locally and create a `README.md` file with basic project information.
3. Commit and push the `README.md` to the main branch.

## Branch Creation and Feature Development

1. Each team member creates a new branch from the main branch:
   - Member A: Create a branch named `feature-A`.
   - Member B: Create a branch named `feature-B`.

2. On your respective branches, add a new file:
   - Member A: Add `feature-A.txt` with relevant content.
   - Member B: Add `feature-B.txt` with relevant content.

3. Commit and push your changes to your branch.

## Creating and Reviewing Pull Requests

1. Each member creates a pull request (PR) to merge their feature branch into the main branch.
2. Review each other’s PRs, provide feedback, and suggest changes if necessary (1 comment per PR should be enough).
3. Approve and complete the PR after the review process.

## Merging Pull Requests

1. After PR approval, merge your feature branch into the main branch.
2. Ensure that both `feature-A.txt` and `feature-B.txt` files are present in the main branch after merging.

## Creating a Conflict

1. Both team members edit a file named `shared.txt` on their respective branches, making changes that will conflict with each other.
2. Commit and push your changes, then create a pull request to merge your `shared.txt` changes into the main branch.

## Resolving Conflicts

1. Work together to resolve the conflict in `shared.txt`.
2. Decide how to merge the conflicting changes, update the file accordingly, and complete the merge.
