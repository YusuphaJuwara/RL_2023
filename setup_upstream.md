# Managing Materials and Solutions in GitHub Repositories

## Fetching Materials from Professor's Repository

### Step 1: Fork the Professor's Repository
- Visit your professor's GitHub repository.
- Click the "Fork" button to create your own copy.

### Step 2: Clone Your Forked Repository
- Open a terminal or command prompt.
- Use `git clone` to download your forked repository.
```bash
git clone https://github.com/YusuphaJuwara/RL_2023.git
```

### Step 3: Set Up Upstream Repository (Optional)

- Add the professor's repository as an "upstream" remote to keep your fork updated.
```bash
git remote add upstream https://github.com/KRLGroup/RL_2023.git
```

### Step 4: Periodically Sync with Upstream (Optional)

- To update your fork (main) with the professor's (upstream) changes, run these commands:
```bash
git fetch upstream
git checkout main
git merge upstream/main
git push
```

## Pushing Your Solutions to Your Repository

### Step 1: Modify or add files

- Create or modify files in your local repository.

### Step 2: Commit Your Changes

- Commit your changes using the following commands:
```bash
git add .
git commit -m "Your commit message"
```

### Step 3: Push to Your Repository

- Push your changes to your GitHub repository:
```bash
git push origin main
```

## Automation (Optional)

- To automate this workflow, consider using GitHub Actions or other automation tools.

**Note**: Always respect copyright and usage restrictions when sharing materials and solutions.

