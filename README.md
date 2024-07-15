# My Resume

## Updating
Update resume version here by running:
```
git pull --rebase
$ textutil -convert html Michelle_Xia_Resume.docx -stdout | pandoc -s -f html -t latex -o Michelle_Xia.tex
git add .
git commit -m "Description of resume update"
git push
```
