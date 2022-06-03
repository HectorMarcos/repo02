# Repo02

## Steps

```
mkdir repo02
cd repo02
git init
touch readme.md
git add .
git commit -m "1st commit"
git remote add origin https://github.com/HectorMarcos/repo02.git
git branch -M main
git push -u origin main
cd ..
rm -r repo02
git clone https://github.com/HectorMarcos/repo02.git
```

## Git Tips

_start your repository_
```
git init
```
_set a single file to stage area_
```
git add salmple.txt
```

_set ALL files to stage area_
```
git add .
```

_add files to respository_
```
git commit -m "message"
```

_check actual estatus of your files_
```
git status
```

_check all commits done_
```
git log 
```
