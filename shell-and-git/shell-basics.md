<h1> Basic Shell commands </h1>

| Git command                                     | functionality                                                                                                    |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| ls                                              | list the content of the current directory                                                                        |
| ls -a                                           | um versteckte Ordner anzusehen                                                                                   |
| cd <foldername>                                 | change directory into a folder                                                                                   |
| cd ..                                           | change into the parent folder                                                                                    |
| cd ~                                            | change into your home directory                                                                                  |
| pwd                                             | to see your current directory path                                                                               |
| touch example.md                                | create a file called "example.md"                                                                                |
| mkdir newFolder                                 | create a folder called "newFolder"                                                                               |
| mv <oldname> <newname>                          | move or rename a file                                                                                            |
| rm <filename>                                   | delete a file permanently (there is no trash bin to recover files!)                                              |
| open .                                          | open the current folder in the finder                                                                            |
| cat <filename>                                  | prints the content of a specific file                                                                            |
| curl <url>                                      | prints the received content from the specified url. (try curl ipinfo.io)                                         |
| git status                                      | List all files that have changed and their state                                                                 |
| git add <filename>                              | Add a file to the stage                                                                                          |
| git commit -m "add foo"                         | Create a commit including all staged files                                                                       |
| git log --oneline                               | Show the commit history                                                                                          |
| git push                                        | Upload content to the remote repository                                                                          |
| git pull                                        | Download content from the remote repository                                                                      |
| tree                                            | Übersicht von alles Dateien/Ordner                                                                               |
| git commit -m "write your commit message here"  | After you added files to the stage, you can commit them and add a commit msg.                                    |
| git push origin main or git push -u origin main | if you push for the first time Push your commited files to the Github repository.                                |
| git restore --staged <filename>                 | Von der Stage runternehmen und zu modiefied wieder "zurücksetzen".                                               |
| git restore <filename>                          | Macht alles bis zum letzten commit rückgängig, davor muss man die Datei aber von der Stage nehmen.               |
| git remote -v                                   |  Wo bin ich auf Github?                                                                                          |
| git remote rm origin                            | Remote Verknüpfung entfernen, z.B. wenn ich ausversehen https verwendet habe aber ssh will.                      |
| git init                                        |  Mach mir aus diesem Ordner in dem ich mich befinde ein Git Repo. Ordner hat dann einen versteckten .git Ordner. |
| git log --online                                |  Allgemeine Infos anzeigen, dann q drücken um aus diesem Modus raus zu kommen.                                   |
| echo ".DS_Store" > .gitignore                   | Write something into a file, here into the gitignore file.                                                       |
