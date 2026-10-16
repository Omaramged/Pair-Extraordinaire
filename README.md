# Pair-Extraordinaire

A small collaboration demo repository owned by Omaramged with MuhannedAmged
as a collaborator. It exists to practice a legitimate, correctly attributed
co-authored contribution on GitHub.

## How collaboration works here

- The default branch is `main`.
- Changes are proposed on short-lived feature branches (for example,
  `feat/pair-extraordinaire`) and merged into `main` through a Pull Request.
- Each co-authored commit uses Git's official `Co-authored-by` trailer so
  GitHub attributes the change to every contributor.

## Contributing a co-authored change

1. Create a focused branch from `main`:

   ```powershell
   git switch -c feat/your-change
   ```

2. Make a small, useful change and review it before committing:

   ```powershell
   git diff --cached
   ```

3. Commit with the primary author set to the change author and add the
   collaborator with a `Co-authored-by` trailer that uses the collaborator's
   verified GitHub address:

   ```text
   Improve repository documentation

   Co-authored-by: Muhanned Amged <164972846+MuhannedAmged@users.noreply.github.com>
   ```

4. Push the branch, open a Pull Request targeting `main`, have it reviewed,
   and merge it using a method that preserves the original commit (regular
   merge) so the co-author trailer stays intact.

## Verifying attribution

- Open the merged Pull Request and confirm the co-authored commit is included.
- Open the commit on GitHub and confirm the collaborator appears as a linked
  co-author.
- Check each contributor's profile for contribution history. Achievement
  awarding is controlled by GitHub and may take time.