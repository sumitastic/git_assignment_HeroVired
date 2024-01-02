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
git checkout -b feature/circle-area
git stash save "WIP: Circle Area Feature"
git status
git checkout -b feature/rectangle-area
git stash save "WIP: Rectangle Area Feature"
git status
git checkout feature/circle-area
git stash apply
radius = 5
print(f"The area of the circle with radius {radius} = {calculator.calculate_circle_area(radius)}")
git add .
git commit -m "Implement Circle Area Feature"
git push origin feature/circle-area
git checkout feature/rectangle-area
git stash apply
length = 10
width = 6
print(f"The area of the rectangle with length {length} and width {width} = {calculator.calculate_rectangle_area(length, width)}")
git add .
git commit -m "Implement Rectangle Area Feature"
git push origin feature/rectangle-area



