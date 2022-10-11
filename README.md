# Лабараторная работа 2 в парах

Данный репозиторий выглядит так:
```
              v0.0     v1.0                           v2.0  v2.1  v2.2
o--------------o--------o-------------------------------o----o----o main          
 \            / \      /                               /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
# Используемые команды
```
1. git clone <url>
2. git status
3. git add <file-name>
4. git commit -m "<comment>"
5. git log
6. git push
7. git branch <new-branch>
8. git branch -a /-r
9. git switch / checkout
9. git pull
10. git push 
11. git tag -a <tag-name> <hash-commit> -m "<commit-tag>"
12. git push origin --tags
13. git tag -d <tag-name>
14. git merge <merged-branch-name>
15. git tag -a <tag-name> <hash-commit> -m "<commit-tag>"
16. git submodule add <url-repository>
```

# История

## Dev 1
Добавлена ветка **`develop`**
```
o  main
 \
  o  develop
```

## Dev 2
Добавлен файл **`dev2.txt`**
```
o  main
 \
  o ---- o develop
```

## Pull Request & Merge: develop->main

```
o----------o main
 \        /
  o ---- o develop
```

## Feature 1

```
o----------o main
 \        /
  o ---- o develop
          \
           o feature1
```

## Hotfix
```
o-------------o main   
 \           / \
  \         /   o----o hotfix
   \       /
    o ---- o develop
            \
             o feature1
```


## Pull Request & Merge: hotfix->main | hotfix->develop
```
o-------------o--------o main   
 \           / \      /
  \         /   o----o hotfix
   \       /          \
    o ---- o-----------o develop
            \
             o feature1
```
## Feature 1 update & add Feature 2
```
o-------------o--------o main   
 \           / \      /
  \         /   o----o hotfix
   \       /          \
    o ---- o-----------o develop
            \           \
             \           o-------o feature2
              \
               o--------o feature1
```
## Pull Request & Merge: feature2->develop
```
o-------------o--------o main   
 \           / \      /
  \         /   o----o hotfix
   \       /          \
    o ---- o-----------o-----------o develop
            \           \         /
             \           o-------o feature2
              \
               o--------o feature1
```
## Pull Request & Merge: feature1->develop
```                                                    
o--------------o--------o main          
 \            / \      /
  \          /   o -- o  hotfix                      
   \        /          \                             
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
## Release branch
```
o--------------o--------o main          
 \            / \      /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
## Pull Request & Merge: release->main

```
o--------------o--------o-------------------------------o main          
 \            / \      /                               /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
## Update README.md in main
```
o--------------o--------o-------------------------------o----o main          
 \            / \      /                               /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
## Add tags, Submodules
```

              v0.0     v1.0                           v2.0  v2.1  v2.2
o--------------o--------o-------------------------------o----o----o main          
 \            / \      /                               /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
