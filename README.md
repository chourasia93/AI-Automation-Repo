# Extract repo zip
unzip ai-automation-framework_with_CI.zip
cd ai-automation-framework

# Initialize git
git init
git add .
git commit -m "Initial commit with CI/CD workflows"

# Add remote (replace with your repo URL)
git remote add origin https://github.com/yourusername/ai-automation-framework.git
git branch -M main
git push -u origin main
