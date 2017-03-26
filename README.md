echo "# First-Web" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/lsionlan/First-Web.git
git push -u origin master
git checkout --orphan gh-pages
git rm -rf .
<h1>Sam Chang is goddamn handsome.</h1>
git add .
git commit -a -m "test!!!!"
git push origin gh-pages
