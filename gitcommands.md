| Git-kommando                                                  | Beskrivning                                                                           | Fel/problem & lösning (om tillämpligt) |
|---------------------------------------------------------------|---------------------------------------------------------------------------------------|----------------------------------------|
| git fetch                                                     | Hämtar nya data från remote repository utan att integrera dem                         |                                        |
| git cherry-pick <commit>                                      | Tillämpa ändringar från en specifik commit på den nuvarande grenen                      |                                        |
| git rebase <branch>                                           | Basera om den nuvarande grenen på en annan gren för en rakare historik                  |                                        |
| git blame <file>                                              | Visar rad-för-rad historik för en fil, med information om vem som gjort ändringar         |                                        |
| git archive --format=zip --output=archive.zip <branch>        | Skapar ett arkiv (ZIP-fil) av den angivna grenen                                        |                                        |
| git bisect start                                              | Initierar bisekteringsprocessen för att hitta en bugg                                   |                                        |
| git bisect bad                                                | Markerar den aktuella commit som defekt i bisekteringsprocessen                         |                                        |
| git bisect good <commit>                                      | Markerar en commit som fungerande i bisekteringsprocessen                               |                                        |
| git shortlog                                                  | Ger en sammanfattning av commits grupperade efter författare                            |                                        |
| git reflog                                                    | Visar en logg över alla referensuppdateringar, användbart för att återställa commits      |                                        |
| git clean -f                                                  | Tar bort oversionerade filer från arbetskatalogen                                       |                                        |
| git mv <oldfile> <new_file>                                     | Flyttar eller byter namn på filer inom repositoryt                                      |                                        |
| git submodule add <rep_url> <path>                              | Lägger till en submodul från en extern repository                                       |                                        |
| git submodule update --init                                   | Initialiserar och uppdaterar alla submoduler så att de matchar konfigurerade versioner    |                                        |
| git reflog expire --expire=now --all                           | Rensar gamla referensloggar omedelbart för att frigöra lagringsutrymme                   |                                        |
