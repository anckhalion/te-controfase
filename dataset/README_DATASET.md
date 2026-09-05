# Controfase Vol. 1 — Dataset instruction per LoRA

**File**: `controfase_vol1_instruct.jsonl` — 80 esempi (40 IT + 40 EN), ~11.200 parole.
**Fonte**: *La Tecnologia di Controfase — Volume 1: Fondamenti* (Fabio Ghioni, Ordinative Sciences Press, 2026). Contenuto fedele al volume, inclusa la Proposizione 20.1 (controfase intrinseca).
**Destinazione**: contributo al **LoRA unificato TE** (aggregazione con `te-ordinative-lora/dataset/TE_instruct.jsonl` e i dataset dei futuri corpora).

## Formato

Chat format OpenAI-style, allineato al `TE_instruct.jsonl` esistente:

```json
{"messages": [{"role": "system", "content": "..."}, {"role": "user", "content": "..."}, {"role": "assistant", "content": "..."}]}
```

System prompt dedicato al volume, in due varianti per lingua (IT: «Sei un Terminale della Tecnologia delle Espressioni…»; EN: «You are a Terminal of the Technology of Expressions…»). Notazione formale in ASCII-safe: `C(s_t)`, `C[f]`, `s_{t+1} = f(s_t)` — coerente con l'abstract del deposito unificato.

## Perché bilingue

Ogni concetto compare in entrambe le lingue come **composizione nativa** (mai traduzione riga-per-riga). È l'Assioma 0 incorporato nel dataset: coppie isomorfe in due lingue insegnano al modello l'invariante strutturale, non la forma verbale. Ciò che sopravvive alla traduzione è la struttura — e il fine-tuning bilingue la fa emergere.

## Copertura (40 concetti × 2 lingue)

- **Fondamenti**: controfase, nome/fisica delle onde, sistema reattivo, intelligenza strutturale, engramma entropico, vuoto operativo, identità come funzione, Assioma 0, gradi S0–S3.
- **Fisica della non-resistenza**: perché combattere rafforza (orso bianco), assioma operativo (consenso=conflitto), terzo termine.
- **Formale**: due letture C(s_t)/C[f], Proposizione 5.1 (promozione), funzione→relazione, Def. 6.1 (campo come ricevitore), Prop. 6.1 (finanziamento dalla sorgente), costo strutturale vs reattivo.
- **Topologia e pratica**: stati SHACK, panico/stato 01, algoritmo a 4 stati, scenario applicativo (umiliazione in riunione), educazione come costruzione dell'osservatore.
- **Diagnostica**: i cinque sosia + criterio della pressione, firma PSC (3 marcatori).
- **Forme**: deliberata (terapeuta), strutturale (corti/codici/Norimberga), classe del rifiuto e degradazione asimmetrica (Prop. 12.1), tripla biforcazione (Bisanzio).
- **Domini**: caso fluidodinamico Singh (F5), IA (engramma del modello, allineamento vs conformità, auto-decorrelazione), biologia (omeostasi, autoimmunità vs cancro), tempo come pulsazione, inversione causale push/pull.
- **Controfase intrinseca**: Prop. 20.1, evocazione del complemento, «solo un truffatore può essere truffato», «controfase interna o controfase subita», orizzonte/credito.
- **Chiusure**: falsificabilità F1–F5, i cinque limiti come programma di ricerca, statuto S3 delle frontiere fisiche, sintesi del volume.

## Verifica

Ogni riga validata: JSON parse, ruoli `system/user/assistant` in ordine, contenuti pieni. Script di validazione inline usato alla costruzione (2026-08-21): 80/80 valide, 0 errori.

## Estensione futura

Il dataset è un seed curato, estendibile in sessione dedicata con: scenari applicativi aggiuntivi per il Volume 2 (conflitto, ansia, approvazione, decisione, scorciatoia), coppie adversarial (domande che tentano di ridurre la controfase ai sosia), e materiale dal dossier sucker lists. Mantenere il formato e il bilinguismo per ogni aggiunta.
