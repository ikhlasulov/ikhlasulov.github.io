# Material 3 Expressive / Материальный выразительный дизайн

This site is adapted from
[Velmi1337/velmi1337.github.io](https://github.com/Velmi1337/velmi1337.github.io)
(GPL-3.0-only, by Velmi1337) and rewritten for the projects of
[@ikhlasulov](https://github.com/ikhlasulov). The layout, palette system and
progressive enhancements are kept; copy, project cards, screenshots and
identity are new.

The website uses HTML, CSS and small progressive JavaScript enhancements
inspired by Google's Material 3 Expressive. It is a web implementation, not the
Android Compose component library or an imported Figma document.

## Design references

- [Material 3](https://m3.material.io/)
- [Color roles](https://m3.material.io/styles/color/roles)
- [Motion specifications](https://m3.material.io/styles/motion/overview/specs)
- [Material 3 in Compose](https://developer.android.com/develop/ui/compose/designsystems/material3)
- [Official design kit](https://www.figma.com/community/file/1035203688168086460/material-3-design-kit)

Four seed colors are converted into light/dark tonal palettes by Google's
`@material/material-color-utilities` using `SchemeTonalSpot`. `assets/tokens.css`
is the generated output and is kept as-is; there is no build step in this
repository. The interface uses semantic surface/container/on-color roles,
expressive rounded shapes, connected controls, large variable typography and
the documented expressive spatial/effects easing curves. Desktop navigation
becomes bottom navigation on small screens.

Appearance preferences stay in localStorage on the device. There is no
analytics, polling, remote font request or runtime GitHub API request. Core
content and navigation work without JavaScript. Reveal animations run once;
reduced-motion preferences disable movement. Modal controls use native dialog
semantics and keyboard dismissal.

## Sources and licenses

- Website code and copy: GPL-3.0-only, root `LICENSE`. Adapted from
  Velmi1337/velmi1337.github.io (GPL-3.0-only); see the notice above.
- Google Sans Flex and Roboto Flex are self-hosted, obtained from
  [expressive-profile](https://github.com/metawka/expressive-profile). Their
  exact OFL notices are in `assets/fonts/`.
- Rounded Material Symbols: Google, Apache-2.0, see `LICENSES/Apache-2.0.txt`.
  Sprite paths come from `@material-symbols/svg-400` 0.48.2.
- Shape inspiration: expressive-profile, MIT, see
  `LICENSES/MIT-Expressive-Profile.txt`.
- Avatar: the author's own photo.
- Screenshots: taken from the author's own projects, Namaz (GPL-3.0-only) and
  OpenRPM (GPL-3.0-only).

## Русский

Сайт адаптирован из проекта
[Velmi1337/velmi1337.github.io](https://github.com/Velmi1337/velmi1337.github.io)
(GPL-3.0-only) и переписан под проекты
[@ikhlasulov](https://github.com/ikhlasulov). Сохранены вёрстка, система
палитр и прогрессивные улучшения; текст, карточки проектов, скриншоты и
идентичность — новые.

Оформление следует принципам Material 3 Expressive: смысловые роли цвета,
четыре палитры со светлой и тёмной темой, выразительные формы, крупная
типографика, адаптивная навигация и анимации по спецификации Google. Для веба
используются HTML/CSS; Android Compose и файл Figma не встроены в сайт.

Текст и ссылки работают без JavaScript. Скрипт добавляет выбор оформления и
короткие анимации. Настройки сохраняются только в браузере; аналитики,
фонового опроса и внешней загрузки шрифтов нет. При включённом уменьшении
движения анимации отключаются.

Ссылки на официальные материалы и лицензии всех заимствованных ресурсов
приведены выше.
