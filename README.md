# Motorq Data Science Assignment 2025

## 📦 Git LFS (Large File Storage)

This repository uses **Git LFS** to efficiently manage large files. The dataset file (`Motorq Data Science Assignment - 2025.zip`, ~60MB) is stored using LFS.

### Why Git LFS?
Git LFS replaces large files with small pointer files in your Git repository, while storing the actual file contents on a remote server. This keeps the repository lightweight and improves clone/fetch performance.

### Prerequisites: Install Git LFS

**Before cloning this repository**, you need to have Git LFS installed:

#### On macOS:
```bash
brew install git-lfs
```

#### On Ubuntu/Debian:
```bash
sudo apt-get install git-lfs
```

#### On Windows:
Download and install from [git-lfs.github.com](https://git-lfs.github.com/)

#### Initialize Git LFS (one-time setup):
```bash
git lfs install
```

### Cloning This Repository

Once Git LFS is installed, clone the repository normally:
```bash
git clone https://github.com/theharshavinash/ds_assement_2026_summer_intern_CE.git
cd ds_assement_2026_summer_intern_CE
```

Git LFS will automatically download the large files during the clone process.

### Verify LFS Files

To verify that LFS files were downloaded correctly:
```bash
git lfs ls-files
```

You should see:
```
73e36f474f * Motorq Data Science Assignment - 2025.zip
```

To check the file size (should be ~60MB, not a few KB):
```bash
ls -lh "Motorq Data Science Assignment - 2025.zip"
```

### Troubleshooting

**Problem:** The zip file is only a few KB (instead of ~60MB)
- **Solution:** Git LFS is not installed or not initialized. Install Git LFS, run `git lfs install`, then `git lfs pull` to download the actual files.

**Problem:** `git lfs` command not found
- **Solution:** Install Git LFS using the instructions above, then run `git lfs install`.

**Problem:** LFS files show as "pointer" files
- **Solution:** Run `git lfs pull` to download the actual file contents.

## Instructions for Applicants

### Step 1: Read the Assignment
📖 **Read `problem_statement_ce.pdf` carefully** - This contains all the requirements, specifications, and evaluation criteria for your assignment.

### Step 2: Get the Dataset
📦 **Extract `Motorq Data Science Assignment - 2025.zip`** - This file is already in the repository (managed via Git LFS) and contains your dataset and any supporting materials. Simply extract it in your working directory.

### Step 3: Complete the Assignment
💻 Develop your solution according to the specifications in the PDF.

### Step 4: Submit Your Work
📤 **Zip all your code and upload to GitHub:**
- Create a new repository for your solution
- Include all your code, notebooks, documentation, and results
- Make sure your repository is public or share access with the evaluation team
- Include a clear README explaining your approach and how to run your code

### Step 5: Clean Up
🗑️ **Delete the dataset after completion** - For data privacy and security reasons, please delete all assignment data from your local machine once you've submitted your work.

## Need Help?
💬 **Feel free to reach out to the Motorq team** if you have any questions or need clarification during the assignment.

## Repository Contents
- `problem_statement_ce.pdf` - **START HERE** - Complete assignment requirements
- `Motorq Data Science Assignment - 2025.zip` - Dataset and materials (managed via Git LFS)
- `.gitattributes` - Git LFS configuration for tracking `*.zip` files

---
**All the best with your assignment!** 🚀