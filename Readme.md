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

* [Visual Studio Code](https://code.visualstudio.com/) installieren
  * Markdown All in One (3.4.0)
  * YAML (0.13.0)
  * (optional) Hugo Language and Syntax Support
* [GitHub](https://github.com) Account anlegen
* [GitHub Desktop](https://desktop.github.com/) installieren (oder ein anderer Git Client)
* [GitHub Learning Lab zu Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)
* Hugo runterladen (z.B. [Chocolatey](https://chocolatey.org/))
  
  * Hugo installieren (in einer Admin cmd/powershell):
  `choco install hugo-extended -confirm`


## TODO
- [ ] Continious Integration Pipeline (GitHub Actions)
- [ ] Templates anlegen
  - [ ] Template für Warbands
  - [ ] Template für Skills
  - [ ] Template für Magic
  - [ ] Template für Waffen
- [ ] Grundregeln
  - [ ] Parry
  - [ ] Wetter
  - [ ] Szenarien
  - [ ] Exploration Table (später)
- [ ] Format für Skills
- [ ] Warbands
- [ ] Legal notice and attribution