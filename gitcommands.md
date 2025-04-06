| Git-kommando                                  | Beskrivning                                                                                      | Fel/problem & lösning (om tillämpligt) |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------|----------------------------------------|
| git push --set-upstream origin                | Skickar lokala commits till fjärr-repository och sätter upp en upstream-branch                    |                                        |
| git stash                                     | Sparar temporärt ändringar som inte är committade                                                 |                                        |
| git stash pop                                 | Återställer senast stashade ändringar och tar bort dem från stash-listan                          |                                        |
| git merge --no-ff                             | Slår samman grenar med en merge commit utan fast-forward                                          |                                        |
| git pull -rebase                              | Hämtar remote ändringar och applicerar dem med rebase istället för merge                           |                                        |
| git remote set -url origin                    | Uppdaterar URL:en för remote "origin"                                                            |                                        |
| git branch -D                                 | Tvingar borttagning av en lokal gren                                                             |                                        |
| git branch -d                                 | Tar bort en lokal gren som redan är mergad                                                      |                                        |
| git reset [file]                              | Återställer en specifik fil från staging-området                                                |                                        |
| git revert [commit]                           | Skapar en ny commit som återställer effekten av ett tidigare commit                              |                                        |
| git config --global user.name                 | Sätter globalt användarnamn för commits                                                          |                                        |
| git config --global user.email                | Sätter global e-postadress för commits                                                           |                                        |
| git status                                    | Visar aktuell status för filer i repositoryt                                                   |                                        |
| git show                                      | Visar detaljerad information om en commit                                                      |                                        |
| git rm                                        | Tar bort filer från arbetskatalogen och staging-området                                          |                                        |
| git remote remove                             | Tar bort en remote konfiguration                                                                 |                                        |
| git remote show origin                        | Visar detaljerad information om remote "origin"                                                |                                        |
| git merge --abort                             | Avbryter en pågående merge och återställer repositoryt till föregående tillstånd                  |                                        |
| git pull --rebase                             | Hämtar remote ändringar och rebasar lokala commits                                               |                                        |
| git push --force                              | Tvingar en push till remote repository och skriver över historiken                                |                                        |
| git diff --staged                             | Visar skillnader mellan staged ändringar och den senaste commit                                  |                                        |
| git diff                                      | Visar skillnader mellan arbetskatalogen och den senaste commit                                   |                                        |
| git tag -a v1.0 -m "version 1.0 release"        | Skapar en annoterad tagg med meddelande                                                          |                                        |
| git reset --hard                              | Återställer både arbetskatalog och staging-området till senaste commit, oåterkalleligt             |                                        |
| git rebase -i HEAD                            | Startar en interaktiv rebase från HEAD för att redigera commit-historiken                          |                                        |
| git log --oneline                             | Visar en översiktlig lista över commits i en kompakt form                                        |                                        |
| git reset --soft HEAD-                        | Återställer HEAD men behåller ändringarna i staging-området                                      |                                        |
| git stash list                                | Visar en lista över alla stashade ändringar                                                     |                                        |
| git stash apply                               | Applicerar en specifik stash utan att ta bort den från listan                                    |                                        |
| git stash clear                               | Tar bort alla stashade ändringar permanent                                                      |                                        |
