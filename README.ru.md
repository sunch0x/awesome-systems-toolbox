# Awesome Systems Toolbox

Темы: крипта, AI, код, OSINT, дизайн и повседневные жизненные системы. Библиотека инструментов, ссылок и рабочих процессов, которые я реально использую и продолжаю обновлять.

> Это место, где я упорядочиваю свой стек инструментов, чтобы быстро ими пользоваться самому, не вспоминая каждый раз с нуля.
> И заодно — открытая полка: если тебе пригодятся какие‑то из этих штук, бери и используй под свои проекты  
> Also available in: [English version](./README.md)

---

## Inspiration

Я делаю это как публичный toolbox, а не приватный склад.

Мне не хочется, чтобы ты, мой дорогой тратил часы на тот же ресёрч, который я уже однажды проделал.  
Благодаря данной репе - ты можешь:

- собрать набор проверенных инструментов под новый проект за минуты, а не часы  
- переиспользовать паттерны для UI, инфраструктуры, крипты, OSINT и «лайф‑тем»  

Это мой способ чуть‑чуть «отдать обратно»: собрать то, что реально сработало для меня, отфильтровать шум и оставить только те штуки, которые помогли доводить проекты до конца

---

## Some pointers

- Это субъективная и личная подборка.  
  Она не претендует на полноту или «объективность». Если инструмент здесь, значит он:
  - пережил хотя бы один реальный сценарий использования у меня, или  
  - выглядит достаточно сильным, чтобы в ближайшее время его протестировать.

- Разделы упорядочены не в топ градациях, просто сверху-вниз :
  - Design / vibe‑UI  
  - AI & coding  
  - Crypto  
  - OSINT  
  - Life infrastructure  

- Я предпочитаю:
  - инструменты, которые более‑менее уважают приватность и не являются чистым surveillance‑adware  
  - продукты с понятной практической пользой, а не просто очередную блестящую AI‑обёртку

- Часть инструментов может быть платной или закрытой, если они по‑настоящему полезны.  


---

## Contents

## Contents

