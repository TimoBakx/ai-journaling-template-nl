# 📚 AI-Powered Journalling & Personal Growth System

Een gestructureerd systeem voor persoonlijke en professionele ontwikkeling door dagelijks journallen met AI-ondersteuning. Dit template helpt je om groei zichtbaar te maken, patronen te herkennen en betekenisvolle reflecties vast te leggen.

## 🎯 Doel

Dit journalling systeem is ontworpen om:
- **Persoonlijke en professionele groei bij te houden** door gestructureerde reflectie
- **Inzichten te bewaren** uit dagelijkse ervaringen, gesprekken en leermomenten
- **Patronen te herkennen** in je denken, gedrag en ontwikkeling
- **Samen te werken met AI** voor verbeterde zelfkennis en begeleiding
- **Een doorzoekbaar archief op te bouwen** van je gedachten en leerervaringen
- **Groei zichtbaar maken** voor evaluaties, gesprekken en carrière-ontwikkeling

### 💡 Waarom Dit Systeem?

Subtiele maar waardevolle groei blijft vaak onzichtbaar in traditionele evaluatiesystemen. Door systematische documentatie van:
- **Dagelijkse ervaringen** en concrete gebeurtenissen
- **Groeimomenten** en doorbraken (groot en klein)
- **Patronen** in je gedrag, denken en samenwerking
- **Skills evolutie** over tijd heen

Creëer je een **evidence base** die je werkelijke ontwikkeling toont. Deze aanpak helpt je niet alleen jezelf beter te begrijpen, maar ook je waarde en groei zichtbaar te maken voor anderen.

## 🗂️ Structuur

```
notes/
├── .cursor/
│   └── rules/                 # AI Coach configuratie en regels
│       ├── ai-coach-persoonlijkheid.mdc  # Persoonlijkheid en karakter van je AI coach
│       ├── ai-coach-rol.mdc              # Rol en functies van je AI coach
│       ├── algemene-regels.mdc           # Project structuur en werkwijze
│       ├── gebruikersprofiel.mdc         # Verwijzing naar profiel directory
│       ├── journalling-regels.mdc        # Dagelijkse journalling werkwijze
│       ├── reflectie-regels.mdc          # Einde dag reflectie methodiek
│       └── evaluatie-regels.mdc          # Wekelijkse evaluatie aanpak
├── profiel/                   # Persoonlijke assessments en profielen (optioneel)
│   ├── big-five.md            # Big Five persoonlijkheidsassessment
│   ├── disc.md                # DISC gedragsanalyse  
│   ├── human-design.md        # Human Design body graph
│   ├── neurodivergence.md     # Neurodivergente eigenschappen
│   └── professional.md        # Professionele achtergrond en expertise
├── werk-evaluaties/           # Performance reviews en groeiplannen (optioneel)
│   ├── [DATUM]-jaargesprek.md            # Jaarlijkse gesprekken
│   ├── [DATUM]-halfjaargesprek.md        # Halfjaars check-ins
│   └── persoonlijke-groei-plan-[JAAR].md # Groeiplannen
├── journal/                   # Dagelijkse journalling en reflectie
│   ├── [JAAR]/                # Jaar directory (bijv. 2025/)
│   │   └── [WEEK]/            # Week directory (bijv. 45/)
│   │       ├── 1-maandag-[JAAR]-[MAAND]-[DAG].md
│   │       ├── 2-dinsdag-[JAAR]-[MAAND]-[DAG].md
│   │       ├── 3-woensdag-[JAAR]-[MAAND]-[DAG].md
│   │       ├── 4-donderdag-[JAAR]-[MAAND]-[DAG].md
│   │       ├── 5-vrijdag-[JAAR]-[MAAND]-[DAG].md
│   │       ├── weekevaluatie.md          # Wekelijkse reflectie
│   │       └── checkin.md (optioneel)    # Voor gesprekken met leidinggevende
│   ├── daily-journal-template.md         # Template voor dagelijkse entries
│   ├── weekly-review-template.md         # Template voor week evaluaties
│   └── checkin-template.md               # Template voor check-in rapportages
├── projecten/                 # Project context en documentatie (optioneel)
│   ├── _template.md           # Template voor nieuwe projecten
│   └── [project-naam].md      # Project details en reflecties
└── mensen/                    # Collega's en samenwerkingspartners (optioneel)
    ├── _template.md           # Template voor nieuwe personen
    └── [naam].md              # Notities over individuen
```

### 📅 Week Structuur Voorbeeld

Elke week volgt een consistente structuur binnen `journal/[JAAR]/[WEEKNUMMER]/`:

```
journal/2025/45/
├── 1-maandag-2025-11-03.md
├── 2-dinsdag-2025-11-04.md
├── 3-woensdag-2025-11-05.md
├── 4-donderdag-2025-11-06.md
├── 5-vrijdag-2025-11-07.md
└── weekevaluatie.md
```

Weeknummers volgen de ISO 8601 standaard (gebruik `date +%V` op Unix systemen).

## 🚀 Aan de Slag

### 1. Configureer Je AI Coach
Pas de AI Coach configuratie aan in `.cursor/rules/`:
- **`ai-coach-persoonlijkheid.mdc`** - Definieer het karakter en de emotionele houding van je AI coach
- **`ai-coach-rol.mdc`** - Bepaal de functie en activiteiten van je AI coach binnen dit project
- **`algemene-regels.mdc`** - Basis projectstructuur en werkwijze (pas aan naar jouw situatie)
Veel placeholders staan tussen [blokhaken], pas die vooral aan (m.u.v. de template bestanden).

