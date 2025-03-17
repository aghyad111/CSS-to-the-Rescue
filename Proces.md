# Procesverslag Ambient Light Project

## Codestructuur en leesbaarheid
- HTML is semantisch opgebouwd met duidelijke elementen
- CSS is georganiseerd in logische lagen via @layer
- Code is consistent geïndenteerd voor betere leesbaarheid
- Commentaar toegevoegd bij complexe functionaliteit
- Bronnen zijn vermeld bij hergebruikte of geïnspireerde code

## Wekelijkse voortgang

### Week 1: Conceptontwikkeling
- Oorspronkelijk idee: een lamp bedieningspaneel
- Aanpak: onderzoeken van CSS-selectors en moderne technieken
- Uitdagingen: bepalen van de juiste aanpak zonder JavaScript
- Beslissingen: keuze voor radio buttons als schakelaar voor verschillende lichtkleuren

### Week 2-3: Typografie Panel (Verkeerde richting)
- Focus op een typografie bedieningspaneel
- Geïmplementeerde functies: lettertype selectie, tekstgrootte aanpassingen
- Toegepaste technieken: CSS :has() selector, CSS nesting
- Feedback tijdens voortgangsgesprek: verkeerde interpretatie van de opdracht

### Week 4: Switch naar Ambient Light Panel
- Terug naar oorspronkelijke idee: lamp bedieningspaneel
- Herontwerp van project volgens opdrachtcriteria
- Implementatie van:
  - Selector-first CSS aanpak
  - Minimaal gebruik van classes (slechts één class gebruikt)
  - CSS nesting en @layer architectuur
  - Container queries voor responsiviteit
  - Pseudo-elementen voor visuele details

### Technische uitdagingen en oplossingen
- Uitdaging: Lichteffecten creëren zonder JavaScript
  - Oplossing: Gebruik van CSS transitions en combinators (~)
- Uitdaging: Realistische reflecties op lamp
  - Oplossing: Pseudo-elementen (::before, ::after) voor hoogtepunten
- Uitdaging: Dynamische kleurveranderingen
  - Oplossing: CSS variabelen gecombineerd met radio inputs

## Bronnen
- Documentatie: MDN Web Docs voor CSS nesting en container queries
- Inspiratie: [Plafondlamp illustratie op Freepik voor het visuele ontwerp van de lamp](https://nl.freepik.com/premium-vector/plafondlamp-op-gele-achtergrond_69439181.htm)
- AI assistentie: ChatGPT voor het oplossen van specifieke CSS-uitdagingen en suggesties
- Workshops: has() selector workshop door Krijn. Gradients workshop door Sanne.


## Reflectie
- Grootste leerpunt: Het belang van goed begrijpen van de opdrachtcriteria en het stellen van gerichte vragen tijdens voortgangsgesprekken
- Technische groei: Beter begrip van moderne CSS-mogelijkheden zoals CSS nesting, @layer, geavanceerde selectors, container queries, pseudo-elementen en custom properties
- Aanpassingsvermogen: Snel kunnen schakelen naar een nieuwe richting en effectief toepassen van eerder opgedane kennis
- Persoonlijke ontwikkeling: Verbetering in het plannen van mijn werk en het stellen van prioriteiten bij beperkte tijd
- Toekomstige verbeteringen: Complexere lichteffecten, meer interactiemogelijkheden en betere integratie van typografische elementen
