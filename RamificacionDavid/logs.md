# logs

```bash
david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git pull
Already up to date.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git branch
* main

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git add .

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git branch RamificacionDavid

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git branch
  RamificacionDavid
* main

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git checkout RamificacionDavid
Switched to branch 'RamificacionDavid'

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git add .

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 4 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), 1.41 KiB | 96.00 KiB/s, done.
From https://github.com/Grupo-2-El-mas-Melon/ContenidosCurso
 * [new branch]      RamificacionEze -> origin/RamificacionEze
Already up to date.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git branch
* RamificacionDavid
  main

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git pull RamificacionEze
fatal: 'RamificacionEze' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git branch
* RamificacionDavid
  main

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git merge RamificacionEze
merge: RamificacionEze - not something we can merge

Did you mean this?
        origin/RamificacionEze

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git merge RamificacionDavid
Updating 849ca77..1fbab19
Fast-forward
 RamificacionDavid/prueba.md | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 RamificacionDavid/prueba.md

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git push origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Grupo-2-El-mas-Melon/ContenidosCurso
   849ca77..1fbab19  main -> main

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ echo > logs.md

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 669 bytes | 55.00 KiB/s, done.
From https://github.com/Grupo-2-El-mas-Melon/ContenidosCurso
   ef72fed..d60b011  RamificacionRocio -> origin/RamificacionRocio
Already up to date.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git pull
Updating 1fbab19..18257d3
Fast-forward
 README.md                   | 14 +++++++++++++-
 RamificacionRocio/primer.md |  1 +
 2 files changed, 14 insertions(+), 1 deletion(-)
 create mode 100644 RamificacionRocio/primer.md

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git pull
Updating 2073d9f..5f2f2c0
Fast-forward
 RamificacionEze/bubalungas.txt | 66 ++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 66 insertions(+)
 create mode 100644 RamificacionEze/bubalungas.txt

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git branch
  RamificacionDavid
* main

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git checkout RamificacionDavid
Switched to branch 'RamificacionDavid'
Your branch is up to date with 'origin/RamificacionDavid'.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git rebase main
Successfully rebased and updated refs/heads/RamificacionDavid.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git pull
Already up to date.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 1 commit, and can be fast-forwarded.
  (use "git pull" to update your local branch)

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git pull
Updating 5f2f2c0..9f4c5ad
Fast-forward
 RamificacionJuanAntonio/Fudefua.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 RamificacionJuanAntonio/Fudefua.txt

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (main)
$ git checkout RamificacionDavid
Switched to branch 'RamificacionDavid'
Your branch is ahead of 'origin/RamificacionDavid' by 5 commits.
  (use "git push" to publish your local commits)

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ git rebase main
Successfully rebased and updated refs/heads/RamificacionDavid.

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$ echo > RamificacionDavid/logs.md

david_3hl9vpw@PC_Celia_David MINGW64 /c/Dev/Git-tutorial/ContenidosCurso (RamificacionDavid)
$
```
