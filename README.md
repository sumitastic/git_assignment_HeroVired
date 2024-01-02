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
