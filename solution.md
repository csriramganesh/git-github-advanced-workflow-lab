# Task 1 - Pull Requests

## What is a Pull Request?

A Pull Request (PR) is a mechanism used to review and merge code changes from one branch into another.

## Steps Followed

1. Created a feature branch.
2. Added a new file.
3. Committed changes.
4. Pushed branch to GitHub.
5. Created a Pull Request.
6. Merged the Pull Request into main.

## Pull Request Best Practices

- Use meaningful titles.
- Write clear descriptions.
- Keep PRs small and focused.
- Review code before merging.

## Handling Review Comments

- Address requested changes.
- Push updates to the same branch.
- Re-request review if necessary.



# Task 2 - Reset and Revert

## Git Reset

Git reset moves the branch pointer to a previous commit.

### Soft Reset

- Removes commit
- Keeps changes staged

### Mixed Reset

- Removes commit
- Unstages changes
- Keeps files intact

### Hard Reset

- Removes commit
- Removes changes
- Dangerous operation

## Git Revert

Git revert creates a new commit that reverses a previous commit.

## Reset vs Revert

| Reset | Revert |
|---------|---------|
| Rewrites history | Preserves history |
| Good for local work | Good for shared branches |
| Can remove commits | Creates undo commit |

## When To Use

- Use reset before pushing.
- Use revert after pushing to shared repositories.


# Task 3 - Git Stash

## What is Git Stash?

Git stash temporarily saves uncommitted changes without creating a commit.

## Workflow Performed

1. Modified a file.
2. Created a stash.
3. Switched branches.
4. Restored changes using stash pop.
5. Demonstrated stash apply.

## stash pop vs stash apply

### git stash pop

- Restores changes
- Removes stash entry

### git stash apply

- Restores changes
- Keeps stash entry

## When To Use Git Stash

- Urgent branch switching
- Context switching
- Temporary work preservation
- Testing without commits


# Task 4 - Cherry Picking

## What is Cherry-Picking?

Cherry-picking applies a specific commit from one branch onto another branch.

## Workflow Performed

1. Created a bug-fix branch.
2. Added a fix.
3. Committed the fix.
4. Returned to main.
5. Applied the commit using git cherry-pick.

## Real-World Usage

- Backporting fixes
- Production hotfixes
- Selective feature movement
- Emergency bug fixes

## Risks of Cherry-Picking

- Duplicate commits
- Merge conflicts
- Difficult history tracking if overused
