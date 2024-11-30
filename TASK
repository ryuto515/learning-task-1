# Step 1: Initialize Repository
mkdir my-first-repo && cd my-first-repo
git init
echo "This is my first Git repository." > README.md
git add README.md
git commit -m "Initial commit: Added README.md"

# Step 2: Make Changes and Commit
echo "Learning Git is fun!" >> README.md
git add README.md
git commit -m "Updated README.md with a new line"

# Step 3: Branching and Merging
git branch feature-branch
git checkout feature-branch
echo "This change is on the feature branch." >> feature.txt
git add feature.txt
git commit -m "Added feature.txt with a feature-specific change"
git checkout main
git merge feature-branch
git branch -d feature-branch
