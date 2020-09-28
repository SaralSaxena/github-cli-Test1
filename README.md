A sample read me file for the feature branch

gh auth status
gh repo create SaralSaxena/github-cli-Test1
cd github-cli-Test1
vi README.md
git add .
git  commit -am "[add] new read me file in master"
git  push origin master
gh repo view
gh help


--------------------
gh issue create
gh issue list
git checkout -b feature-issue1
git branch
vi README.md
git commit -am "[update] modified readme file in feature-issue1"
git push origin feature-issue1
gh issue list
gh pr create
gh pr list
gh pr diff
gh pr status
gh pr merge
λ gh pr checks
gh pr diff
