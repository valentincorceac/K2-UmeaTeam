- vem användaren eller kunden är
- vilket problem lösningen ska adressera
- vilket värde lösningen ska skapa
- vilken kärnfunktion som måste fungera vid redovisningen
- vad som uttryckligen ligger utanför projektets omfattning

# Produktvision
Event flow: Skapa ett smidig webbapplikation där man kan hitta och sortera efter evenemag.

## Målgrupp
Invånare i olika åldrar. Kommunen eller godkänd användare kan lägga till evenemang.

## Problem
Information om evenemang finns på flera olika platser.
Det gör det svårt att få en överblick, hitta relevanta
aktiviteter och förstå hur man anmäler sig.

## Kundvärde
För kommunens invånare som har svårt att hitta aktuella och samlade evenemangstider ger vårt 
applikation dem möjligheten att snabbt se vad som händer, när det händer och planera sin fritid 
utan krångel så att de enkelt kan ta del av kommunens utbud och få mer glädje, aktivitet och gemenskap i vardagen.


## Produktmål
- Visa kommande evenemang och detaljer om varje evenemang.
- Erbjuda sökning och filtrering efter kategori.
- Visa tydlig information när inga evenemang matchar.
- Erbjuda ett anmälningsformulär med validering och bekräftelse.
- Fungera på mobil och dator samt kunna användas med tangentbord.
- Visa relevant information från ett tillhandahållet externt API.
- Modellera evenemang och anmälningar i en relationsdatabas
  i SQL Server med god dataintegritet.

## Avgränsningar
- Ingen betalning eller biljettförsäljning
- Ingen inloggning eller administratörspanel i första versionen
- Anmälningsflödet demonstreras i frontend
- SQL Server-databasen och SQl-operationerna visas separat
