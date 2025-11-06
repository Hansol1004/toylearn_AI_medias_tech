# PowerShell 명령 연습문제
## 문제1
```

PS C:\Users\PC> cd ../../
PS C:\> cd C:\Commands\
PS C:\Commands> pwd

Path
----
C:\Commands


```
## 문제2
```

PS C:\Commands> mkdir Test


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:55                Test


PS C:\Commands> ls


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:55                Test
```

## 문제3
```

PS C:\Commands> mkdir Notes


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:56                Notes


PS C:\Commands> cd .\Notes\
PS C:\Commands\Notes> pwd

Path
----
C:\Commands\Notes
```

## 문제4
```
PS C:\Commands\Notes> cd ../
PS C:\Commands> mkdir Images, Videos, Docs


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:56                Images
d-----      2025-11-06   오후 5:56                Videos
d-----      2025-11-06   오후 5:56                Docs


PS C:\Commands> ls


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:56                Docs
d-----      2025-11-06   오후 5:56                Images
d-----      2025-11-06   오후 5:56                Notes
d-----      2025-11-06   오후 5:55                Test
d-----      2025-11-06   오후 5:56                Videos
```

## 문제5
```

PS C:\Commands> cd .\Docs\
PS C:\Commands\Docs> cd ../
PS C:\Commands> ls


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:56                Docs
d-----      2025-11-06   오후 5:56                Images
d-----      2025-11-06   오후 5:56                Notes
d-----      2025-11-06   오후 5:55                Test
d-----      2025-11-06   오후 5:56                Videos


PS C:\Commands>
```