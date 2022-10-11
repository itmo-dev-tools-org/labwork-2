# Лабараторная работа 2 в парах

Данный репозиторий выглядит так:
```
o--------------o--------o-------------------------------o----o----o main          
 \            / \      /                               /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
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
## Edited
```
o--------------o--------o-------------------------------o----o----o main          
 \            / \      /                               /
  \          /   o -- o  hotfix                       o release
   \        /          \                             /
    o ---- o ---------- o ----- o ---------- o------o  develop
            \            \     /            /
             \            o---o feature2   /
              o ------------------------- o  feature-1
```
