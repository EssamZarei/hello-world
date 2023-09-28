

# Essam Zarei 2135306



# git-it-assignment
1. Get git
git --version
git confi ...
git config

2. Repository
mkdir hello-world
cd hello-world
git init
git status
cd hello-world
pwd


3. Commit To It
cd hello-world
git status
git add readme.txt
git status
git commit -m "your commite message"


4. GitHubbin
git config --global user.username EssamZarei


5. Remote Control
cd C:\Users\eaz99\hello-world
git remote add origin https://github.com/EssanZarei/hello-world.git
git push origin main


6. Forks And Clones
???
cd ..
git clone https://github.com/EssamZarei/patchwork.git
cd patchwork
git remote add upstream https://github.com/jlord/patchwork.git
git remote -v origin


7. Branches Aren't Just For Birds
git status
git branch add-EssamZarei
git checkout add-EssamZarei

cd C:\Users\eaz99\patchwork
git status
git branch add-EssamZarei
git checkout add-EssamZarei
git status
git add contributors/add-EssamZarei.txt
git commit -m "move file into contributors folder"
git push origin add-EssamZarei

git push origin add-EssamZarei
git commit -m "move file into contributors folder"
git push origin add-EssamZarei

cd C:\Users\eaz99\patchwork
mv "C:\Users\eaz99\patchwork\Patchwork\contributors\add-EssamZarei.txt" "Patchwork/contributors"
dir Patchwork\contributors
git add -A
git commit -m "Move file into contributors folder"
git push origin add-EssamZarei


8. It's A Small World
https://github.com/YOURUSERNAME/patchwork


9. Pull Never Out Of Date
cd C:\Users\eaz99\patchwork\Patchwork\contributors
git status
git pull origin add-EssamZarei
git fetch --dry-run


10. Requesting You Pull Please
NO CODE :)

11. Merge Tada
git checkout gh-pages
git checkout gh-pages
Switched to branch 'gh-pages'
git merge add-EssamZarei
git branch -d add-EssamZarei
git push origin --delete add-EssamZarei
git pull upstream gh-pages




![](./Screenshot_Git_It.png)




