## Setting up my Git Repository

1. Instructions to set up my local folder to point to Github

```bash
    echo "# colmaracademy" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/SEI-agi/colmaracademy.git
    git remote -v
    git push -u origin main
```

2. In the event that the URL repo is set wrongly, use the following command to set the correct url:

```bash
git remote set-url origin https://github.com/thinktinker/colmaracademy.git
git remote -v
git push
```

3. Important Note on css specificity:

Universal selector (*) targets every element (regardless tag, class, ID)
If pseudo class :root is used, :root takes priority over html
When applied, font size of 5px takes priority over that of html
Here, html selector takes priority as root element over universal selector
