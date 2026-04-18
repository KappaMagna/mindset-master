# Mindset Master

> **47 modi di pensiero per lavorare strategicamente con Claude.**
> Documento + skill `cognitive-modes` pronta da installare.

---

## Cosa contiene questo repo

| File | Cosa è |
|---|---|
| [`mindset-master.md`](./mindset-master.md) | Il documento completo: 47 modi cognitivi organizzati in 7 famiglie (Reasoning, Evaluative, Creative, Persona, Communication, Operational, Meta), con activation prompt per ognuno e 5 stack recipes testate. |
| [`cognitive-modes/SKILL.md`](./cognitive-modes/SKILL.md) | La skill operativa per Claude. Si attiva automaticamente quando il task richiede pensiero strategico e seleziona 1–3 modi appropriati. |
| [`LICENSE`](./LICENSE) | MIT. Usa, modifica, condividi liberamente. |

---

## Da dove viene

Il documento *Mindset Master* nasce dal lavoro di [Contento.Consulting](https://contento.consulting) sull'integrazione tra intelligenza umana e artificiale. È il risultato di anni di workshop, coaching e prompt design su Claude — distillato in 47 configurazioni cognitive che cambiano la postura con cui l'AI affronta un problema.

La skill `cognitive-modes` è la sua implementazione operativa: Claude la attiva da solo quando rileva che il task ne ha bisogno.

---

## Perché esiste

Claude di default è **ancorato all'analitico**: sicuro, strutturato, statisticamente medio. Per la maggior parte dei task di pensiero questo è sotto-prestante. I 47 modi cognitivi sono configurazioni esplicite che forzano una postura specifica *prima* della generazione.

→ La skill cambia il modo in cui Claude *pensa*, non solo cosa risponde.

---

## Come si installa la skill (2 minuti)

1. Clona o scarica il repo:
   ```bash
   git clone https://github.com/KappaMagna/mindset-master.git
   ```

2. Copia la cartella `cognitive-modes/` in `~/.claude/skills/`:
   ```bash
   cp -r mindset-master/cognitive-modes ~/.claude/skills/
   ```

3. Apri Claude Code (o Claude Desktop con plugin support). La skill è ora attiva e si auto-attiva quando incontra task strategici.

4. Test rapido — apri una nuova chat e prova:
   > *"Stiamo pensando di lanciare un nuovo prodotto. Che ne pensi?"*

   Claude dovrebbe annunciare i modi che applica (es. *"Applico Pre-mortem + Comparative + Calibration"*) prima di rispondere.

---

## Come si legge il documento

Il documento `mindset-master.md` è pensato per due livelli di lettura:

- **Lettura veloce** — vai alla *Tabella di selezione rapida* (sezione 10) e trova il modo per la tua situazione
- **Lettura profonda** — leggi le 7 famiglie in ordine, con activation prompts e insight

Lo puoi anche stampare — è formattato per essere leggibile sia a video che su carta.

---

## Approfondimento

Il caso studio completo di come è nata questa skill, le 3 decisioni di design chiave, e un toolkit di 5 skill strategiche pronte da costruire — è nella Coffee-Break Guide:

> 📘 **Claude Strategico** — *Skill avanzate per trasformare Claude da assistente medio a partner di pensiero*
> Disponibile su [contento60.gumroad.com](https://contento60.gumroad.com/)

---

## Contributi

Pull request benvenute. Se trovi un modo nuovo che funziona, una stack recipe testata sul campo, o un esempio di applicazione che vale la pena condividere — aprila.

---

*A cura di Kerstin Petrick · Contento.Consulting · 2026*
*Licenza MIT*
