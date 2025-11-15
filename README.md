# anamdotaznik.github.io
Dynamický anamnestický dotazník pro web **diagnostikaditete.cz**

**Preview:** https://strojiladam.github.io/anamdotaznik.github.io/

---

## Patch Notes

### 2.1
#### Ukládání a práce s daty
- Manuální průběžné uložení.
- Automatické průběžné ukládání.
- Manuální znovunačtení posledního automatického uložení.
- Možnost vymazání historie a aktuálního průchodu.
- **Export a import JSON souboru**:
  - Umožňuje přenést průchod mezi zařízeními.
  - Klient může přinést vyplněný JSON soubor odborníkovi.
  - Alternativa při problémech exportu do PDF (např. na telefonu) — odborník si PDF vytvoří na svém zařízení.
  - Někteří odborníci mohou upřednostnit ukládání a načítání editovatelných souborů ve formátu JSON přímo ve svém zařízení, namísto archivace výsledků ve fixním PDF.

#### Uživatelské rozhraní
- Nový úvodní a závěrečný blok s přehledem funkcí (ukládání, export, instrukce).
- Přidány nové sekce **Škola** a **Školka**.

---

### 2.0
- **Nová funkce náhledu tisku**:
  - Zobrazuje orientační vzhled budoucí tištěné nebo PDF verze.
  - Pomáhá řešit problémy exportu do PDF na mobilních zařízeních.
  - Lépe pracuje s automaticky rozbalovacími seznamy a jejich chováním při tisku.

---

### 1.1.2
- Upraven design volby „Bez odpovědi“ (červené zvýraznění, přesun na konec nabídky).
- Přidána dynamická indikace nezodpovězených otázek (puntík).
- Tištěná verze nově označuje nezodpovězené položky červenou hvězdičkou „*“.

---

### 1.1.1
- Podmíněné zobrazování nově využívá plynulou animaci.
- Sjednocen vzhled a chování napříč prohlížeči (písmo, styl aktivních polí, odstranění nativních prvků jako šipky a scrollbary).

---

### 1.1
- Nahrazení rozbalovacích seznamů přehlednějšími multiple-choice položkami včetně volby „Bez odpovědi“ („–“).
- Odpovědi jsou nyní umístěny pod otázkami pro lepší čitelnost.
- Upravená struktura zamezuje rozdělování otázek a odpovědí při exportu do PDF.
- Přidán nový informační blok *„Proč se ptáme?“*.
- Doplněna a sjednocena logika podmíněného zobrazování.
- Pole „Věk“ automaticky skloňuje jednotky (rok/roky/let; měsíc/měsíce/měsíců).
- Přidána možnost lokálního uložení, načtení a smazání průchodu (zatím testovací režim).
- Další drobná vylepšení.

---

### 1.0 (Legacy)
- Vytvoření dotazníku s jednoduchým dynamickým zobrazováním otázek
- Základní možnost tisku

---

© Adam Strojil, 2025.  
All rights reserved.
