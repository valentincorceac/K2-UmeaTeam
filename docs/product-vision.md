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
EventFlow samlar evenemang på ett ställe. Besökaren kan söka,
filtrera efter kategori och se datum, tid, plats och arrangör.
Besökare ska ha tillgång till biljetten efter dom har anmält sig

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
- Tidligt Frontend
- Sparar evenemang i ett databas med information, datum.
