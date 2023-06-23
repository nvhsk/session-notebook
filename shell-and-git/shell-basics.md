<h1> Git Cheat Sheet </h1>

`git init`
Mach mir aus diesem Ordner in dem ich mich befinde ein Git Repo.
Ordner hat dann einen versteckten .git Ordner.

`echo ".DS_Store" > .gitignore`
Write something into a file, here into the gitignore file.

`git log --online`
Allgemeine Infos anzeigen, dann `q` drücken um aus diesem Modus raus zu kommen.

`git add .`
Add all files to the stage.

`git status`
show what you added to the stage.

`git commit -m "write your commit message here"`
After you added files to the stage, you can commit them and add a commit msg.

`git push origin main` or `git push -u origin main` if you push for the first time
Push your commited files to the Github repository.

`git restore --staged <filename>`
Von der Stage runternehmen und zu modiefied wieder "zurücksetzen".

`git restore <filename>`
Macht alles bis zum letzten commit rückgängig, davor muss man die Datei aber von der Stage nehmen.

`git remote -v`
Wo bin ich auf Github?

`git remote rm origin`
Remote Verknüpfung entfernen, z.B. wenn ich ausversehen https verwendet habe aber ssh will.
