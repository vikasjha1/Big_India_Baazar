# Big_India_Baazar

command for setting git repository. Run these commands one by one in your terminal from the root directory. This will set up your Git repository and push your initial commit to GitHub.

cd ..
git init
echo "# Node modules\nbackend/node_modules/\nfrontend/node_modules/\n\n# Environment variables\nbackend/.env\nfrontend/.env\n\n# Logs\nlogs/\n*.log\nnpm-debug.log*\nyarn-debug.log*\nyarn-error.log*\n\n# Build directories\ndist/\nbuild/\n\n# Temporary files\n*.tmp\n*.swp\n" > .gitignore
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/Big_India_Bazaar.git
git push -u origin master
