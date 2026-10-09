# Databasmodell
En arrangör arrangerar lokala evenemang. 
Varje evenemang har en titel, ett datum, en starttid och en beskrivning. 
Ett evenemang arrangeras av exakt en arrangör, men en arrangör kan ansvara för många evenemang. 
Varje evenemang tillhör exakt en kategori, till exempel musik, sport eller kultur, 
medan en kategori kan användas för många evenemang. Ett evenemang hålls på exakt en plats, 
och samma plats kan användas för många evenemang över tid.
Besökare kan anmäla sig till evenemang. En besökare kan anmäla sig till många evenemang, 
och ett evenemang kan ha många anmälda besökare. 
För varje anmälan behöver verksamheten veta vilken besökare som anmält sig, 
vilket evenemang anmälan gäller och när anmälan gjordes.

## Entiteter
- Visitor
- Registration
- Organizer
- Event
- Venue
- Category

## Viktiga relationer
- En visitor kan ha många registrationer.
- En registration måste tillhöra en visitor.

- En Organizer kan skapa många event.
- Ett event måste tillhöra en organizer.

- Ett event har många registrationer.
- En registration måste tillhöra en event.

- En category kan ha många event.
- Ett event måste tillhöra en category.

- En venue kan ha många event.
- Ett event måste tillhöra en venue.

## Antaganden
- En registration kan inte skapas utan visitor.
- Visitor kan finnas utan registration.

- Ett event kan inte skapas utan organizer, venue och category.
- Ett event kan finnas utan registration.

- En category och venue kan finnas utan att vara kopplad till event.

## Öppna frågor
- Vilka uppgifter behöver vi lagra om en besökare (räcker namn, telefonnummer och e-post)?
- Behövs flera kategorier eller arrangörer per evenemang?
- Hur representeras digitala evenemang?
- Hur hanteras avbokningar och inställda evenemang?
- Får en besökare anmäla sig flera gånger till samma evenemang?
- Behövs maxantal platser eller sista anmälningsdatum?
- Hur identifieras återkommande besökare?
