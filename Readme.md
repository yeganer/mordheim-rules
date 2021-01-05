# Mordheim konsolidiertes Regelwerk

## Vorbereitungen
### Chocolatey installieren:  
In einer Administrator Powershell (siehe [Anleitung](https://chocolatey.org/install#individual)):
```powershell  
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

In einer Administrator powershell/cmd folgendes ausführen um alle tools zu installieren:
```batch
choco install vscode git github-desktop hugo-extended -confirm
```

* Visual Studio Code Extensions installieren
  * Markdown All in One (3.4.0)
  * YAML (0.13.0)
  * Hugo Language and Syntax Support
  * GitHub Pull Requests and Issues
  * GitLens - Git Supercharged
* [GitHub](https://github.com) Account anlegen
* [GitHub Learning Lab zu Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)

## TODO
- [ ] Legal notice and attribution
- [ ] Continious Integration Pipeline (GitHub Actions)
- [ ] Templates anlegen
  - [ ] Template für Warbands
  - [ ] Template für Skills (Philip)
  - [ ] Template für Scenarios (Witram)
  - [ ] Template für Explorarion Tables (Niko)
  - [ ] Template für Magic
  - [ ] Template für Waffen
- [ ] Grundregeln
  - [ ] Parry
  - [ ] Wetter
  - [ ] Szenarien
  - [ ] Exploration Table (später)
- [ ] Format für Skills
- [ ] Warbands

## Run the development server
```batch
hugo server -D
```

## Build the website
```batch
hugo
```

## Add a new screnario/etc.
```batch
hugo new scenario/breakthrough.md
```