- [Design / Vibe UI](#design--vibe-ui)  
- [AI & Coding](#ai--coding)  
  - [AI coding environments](#ai-coding-environments)  
  - [General AI / chat](#general-ai--chat)  
  - [Dev tooling & automation](#dev-tooling--automation)  
- [Crypto](#crypto)  
  - [Wallets & key management](#wallets--key-management)  
  - [On‑chain analytics & explorers](#on-chain-analytics--explorers)  
  - [Market data & rankings](#market-data--rankings)  
  - [Infra / privacy / accounts](#infra--privacy--accounts)  
  - [Numbers, SIMs, cards](#numbers-sims-cards)  
- [OSINT](#osint)  
  - [People / profiles](#people--profiles)  
  - [Domains, IP, infrastructure](#domains-ip-infrastructure)  
  - [Crypto OSINT](#crypto-osint)  
- [Life Infrastructure](#life-infrastructure)  
  - [Notes & knowledge](#notes--knowledge)  
  - [Health / tracking](#health--tracking)  
  - [Ops / privacy / money](#ops--privacy--money)  
- [Contributing](#contributing)


---

## Design / Vibe UI

### Galleries & references

| Tool / Site   | Link                                            | What it’s for                                                                                           |
|---------------|-------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| Mobbin        | https://mobbin.com                              | Разбор реальных продуктовых флоу: дашборды, логин, биллинг, настройки, списки, формы                   |
| Dribbble      | https://dribbble.com                            | Визуальный вайб: hero‑секции, концепты, стили иллюстраций                                              |
| Lapa Ninja    | https://www.lapa.ninja                          | Структуры лендингов для SaaS/стартапов (hero, фичи, прайсинг, FAQ, футер)                              |
| Landingfolio  | https://www.landingfolio.com                    | Готовые секции (pricing, signup, testimonials, 404, empty states) как паттерны                         |
| Footer.design | https://www.footer.design                       | Быстрый выбор вменяемого футера вместо изобретения с нуля                                              |

### Components & micro‑UI

| Tool / Site      | Link                             | What it’s for                                                                 |
|------------------|----------------------------------|-------------------------------------------------------------------------------|
| Reactbits        | https://reactbits.dev           | Анимированные React‑компоненты: текст, фон, курсоры, карточки                |
| Uiverse          | https://uiverse.io              | Мелкие UI‑элементы (кнопки, тогглы, лоадеры, инпуты), которые сразу копируешь |
| Realtime Colors  | https://realtimecolors.com      | Пробовать цветовые схемы на реальном UI и экспортировать в CSS/Tailwind     |

### Icons & illustrations

| Tool / Site         | Link                                                                 | What it’s for                                                                                 |
|---------------------|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Flaticon            | https://www.flaticon.com                                            | Большие наборы иконок в SVG/PNG/шрифтах, быстрые правки в веб‑редакторе                      |
| Phosphor Icons      | https://phosphoricons.com                                           | Цельное много‑весовое икон‑семейство для продукта, есть React/Vue/Svelte + Figma             |
| Feather Icons       | https://feathericons.com                                            | Минималистичный open‑source набор для лёгких интерфейсов                                     |
| Icons8              | https://icons8.com                                                  | Иконки, иллюстрации и фото для UI и маркетинговых материалов                                 |
| Icons8 Figma plugin | https://www.figma.com/community/plugin/791103617505812222/icons8-icons-illustrations-photos | Кидать ассеты Icons8 прямо в Figma без переключений                                          |

### Identity / logo

| Tool / Site   | Link                             | What it’s for                                                     |
|---------------|----------------------------------|-------------------------------------------------------------------|
| Figr Identity | (Figma plugin)                   | Автосборка айдентики и дизайн‑токенов прямо в Figma               |
| Higgsfield    | https://higgsfield.ai            | Генерация hero‑картинок и бесшовных видео‑лупов / промо через AI  |
| Logo Diffusion| https://logodiffusion.com        | Быстрый перебор логотипов через диффузию перед ручной полировкой  |

### 3D, animation & FX

| Tool / Site    | Link                             | What it’s for                                                                 |
|----------------|----------------------------------|-------------------------------------------------------------------------------|
| Spline         | https://spline.design           | 3D‑объекты и сцены для hero‑секций и интерактивных визуалов                   |
| Unicorn Studio | https://www.unicorn.studio      | No‑code WebGL‑эффекты и фоновые анимации поверх существующего UI             |
| Rive           | https://rive.app                | Состояние‑зависимые иконки, лоадеры и микропереходы, которые реагируют на апку|
| Paper Animator | https://paperanimator.com       | Быстрые “бумажные” анимации для выделяющихся секций                          |

### Design tools & Figma

| Tool / Site    | Link                             | What it’s for                                                                 |
|----------------|----------------------------------|-------------------------------------------------------------------------------|
| Figma          | https://www.figma.com            | Главный центр: дизайн, компоненты, прототипы                                 |
| HTML.to.design | https://www.html.to.design       | Затянуть существующий сайт в Figma как редактируемую разметку               |
| Flamel 3D      | (Figma plugin)                   | Генерация консистентных 3D‑наборов иконок через AI прямо в Figma            |
| Figma AI (Make)| —                                | Черновики экранов и React‑кода из текстового описания приложения            |


---

## Contributing

Я всегда рад новым находкам.
Если кажется, что какой‑то инструмент сюда хорошо вписывается:

- создай issue с ссылкой  
- добавь 1–2 предложения, почему это реально годно и в какой раздел это положить

---

## Stay in touch

Если интересно посмотреть, как я на практике пользуюсь этой базой, и в принципе мой контент и творчество:

- **TWITTER / X (ENG):** https://x.com/@sunch0x  
- **Telegram (RU):** https://t.me/sunch_exe  
- **Obsidian / notes repo:** https://publish.obsidian.md/sunch0x.dev

---

## License
Ничего душного, просто ссылайся на меня - мне будет приятно, что мой труд используют себе во благо. Ниже чуть подробнее:
Этот репозиторий распространяется по лицензии [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
Разрешается:
- **Делиться** — копировать и распространять материалы на любом носителе и в любом формате  
- **Адаптировать** — ремиксить, модифицировать и использовать в своих проектах, в том числе коммерческих  

На следующих условиях:
- **Attribution** — нужно указывать авторство, ссылку на этот репозиторий.  
  Простой вариант:
  > Based on the “awesome-systems-toolbox” curated by [sunch0x](https://github.com/sunch0x).
