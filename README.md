# See this repository pages <a href="https://marlissonls.github.io/Front-end/" target="_blank">CLICK HERE</a>

# How to push in a new brach:
```
1   git clone "repositoryurl.git"
2   cd "/folder who contains .git folder"
3   git add "arquivo1" "arquivo2" ...
4   git commit -m ""descrição""
5   git branch "newbranchname"
6   git checkout "newbranchname" (as linhas 5 e 6 podem ser substituidas por - git checkout -b "newbranchname")
7   git push -u origin "newbranchname" (ou git push --set-upstream origin "newbranchname")
```
# On origin repository, create the Pull Request. After merge on branch main, delete your "newbranchname"
```
8   git checkout main
9   git push origin -d "newbranchname" (git push origin --delete "newbranchname")
10  git branch -d "newbranchname"
```
# To see the branch's graph:
```
11  git log --graph --pretty=oneline
```
