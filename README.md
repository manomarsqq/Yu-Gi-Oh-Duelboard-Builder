# Duel Board Builder

Make Yu-Gi-Oh! duel boards for your AO3 fic by clicking and typing — no code to write.

**Open the builder:** `index.html` (when GitHub Pages is on, it lives at `https://<your-username>.github.io/duel-board-builder/`).

## What it does

- Shows the whole field: both duelists' LP, hands, Deck/Extra Deck/Graveyard piles, Monster, Spell & Trap, Field and Extra Monster Zones, phase and turn.
- **Look up** fills in a card's type, attribute, level, ATK/DEF and text by name, from [YGOPRODeck](https://ygoprodeck.com/api-guide/)'s free card database.
- Cards in hand can be kept secret or **revealed** face-up.
- Real card pictures: on the field, as a pop-up when a reader points at a card, or in the info panel. The builder checks each picture link and explains what's wrong with a bad one.
- Pointing at a card can swap the info panel to that card's details.
- **Copy board code** gives you HTML to paste into your chapter (in AO3's HTML mode). Paste a board back in to keep editing it next turn.

## Using it on AO3

1. **Once per work:** copy the Work Skin (the button in the builder, or `ao3-work-skin.css`), create it under *Dashboard → Skins → My Work Skins → Create Work Skin*, and select it on your work's Edit page.
2. Build your board, press **Copy board code**, and paste it into your chapter with the editor in **HTML** mode.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The builder. Everything it needs is inside this one file. |
| `ao3-work-skin.css` | The AO3 Work Skin, with comments explaining every part. |
| `duel-board-template.html` | A hand-written, commented example board, for anyone who wants to edit the HTML directly. |

## Pictures

AO3 can't store images, so upload card pictures to an image host and paste the **direct** link (it usually ends in `.png` or `.jpg`). YGOPRODeck asks people not to link its card pictures directly, so save them and re-host them instead.

## Where to host the builder

The card lookup needs to reach `db.ygoprodeck.com`. It works from GitHub Pages and when the file is opened straight from your computer. Some hosts block it: Neocities' free plan, for example, only lets pages talk to their own site, so Look up fails there (everything else still works).
