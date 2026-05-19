---
id: cane_della_morte
nome: Cane della morte
tipo: Mostruosità
dimensione: Media
allineamento: neutrale malvagio
classe_armatura: 12
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 39
  formula: 6d8 + 12
velocita:
  camminata: 12 m
caratteristiche:
  forza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  carisma:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
abilita:
  furtivita: 4
  percezione: 5
immunita_condizione:
- accecato
- affascinato
- assordato
- privo di sensi
- spaventato
- stordito
sensi:
  percezione_passiva: 15
  scurovisione: 36 m
lingue:
- nessuna
grado_sfida:
  valore: 1
  punti_esperienza: 200
  raw: 1 (PE 200; BC +2)
bonus_competenza: 2
---
## Azioni
### Multiattacco
Il cane della morte effettua due attacchi Morso.

### Morso
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 4 (1d4 + 2) danni perforanti. Se il bersaglio è una creatura, subisce il seguente effetto. *Tiro salvezza su Costituzione:* CD 12. *Primo fallimento:* il bersaglio è avvelenato. Finché lo resta, i punti ferita massimi del bersaglio non tornano alla normalità al termine di un riposo lungo. La creatura ripete il tiro salvezza ogni 24 ore trascorse e, se lo supera, l'effetto svanisce. *Fallimenti successivi:* i punti ferita massimi del bersaglio avvelenato sono ridotti di 5 (1d10).