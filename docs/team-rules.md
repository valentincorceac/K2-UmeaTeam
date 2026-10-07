# Teamregler – EventFlow

Status: Förslag som ska godkännas av teamet.

## Våra gruppregler

1. Vi använder teamets gemensamma kanal för frågor och beslut.
2. Alla får komma till tals innan vi fattar gemensamma beslut.
   Vid oenighet jämför vi alternativen med kraven och kundvärdet.
3. Vi ber om hjälp efter 20 minuter utan framsteg.
4. Vi arbetar på separata branches och inte direkt på main.
5. Varje Pull Request granskas av minst en annan teammedlem.
   Vi ger konkret återkoppling på lösningen, inte personen.
6. Vi börjar varje Boiler Room med cirka 10 minuters Daily Scrum
   och dokumenterar ändringar i planen.
7. Vi granskar och testar AI-förslag själva, delar inga hemligheter
   och dokumenterar relevant AI-användning.

## Git-strategi

Vi använder GitHub Flow.

- Branches skapas från uppdaterad main.
- Namn: feature/<issue>-<namn>, fix/<issue>-<namn>
  eller docs/<issue>-<namn>.
- Commits beskriver ett avgränsat steg:
  feat: ..., fix: ... eller docs: ...
- En draft PR öppnas tidigt efter första relevanta ändringen.
- PR:n länkar till sitt backloggkort och beskriver vad, varför
  och hur ändringen kontrollerats.
- En annan teammedlem granskar innan merge.
- Författaren hanterar feedback och löser diskussioner
  tillsammans med granskaren.
- Vid konflikt kontaktar vi den som gjort den andra ändringen,
  jämför båda versionerna och kontrollerar resultatet.
- Efter merge uppdaterar teammedlemmarna sin lokala main.

## Skydd av main

Följande inställningar ska verifieras av repositoryts ägare:

- Pull Request krävs före merge.
- Minst ett godkännande krävs.
- Nya commits tar bort tidigare godkännanden.
- Reviewdiskussioner måste vara lösta.
- Administratörer får inte kringgå reglerna.
- Force push och borttagning av main tillåts inte.
- Inga obligatoriska status checks i det första flödet.

Aktiverat och verifierat: Inte dokumenterat ännu.
Länk till test-PR: Fylls i efter genomfört test.

## Manuell kontroll före merge

- Ändringen motsvarar kortets acceptanskriterier.
- Relevant testning eller dokumentgranskning är genomförd.
- Inga oavsiktliga filer eller känsliga uppgifter ingår.
- Review är godkänd och diskussionerna är lösta.
- Definition of Done kontrolleras.

## Ändra reglerna

Alla kan föreslå ändringar. Teamet diskuterar och godkänner
dem vid en avstämning och uppdaterar detta dokument.
