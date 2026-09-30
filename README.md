# Borozdov Quarto

A theme from the Borozdov collection. Two faces — light **Marginalia**, a research
journal on parchment and cream, and dark **Footnote**, the same journal read by
lamplight. Serif display headings in ink, warm orange for what you follow, a dry
olive for tags and labels.

![Borozdov Quarto in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/quarto/main/screenshots/light.png)

![Borozdov Quarto in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/quarto/main/screenshots/dark.png)

## Principles

- **The serif is display-only.** Quarto Serif, an upright text serif, carries the
  title and the top three heading levels; the platform's own sans handles body
  text and UI, and its mono sets the eyebrow labels.
- **One accent, two shades.** Warm orange is the action colour — links, the open
  file, the caret — and never a surface. A dry olive marks tags and secondary
  emphasis, so the page stays close to monochrome until you need to follow
  something or find it again.
- **Parchment desk, cream page.** The sidebar sits on Parchment, the editor on
  Cream, and anything raised — code, tables, modals — on Bone, the lightest tier.
- **One filled shape.** Every button is a square ghost with a hairline rim except
  the one that matters, a full pill filled with ink — never repeated twice in the
  same view.
- **Eyebrows.** Table headers, property names and the two smallest heading levels
  read as small tracked capitals in the mono face, the way a research log dates
  and signs each entry.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts tinted by type through Obsidian's own colour mixing, not a flat card
- Tags and property pills in olive, square corners to match the rest of the chrome
- Tables framed once, at the table, never doubled at the cell edge
- Quiet editing: no focus ring around the note, its title or form fields while you
  type; property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Quarto**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/quarto/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Quarto/`, then choose Borozdov Quarto under
Settings → Appearance → Themes.

## Font

Quarto Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font
License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic
subset of Linguistics Pro Regular (© 2016 Stefan Peev, Context Ltd), renamed
because the original's ChangeLog declares it a Reserved Font Name. One upright
weight, for the title and the top three heading levels only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Маргиналия» — стол
исследователя на пергаменте и кремовой бумаге, и тёмный «Сноска» — тот же стол при
свете лампы. Прямой антиквенный шрифт для заголовков (Quarto Serif), тёплый оранжевый
для того, что вы выбираете, и сухой оливковый для ярлыков и тегов. Устанавливается из
каталога: Настройки → Оформление → Темы → Настроить → Borozdov Quarto → Установить и
применить.
