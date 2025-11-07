## 문제1
```
~ $ cd Commands/
~/Commands $ pwd
/home/node/Commands
~/Commands $ 
```

## 문제2
```
~/Commands $ mkdir test
~/Commands $ ls -l
total 4
drwxr-sr-x    2 node     node          4096 Nov  7 03:45 test
~/Commands $ 
```

## 문제3
```
~/Commands $ mkdir notes
~/Commands $ cd notes/
~/Commands/notes $ pwd
/home/node/Commands/notes
~/Commands/notes $ 
```

## 문제4
```
~/Commands $ mkdir -p images videos docs
~/Commands $ ls -l
total 20
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 docs
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 images
drwxr-sr-x    2 node     node          4096 Nov  7 03:46 notes
drwxr-sr-x    2 node     node          4096 Nov  7 03:45 test
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 videos
```
## 문제5
```
~/Commands $ cd docs/
~/Commands/docs $ cd ..
~/Commands $ ls -l
total 20
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 docs
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 images
drwxr-sr-x    2 node     node          4096 Nov  7 03:46 notes
drwxr-sr-x    2 node     node          4096 Nov  7 03:45 test
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 videos
```