# 💓 Výpočet tepových zón (Shiny App)

Tato jednoduchá Shiny aplikace ti umožní spočítat **tepové zóny** na základě dvou metod:

- **Maximální srdeční frekvence (Max HR)**
- **Laktátového prahu (LTHR)**

Na základě tebou zadané hodnoty (v bpm) ti aplikace zobrazí přehlednou tabulku s rozsahem jednotlivých tréninkových zón – včetně jejich popisu a procentuálního rozmezí.

---

## 🧠 Co aplikace umí

- Zvolit si metodu výpočtu (`Max HR` nebo `LTHR`)
- Zadáním srdeční frekvence získáš:
  - Pět základních tréninkových zón
  - Procentuální rozmezí
  - Vypočtené hodnoty spodní a horní hranice každé zóny

---

## 🚀 Vyzkoušej online

Aplikace běží přímo v prohlížeči.

👉 [Spustit aplikaci online](https://ondrejklubal.github.io/tepove-zony-app/)

> ⚠️ Žádný server není potřeba – vše běží čistě v prohlížeči jako statická stránka.

---

## 🛠️ Technické detaily

- Vytvořeno v `R` pomocí `shiny`
- Exportováno pomocí `shinylive` jako čistě front-endová aplikace
- Kompatibilní s GitHub Pages
