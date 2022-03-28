# testGIT

# 1. first commit: creation of the repository  
```
echo "# testGIT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/popgenomics/testGIT.git
git push -u origin main
```

# 2. add/update new codes  
```
touch pouet.py
git add pouet.py
git commit -m "super"
git push -u origin main
```
