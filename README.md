# git_assignment_HeroVired
git clone <repository-url>
cd git_assignment_HeroVired
git checkout -b dev
git checkout main
git merge dev
# Resolve any conflicts if needed
git tag v1.0
git push origin main --tags
git checkout -b feature/sqrt
# Inside the Calculator class
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
    git checkout dev
git merge feature/sqrt
git checkout main
git merge dev
# Resolve any conflicts if needed
git tag v2.0
git push origin main --tags

#Question 2- solution
# Navigate to your local repository
cd git_assignment_HeroVired

# Initialize Git LFS
git lfs install
git checkout -b lfs
# Add the large file to be tracked by Git LFS
git lfs track "large_file.bin"

# Commit the changes
git add .gitattributes large_file.bin
git commit -m "Add large binary file and configure Git LFS"
git push origin lfs
git clone <repository-url>
cd git_assignment_HeroVired
git checkout lfs
# Check the file size
ls -lh large_file.bin
#Question-3


