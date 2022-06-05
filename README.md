---
Serzeedgirl/Serzeedgirl is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
echo "# Serzeedgirl" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/Serzeedgirl/Serzeedgirl.git
 git push - ты главный
via pip (latest stable, recommended)
# if you use a virtualenv, don't use the `--user` option
pip install --user buildozer

# latest dev version
# if you use a virtualenv, don't use the `--user` option
pip install --user https://github.com/kivy/buildozer/archive/master.zip

# git clone, for working on buildozer
git clone https://github.com/kivy/buildozer
cd buildozer
python setup.py build
pip install -e .