### 2. (Optioneel) Vul Je Profielen In
De `profiel/` directory helpt je AI coach je beter te begrijpen:
- **`big-five.md`** - Big Five persoonlijkheidsassessment
- **`disc.md`** - DISC gedragsanalyse  
- **`human-design.md`** - Human Design body graph
- **`neurodivergence.md`** - Neurodivergente eigenschappen
- **`professional.md`** - Professionele achtergrond en expertise

Hoe meer context je AI coach heeft, hoe beter de begeleiding!

### 3. Begin Met Journallen
Start je eerste dagelijkse journal entry:
1. Creëer een directory structuur: `journal/[JAAR]/[WEEKNUMMER]/`
2. Gebruik `journal/daily-journal-template.md` voor je eerste entry
3. Deel je gedachten, ervaringen en gebeurtenissen met je AI coach
4. Reflecteer samen aan het einde van de dag

### 4. Wekelijkse Evaluatie
Aan het einde van elke week:
1. Gebruik `journal/weekly-review-template.md` voor je weekevaluatie
2. Analyseer patronen en inzichten met je AI coach
3. Koppel ervaringen aan je groeidoelen (indien van toepassing)
4. Bereid check-ins met leidinggevenden voor (indien gewenst)

### 5. (Optioneel) Gebruik Mensen & Projecten
- **`mensen/`** - Documenteer collega's, samenwerkingspatronen en teamdynamiek
- **`projecten/`** - Houd project context bij en link naar journal entries
- **`werk-evaluaties/`** - Bewaar performance reviews en groeiplannen

## 🤝 Samenwerking met AI

Dit systeem is ontworpen om naadloos te werken met AI-ondersteuning (zoals Cursor, ChatGPT, Claude):
- **Context-rijke gesprekken** - Je profielen en geschiedenis bieden dieper begrip
- **Patroonherkenning** - AI helpt trends in je gedachten en groei te identificeren
- **Gepersonaliseerde begeleiding** - Aanbevelingen gebaseerd op je specifieke situatie
- **Gestructureerde reflectie** - Frameworks voor betekenisvolle groei
- **Geheugen functie** - Terugverwijzen naar eerdere notities en patronen

## 📝 Journalling Workflow

### Dagelijkse Routine
1. **Start je dag** - Vul de "🎯 Gepland" sectie met je taken
2. **Door de dag heen** - Voeg gebeurtenissen toe aan "📝 Dagverloop"
3. **Einde dag** - Reflecteer samen met je AI coach in "🔍 Einde Dag - Reflectie"
4. **Taken voor Later** - Noteer wat niet vandaag gebeurt

### Natuurlijke Flow
- **Wees authentiek** - deel wat er op je mind is, zonder filter
- **Geen perfectie nodig** - ruwe gedachten zijn prima, structuur komt vanzelf
- **Vraag door** - laat je AI coach helpen met verheldering
- **Maak verbindingen** - link naar projecten, mensen en eerdere entries

### AI Coach Rol
Je AI coach helpt je met:
- Gedachten organiseren in gestructureerde notities
- Verhelderingsvragen stellen om inzichten te verdiepen  
- Verbindingen leggen tussen gebeurtenissen en groeipatronen
- Patronen herkennen over tijd heen
- Senior skills en competenties zichtbaar maken

## 🔍 Tips & Best Practices

### Cross-Referencing
- **Link naar projecten**: `([Project](../../projecten/project.md))` in headers en taken
- **Link naar mensen**: `[Naam](../../mensen/naam.md)` in je notities
- **Link naar eerdere entries**: Verwijs naar patronen en eerdere momenten

### Consistentie
- Gebruik de templates voor dagelijkse en wekelijkse entries
- Volg de week structuur: `journal/[JAAR]/[WEEKNUMMER]/`
- Bestandsnaming: `[DAGNUMMER]-[dag]-[JAAR]-[MAAND]-[DAG].md`

### Diepgang
- Wees specifiek in je observaties - concrete voorbeelden werken beter dan algemene uitspraken
- Vraag door bij je AI coach als iets onduidelijk is
- Koppel gebeurtenissen aan je groeidoelen (indien van toepassing)

## 🌱 Filosofie

Deze journalling aanpak is gebouwd op:
- **Veiligheid** - dit is jouw veilige ruimte voor groei en reflectie
- **Eerlijkheid** - authentiek delen zonder filter of oordeel
- **Geduld** - groei heeft tijd nodig, kleine stappen tellen
- **Nieuwsgierigheid** - blijf leren en ontdekken, stel vragen
- **Zichtbaarheid** - maak onzichtbare groei expliciet en tastbaar

---

## 🎯 Aanpassen Voor Jouw Situatie

Dit template is een **startpunt** - pas het aan naar jouw behoeften:
- Voeg extra secties toe aan de daily template die voor jou werken
- Creëer custom directories voor jouw specifieke context
- Pas de AI coach regels aan naar jouw voorkeuren
- Experimenteer met wat werkt en wat niet

**Belangrijkste tip**: Begin simpel, itereer en verfijn naarmate je meer leert over wat jij nodig hebt!

---

*Veel succes met je groeireis! 🚀✨*
