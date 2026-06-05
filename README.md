
# Git & GitHub Advanced Workflow Lab

## Project Overview

This project demonstrates advanced Git and GitHub concepts commonly used in real-world software development and DevOps workflows.

The goal of this challenge was to gain hands-on experience with:

* Pull Requests (PRs)
* Git Reset
* Git Revert
* Git Stash
* Git Cherry-Pick
* Git Rebase

All concepts were practiced using a dedicated GitHub repository while documenting commands, screenshots, and outcomes.

---

## Objectives

* Understand collaborative development using Pull Requests.
* Learn different methods of undoing changes safely.
* Save work temporarily using Git Stash.
* Apply specific commits across branches using Cherry-Pick.
* Maintain a clean commit history using Rebase.
* Build confidence with industry-standard Git workflows.

---

## Skills Covered

* Git Branching
* Pull Requests
* GitHub Collaboration
* Commit Management
* Git Reset
* Git Revert
* Git Stash
* Git Cherry-Pick
* Git Rebase
* Conflict Resolution
* Version Control Best Practices

---

## Project Structure

```text
git-github-advanced-workflow-lab
├── screenshots
├── tasks
│   ├── pr-demo.txt
│   ├── reset-demo.txt
│   ├── stash-demo.txt
│   ├── cherry-pick-demo.txt
│   └── rebase-demo.txt
├── solution.md
└── README.md
```

---

# Task 1: Pull Request Workflow

### Activities Performed

* Created a feature branch
* Added changes
* Committed and pushed changes
* Created a Pull Request
* Merged Pull Request into main branch

### Screenshots

#### Project Setup

![Project Structure](screenshots/01_project_structure_created.png)

#### Feature Branch Created

![Feature Branch](screenshots/02_feature_branch_created_and_commited_pushed.png)

#### Compare Pull Request

![Compare Pull Request](screenshots/Compare_Pull.png)

#### Create Pull Request

![Create Pull Request](screenshots/Create_pull.png)

#### Pull Request Merged

![Pull Request Merged](screenshots/04_pull_request_merged.png)

#### GitHub After Merge

![GitHub After Merge](screenshots/github_after_pr_merged.png)

---

# Task 2: Reset & Revert

### Concepts Practiced

* Soft Reset
* Mixed Reset
* Hard Reset
* Revert

### Screenshots

#### Reset Demo File

![Reset Demo](screenshots/06_reset_demo_file_created.png)

#### Bad Commit Created

![Bad Commit](screenshots/07_bad_commit_created.png)

#### Soft Reset

![Soft Reset](screenshots/08_soft_reset.png)

#### Mixed Reset

![Mixed Reset](screenshots/09_mixed_reset.png)

#### Hard Reset

![Hard Reset](screenshots/10_hard_reset.png)

#### Git Revert

![Git Revert](screenshots/11_git_revert.png)

---

# Task 3: Git Stash

### Concepts Practiced

* Saving uncommitted work
* Switching branches safely
* Restoring stashed changes
* Difference between stash pop and stash apply

### Screenshots

#### Stash Demo File

![Stash Demo](screenshots/12_stash_demo_file_created.png)

#### Uncommitted Changes

![Uncommitted Changes](screenshots/13_uncommitted_changes.png)

#### Git Stash Created

![Git Stash](screenshots/14_git_stash_created.png)

#### Hotfix Branch

![Hotfix Branch](screenshots/15_hotfix_branch_created.png)

#### Stash Pop

![Stash Pop](screenshots/16_stash_pop.png)

#### Stash Apply

![Stash Apply](screenshots/17_stash_apply.png)

#### Cleanup

![Cleanup](screenshots/18_stash_cleanup.png)

---

# Task 4: Cherry-Picking

### Concepts Practiced

* Creating a bug-fix branch
* Selecting a specific commit
* Applying a commit to another branch

### Screenshots

#### Cherry-Pick Demo File

![Cherry Pick Demo](screenshots/19_cherry_pick_demo_file_created.png)

#### Bug Fix Commit

![Bug Fix Commit](screenshots/20_bugfix_commit_created.png)

#### Before Cherry Pick

![Before Cherry Pick](screenshots/21_before_cherry_pick.png)

#### Cherry Pick Applied

![Cherry Pick Applied](screenshots/22_cherry_pick_applied_verified.png)

---

# Task 5: Rebasing

### Concepts Practiced

* Updating feature branches
* Rebasing onto main
* Conflict resolution
* Maintaining clean commit history

### Screenshots

#### Rebase Demo File

![Rebase Demo](screenshots/24_rebase_demo_file_created.png)

#### Feature Branch Before Rebase

![Before Rebase](screenshots/25_feature_branch_before_rebase.png)

#### Main Branch Update

![Main Update](screenshots/26_main_branch_new_commit.png)

#### Diverged History

![Before Rebase History](screenshots/27_before_rebase_history.png)

#### Conflict Resolution

![Conflict Resolution](screenshots/28_rebase_conflict_resolution.png)

#### Rebase Completed

![Rebase Completed](screenshots/29_rebase_completed.png)

#### Rebase Verification

![Rebase Verification](screenshots/30_rebase_file_verified.png)

---

## Key Learnings

### Pull Requests

* Collaborate safely using feature branches.
* Review code before merging.

### Reset vs Revert

* Reset rewrites history.
* Revert preserves history by creating a new commit.

### Git Stash

* Save unfinished work temporarily.
* Resume work without creating unnecessary commits.

### Cherry-Picking

* Move specific commits between branches.
* Useful for bug fixes and hotfixes.

### Rebasing

* Maintain a linear and clean commit history.
* Avoid unnecessary merge commits.

---

## Common Git Commands Used

```bash
git checkout -b <branch>

git add .

git commit -m "message"

git push origin <branch>

git reset --soft HEAD~1 or Hash Id
 
git reset --mixed HEAD~1 or Hash Id

git reset --hard HEAD~1 or Hash Id

git revert HEAD

git stash

git stash pop

git stash apply

git cherry-pick <commit-id>

git rebase main
```

---

## Real-World Applications

* Team collaboration using Pull Requests
* Production hotfix management
* Code review workflows
* Bug fix backporting
* Clean commit history maintenance
* DevOps and CI/CD development practices

---

## Author

**Sriram Ganesh**

Git & GitHub Advanced Workflow Lab completed as part of the **90 Days of DevOps** challenge.
