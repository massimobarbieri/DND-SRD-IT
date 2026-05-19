---
id: behir
nome: Behir
tipo: Mostruosità
dimensione: Enorme
allineamento: neutrale malvagio
classe_armatura: 17
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 168
  formula: 16d12 + 64
velocita:
  camminata: 15 m
  scalata: 15 m
caratteristiche:
  forza:
    punteggio: 23
    modificatore: 6
    tiro_salvezza: 6
  destrezza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  costituzione:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  intelligenza:
    punteggio: 7
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  carisma:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
abilita:
  furtivita: 7
  percezione: 6
immunita_danni:
- fulmine
sensi:
  percezione_passiva: 16
  scurovisione: 27 m
lingue:
- Draconico
grado_sfida:
  valore: 11
  punti_esperienza: 7200
  raw: 11 (PE 7.200; BC +4)
bonus_competenza: 4
---
## Azioni
### Multiattacco
Il behir effettua un attacco Morso e usa Stritolare.

### Morso
*Tiro per colpire in mischia:* +10, portata 3 m. *Colpito:* 19 (2d12 + 6) danni perforanti più 11 (2d10) danni da fulmine.

### Soffio di fulmini (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 16, tutte le creature in una linea lunga 27 metri e larga 1,5 metri. *Fallimento:* 66 (12d10) danni da fulmine. *Successo:* danni dimezzati.

### Stritolare
*Tiro salvezza su Forza:* CD 18, una creatura di taglia Grande o inferiore che il behir è in grado di vedere entro 1,5 metri. *Fallimento:* 28 (5d8 + 6) danni contundenti. Il bersaglio è afferrato (CD 16 per sfuggire) ed è trattenuto finché la presa perdura.

## Azioni bonus
### Inghiottire
*Tiro salvezza su Destrezza:* CD 18, una creatura di taglia Grande o inferiore afferrata dal behir (il behir può inghiottire solo una creatura alla volta). *Fallimento:* Il behir inghiotte il bersaglio, che non è più afferrato. Finché è inghiottita, la creatura è accecata e trattenuta, beneficia di copertura totale contro gli attacchi e altri effetti al di fuori del behir, e subisce 21 (6d6) danni da acido all'inizio di ogni turno del behir. Se il behir subisce 30 o più danni in un singolo turno dalla creatura inghiottita, deve superare un tiro salvezza su Costituzione con CD 14 alla fine di quel turno, altrimenti rigurgita la creatura, che cade prona in uno spazio entro 3 metri dal behir. Se il behir muore, la creatura inghiottita non è più trattenuta e può fuggire dal cadavere usando 4,5 metri di movimento, uscendo prona.