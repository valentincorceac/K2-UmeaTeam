# 💚Projektet K2-EventFlow
1. Skapa ett web applikation åt en kommun som låter en besökare hitta relevant evenemanget på datum, kategori och plats.
---
### 💻Starta projektet
1. Klona projektet.
git clone "<länken>"
cd <mappen>
git status
2. Skapa .NET-projektet.
dotnet new console --name Eventflow --output . --use-program-main
dotnet new gitignore
dotnet build
dotnet run
3. Skapa en feature-branch.
git switch -c feature/console-project
git status
git add .
git commit -m "Skapa grundläggande console-projekt"
git push -u origin feature/console-project
---
### ⭐Git-workflow
1. Skapa en branch från Main.
2. Göra små begripliga commits.
3. Pusha -skicka upp branchen.
4. Pull request - begära granskning.
5. Review- kollegor granskar och du fixar feedback.
6. Merge -PR merge in i Main.
---
### 🖼️Kanban-tavla
