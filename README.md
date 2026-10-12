<p align="center"><a href="https://ghostnever-lkm.github.io/">🌐 Официальный сайт и портфолио</a></p>

<h1 align="center">👋 Привет, я GhosTnever</h1>

<p align="center"><b>Создаю QA-инструменты для игровых модов, локализаций и разработки</b></p>
<p align="center">Делаю локальные Python CLI, GitHub Actions и браузерные приложения, а также плагины для Codex и DeepSeek Harness: code review, onboarding репозиториев, диагностика CI и документация по коду.</p>
<p align="center"><b>Технологии:</b> Python · JavaScript · HTML/CSS · GitHub Actions · Node.js · Rust/WASM (в поддерживаемом open-source fork)</p>
<p align="center"><a href="https://github.com/GhosTnever-lkm?tab=repositories">Все публичные репозитории</a> · <a href="https://github.com/users/GhosTnever-lkm/projects/2/views/1">План разработки</a></p>

<p align="center">
  <a href="https://github.com/GhosTnever-lkm"><img src="https://github-readme-stats.vercel.app/api?username=GhosTnever-lkm&show_icons=true&hide_title=true&theme=transparent" alt="GitHub profile statistics" height="165"></a>
  <a href="https://github.com/GhosTnever-lkm?tab=repositories"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GhosTnever-lkm&layout=compact&langs_count=6&theme=transparent" alt="Top languages across public repositories" height="165"></a>
</p>

### 📊 Проверенные показатели флагмана · ModRelease Studio

*Сверено 2026-10-12; это показатели именно флагмана, а не всех репозиториев.*

| Метрика | Значение |
|:--|:--|
| Выпущенные версии | [67 опубликованных релизов](https://github.com/GhosTnever-lkm/modrelease-studio/releases); последний — [v0.3.62 от 2026-10-12](https://github.com/GhosTnever-lkm/modrelease-studio/releases/tag/v0.3.62) |
| Успешность CI | Последний preflight релиза v0.3.62 успешно завершился на всех пяти матричных jobs: Ubuntu 3.11/3.12/3.13, Windows 3.13 и macOS 3.13 ([workflow](https://github.com/GhosTnever-lkm/modrelease-studio/actions/runs/38185959755)) |
| Автотесты | 73 проверки в наборе v0.3.62 прошли GitHub CI; локально 70 пройдено и 3 платформенные проверки пропущены. **93% покрытия строк** зафиксировано в v0.3.57; CI блокирует результат ниже 80% |
| Проверенная ОС | Ubuntu, Windows и macOS проверены в CI; Windows/macOS используют Python 3.13 |
| Python / Node.js | Python 3.11+ заявлен; CI проверяет 3.11–3.13 на Ubuntu и 3.13 на Windows/macOS. Node.js не требуется |
| Готовая сборка | [ZIP v0.3.62](https://github.com/GhosTnever-lkm/modrelease-studio/releases/download/v0.3.62/ModRelease-Studio-v0.3.62.zip) — **41,0 KiB** |

### ⭐ Закреплённые проекты

| Работа | Что решает | Установка, пример или демо |
|:--|:--|:--|
| [**ModRelease Studio**](https://github.com/GhosTnever-lkm/modrelease-studio) — проверка модов перед релизом | Сканирует папки и ZIP, находит ошибки упаковки и секреты (включая fine-grained GitHub PAT), не раскрывая значения; экспортирует SARIF 2.1.0 | [Quick start и пример](https://github.com/GhosTnever-lkm/modrelease-studio#quick-start) · [скриншот](https://raw.githubusercontent.com/GhosTnever-lkm/modrelease-studio/v0.3.62/docs/demo.png) · [v0.3.62](https://github.com/GhosTnever-lkm/modrelease-studio/releases/tag/v0.3.62) |
| [**ModRelease Gate**](https://github.com/GhosTnever-lkm/modrelease-studio-action) — релизный gate в GitHub Actions | Запускает ModRelease Studio v0.3.62 на pull request, создаёт безопасные annotations и загружаемые JSON/Markdown/SARIF-отчёты; SARIF готов для опциональной загрузки в Code Scanning | [Quick start](https://github.com/GhosTnever-lkm/modrelease-studio-action#quick-start) · [пример policy](https://github.com/GhosTnever-lkm/modrelease-studio-action/tree/main/examples/policy-project) · [v1.0.48](https://github.com/GhosTnever-lkm/modrelease-studio-action/releases/tag/v1.0.48) |
| [**Paradox Mod Quality Gate**](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate) — единая проверка Paradox-модов | Объединяет сканеры, использует ModRelease Studio v0.3.62 и Paradox Mod Workbench v0.2.4, безопасно форматирует JSON/Markdown/CI-аннотации и экспортирует единый SARIF 2.1.0 | [README и пример workflow](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate) · [v1.0.45](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate/releases/tag/v1.0.45) |
| [**BugBundle**](https://github.com/GhosTnever-lkm/bugbundle) — локальный конструктор crash-report | Собирает заметки и логи, маскирует типовые секреты, защищает Markdown-отчёт и показывает bidi/control-символы в именах | [демо](https://ghostnever-lkm.github.io/bugbundle/) · [offline ZIP v1.0.10](https://github.com/GhosTnever-lkm/bugbundle/releases/download/v1.0.10/BugBundle-v1.0.10.zip) · [screenshot](https://raw.githubusercontent.com/GhosTnever-lkm/bugbundle/v1.0.10/docs/bugbundle-preview.png) |
| [**GameText Gate**](https://github.com/GhosTnever-lkm/game-text-gate) — QA игровых переводов | Проверяет ключи, плейсхолдеры и разметку в CSV, PO и вложенном JSON; явно экранирует Unicode line/paragraph separators в отчётах | [установка и запуск](https://github.com/GhosTnever-lkm/game-text-gate#install-and-run) · [samples](https://github.com/GhosTnever-lkm/game-text-gate/tree/v0.1.14/samples) · [скриншот отчёта](https://raw.githubusercontent.com/GhosTnever-lkm/game-text-gate/v0.1.14/docs/report-preview.png) · [v0.1.14](https://github.com/GhosTnever-lkm/game-text-gate/releases/tag/v0.1.14) |
| [**Mod Threat Lens**](https://github.com/GhosTnever-lkm/mod-threat-lens) — первичный triage модов | Локально ищет подозрительные признаки в исходниках, бинарных файлах и архивах; явно экранирует невидимые символы в text/Markdown/JSON/SARIF и не заменяет антивирус | [Quick start](https://github.com/GhosTnever-lkm/mod-threat-lens#quick-start) · [fixture](https://github.com/GhosTnever-lkm/mod-threat-lens/tree/v0.1.9/examples/fixture-mod) · [скриншот отчёта](https://raw.githubusercontent.com/GhosTnever-lkm/mod-threat-lens/v0.1.9/docs/report-preview.png) · [v0.1.9](https://github.com/GhosTnever-lkm/mod-threat-lens/releases/tag/v0.1.9) |

<p align="center">
  <a href="https://github.com/GhosTnever-lkm/modrelease-studio"><img src="https://raw.githubusercontent.com/GhosTnever-lkm/modrelease-studio/v0.3.62/docs/demo.png" alt="ModRelease Studio command-line scan example" width="47%"></a>
  <a href="https://ghostnever-lkm.github.io/bugbundle/"><img src="https://raw.githubusercontent.com/GhosTnever-lkm/bugbundle/v1.0.10/docs/bugbundle-preview.png" alt="BugBundle local crash-report builder and privacy preview" width="47%"></a>
</p>

<p align="center">
  <a href="https://github.com/GhosTnever-lkm/game-text-gate"><img src="https://raw.githubusercontent.com/GhosTnever-lkm/game-text-gate/v0.1.14/docs/report-preview.png" alt="GameText Gate v0.1.14 sample localization QA report preview" width="90%"></a>
</p>

*GameText Gate: пример отчёта по тестовым файлам — 2 ошибки и 2 предупреждения, найденные до сборки.*

<p align="center">
  <a href="https://github.com/GhosTnever-lkm/mod-threat-lens"><img src="https://raw.githubusercontent.com/GhosTnever-lkm/mod-threat-lens/v0.1.9/docs/report-preview.png" alt="Mod Threat Lens heuristic scan report using inert synthetic test strings" width="90%"></a>
</p>

*Mod Threat Lens: только синтетические строки, сканируемые без исполнения; эвристические сигналы требуют ручной проверки.*

### Быстрый старт: CLI

```bash
# Проверить папку мода и сохранить оба отчёта
python -m pip install "modrelease-studio @ git+https://github.com/GhosTnever-lkm/modrelease-studio.git@v0.3.62"
modrelease scan ./my-mod --md-out report.md --json-out report.json

# Сравнить английскую и русскую локализации
python -m pip install "game-text-gate @ git+https://github.com/GhosTnever-lkm/game-text-gate.git@v0.1.14"
game-text-gate --source locales/en.json --target locales/ru.json --report markdown
```

---

### 🛡️ Качество и безопасность игровых модов

- **ModRelease Studio v0.3.62** — проверка папки или ZIP перед выпуском: упаковка, секреты, метаданные, сравнение сборок и отчёты без локальных родительских путей; разделители строк отображаются явно, текстовый файл, выросший сверх лимита во время чтения, получает предупреждение, в folder scan не следует symlink и Windows junction, а при недоступности метаданных junction каталог исключается и получает предупреждение `READ_METADATA`; generated-папки отсекаются до индексации и не занимают лимит; ZIP-скан проверяет каждый упакованный файл (включая `.git` и `node_modules`) на случайные секреты. Недоступные каталоги при обходе дают отдельную blocking-ошибку с путём; OS-junk отмечается предупреждением. [Сайт и демо](https://ghostnever-lkm.github.io/modrelease-studio/) · [релиз v0.3.62](https://github.com/GhosTnever-lkm/modrelease-studio/releases/tag/v0.3.62) · [скачать ZIP](https://github.com/GhosTnever-lkm/modrelease-studio/releases/download/v0.3.62/ModRelease-Studio-v0.3.62.zip)
- **Mod Threat Lens v0.1.9** — локальная эвристическая проверка скриптов, бинарных файлов и ZIP-архивов. Это инструмент первичного анализа, а не антивирус и не вердикт о безопасности. [репозиторий](https://github.com/GhosTnever-lkm/mod-threat-lens) · [релиз](https://github.com/GhosTnever-lkm/mod-threat-lens/releases/tag/v0.1.9) · [скачать ZIP](https://github.com/GhosTnever-lkm/mod-threat-lens/releases/download/v0.1.9/mod-threat-lens-v0.1.9.zip)
- **AegisScan AV v0.1.1** — локальный triage-сканер файлов и ZIP-архивов: ограниченный обход, пользовательские SHA-256 сигнатуры, объяснимые эвристики и JSON/текстовые отчёты. Ничего не запускает, не загружает и не удаляет; не заменяет коммерческий антивирус. [репозиторий](https://github.com/GhosTnever-lkm/aegisscan-av) · [релиз v0.1.1](https://github.com/GhosTnever-lkm/aegisscan-av/releases/tag/v0.1.1)

### 🚀 Готовые инструменты

[AudioScribe Studio](https://github.com/GhosTnever-lkm/audioscribe-studio) · [релиз v0.1.4](https://github.com/GhosTnever-lkm/audioscribe-studio/releases/tag/v0.1.4) · [анонс](https://boosty.to/azizazimov/posts/8bf27107-2627-4292-8589-3191fff70838) | Локальное приложение для расшифровки аудио через faster-whisper: файлы до 5 ГБ, возобновляемая загрузка, экспорт TXT/SRT/VTT/JSON; обработка на компьютере.



[LocaleLens](https://github.com/GhosTnever-lkm/localelens) · [демо](https://ghostnever-lkm.github.io/localelens/) · [релиз v0.1.3](https://github.com/GhosTnever-lkm/localelens/releases/tag/v0.1.3) · [ZIP](https://github.com/GhosTnever-lkm/localelens/releases/download/v0.1.3/LocaleLens-v0.1.3.zip) · [анонс](https://boosty.to/azizazimov/posts/acdf8023-36c5-426d-8fe2-8fb02d984e91) | Сравнивает JSON/ARB-каталоги, находит пропущенные ключи, пустые значения, несовпадение типов и плейсхолдеров; экспортирует отчёт в JSON/CSV.

[CaptionBench](https://github.com/GhosTnever-lkm/captionbench) · [демо](https://ghostnever-lkm.github.io/captionbench/) · [релиз v0.1.2](https://github.com/GhosTnever-lkm/captionbench/releases/tag/v0.1.2) · [ZIP](https://github.com/GhosTnever-lkm/captionbench/releases/download/v0.1.2/CaptionBench-v0.1.2.zip) · [анонс](https://boosty.to/azizazimov/posts/31383539-f1c0-4f5f-8282-cd2818bda2d5) | Локально проверяет и редактирует SRT: длинные строки, скорость чтения, пустые реплики и пересекающиеся тайминги; экспортирует исправленную копию.

[HarborTrace](https://github.com/GhosTnever-lkm/harbortrace) · [демо](https://ghostnever-lkm.github.io/harbortrace/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/harbortrace/releases/tag/v0.1.0) · [анонс](https://boosty.to/azizazimov/posts/1ee1dc9e-12e0-4119-b12f-0bb588181c69) | Локально анализирует HAR-трассы: waterfall запросов, ошибки, медленные endpoints, сравнение двух запусков, CSV и обезличенный HAR-экспорт.

[ShiftLedger](https://github.com/GhosTnever-lkm/shiftledger) · [демо](https://ghostnever-lkm.github.io/shiftledger/) · [релиз v0.1.1](https://github.com/GhosTnever-lkm/shiftledger/releases/tag/v0.1.1) · [ZIP](https://github.com/GhosTnever-lkm/shiftledger/releases/download/v0.1.1/ShiftLedger-v0.1.1.zip) · [анонс](https://boosty.to/azizazimov/posts/23a17455-676d-446b-8104-dee719a645fc) | Табель смен с расчётом оплачиваемых часов и начислений, учётом перерывов и ночных смен, сводкой по неделям и месяцам, CSV и JSON-резервной копией.

[HueDock](https://github.com/GhosTnever-lkm/huedock) · [демо](https://ghostnever-lkm.github.io/huedock/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/huedock/releases/tag/v0.1.0) · [анонс](https://boosty.to/azizazimov/posts/038fe22f-f58c-43c7-9b34-508030688e77) | Локальная мастерская палитр: четыре цветовые гармонии, WCAG AA/AAA контраст, сохранение палитр, JSON-резервная копия и экспорт CSS-токенов.

[TabHarbor](https://github.com/GhosTnever-lkm/tabharbor) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/tabharbor/releases/tag/v0.1.0) · [анонс](https://boosty.to/azizazimov/posts/0b397911-ff04-4e6b-84a2-41db5de42912) | Расширение Chrome и Edge для сохранения, поиска, JSON-экспорта и восстановления рабочих наборов вкладок в отдельных окнах.

[HomeLedger](https://github.com/GhosTnever-lkm/homeledger) · [демо](https://ghostnever-lkm.github.io/homeledger/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/homeledger/releases/tag/v0.1.0) · [анонс](https://boosty.to/azizazimov/posts/9c5fdd21-bc81-4277-9269-bc140211bb2d) | Домашний каталог вещей с ценами, местоположением и сроками гарантии. Локальное хранение, поиск, фильтры и JSON backup.

[PantryPilot](https://github.com/GhosTnever-lkm/pantrypilot) · [демо](https://ghostnever-lkm.github.io/pantrypilot/) · [релиз v0.1.1](https://github.com/GhosTnever-lkm/pantrypilot/releases/tag/v0.1.1) · [ZIP](https://github.com/GhosTnever-lkm/pantrypilot/releases/download/v0.1.1/PantryPilot-v0.1.1.zip) · [анонс](https://boosty.to/azizazimov/posts/841fee9a-520c-4f8e-acd9-8ee32db46fb0) | Планировщик меню на неделю: рецепты и порции автоматически собираются в общий список покупок с учётом запасов дома. Данные остаются в браузере.

[QuoteForge](https://github.com/GhosTnever-lkm/quote-forge) · [демо](https://ghostnever-lkm.github.io/quote-forge/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/quote-forge/releases/tag/v0.1.0) · [анонс](https://boosty.to/azizazimov/posts/b10267ec-b181-480c-bfa5-04f95e869c38) | Локальный конструктор счетов и коммерческих предложений: позиции, дробное количество, скидки, налог, печать/PDF и JSON-резервные копии.

[CalWeave](https://github.com/GhosTnever-lkm/calweave) · [демо](https://ghostnever-lkm.github.io/calweave/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/calweave/releases/tag/v0.1.0) · [скачать ZIP](https://github.com/GhosTnever-lkm/calweave/releases/download/v0.1.0/CalWeave-v0.1.0.zip) · [анонс](https://boosty.to/azizazimov/posts/2a1eef18-244b-478b-a9bc-b351d425b4f9) | Локально импортирует календарь ICS, показывает пересечения событий и свободные интервалы и экспортирует результат. Повторяющиеся события и расширенные часовые пояса пока не разворачиваются.

[FontPair Studio](https://github.com/GhosTnever-lkm/fontpair-studio) · [демо](https://ghostnever-lkm.github.io/fontpair-studio/) · [релиз v1.0.2](https://github.com/GhosTnever-lkm/fontpair-studio/releases/tag/v1.0.2) · [скачать ZIP](https://github.com/GhosTnever-lkm/fontpair-studio/releases/download/v1.0.2/fontpair-studio-v1.0.2.zip) · [анонс](https://boosty.to/azizazimov/posts/eecfbddc-5737-4705-ad44-c7c35cdfc10b) | Локально сравнивает до шести шрифтов, помогает настроить пару для заголовка и текста и экспортирует CSS-тему. Файлы остаются в браузере.

[Subtitle Timing Studio](https://github.com/GhosTnever-lkm/subtitle-timing-studio) · [демо](https://ghostnever-lkm.github.io/subtitle-timing-studio/) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/subtitle-timing-studio/releases/tag/v1.0.1) · [анонс](https://boosty.to/azizazimov/posts/26ba016f-b853-4cf0-811a-173402c831a2) | Локальный редактор SRT/WebVTT с видео-превью, настройкой таймингов по кадру, проверкой пересечений и экспортом. Видео и субтитры остаются в браузере.

[Agent Run Lens](https://github.com/GhosTnever-lkm/agent-run-lens) · [открыть приложение](https://ghostnever-lkm.github.io/agent-run-lens/) · [релиз v1.0.0](https://github.com/GhosTnever-lkm/agent-run-lens/releases/tag/v1.0.0) · [анонс](https://boosty.to/azizazimov/posts/e3a7baaa-0216-4fcc-8995-000d3580a5d9) | Локально исследует JSONL-трассы AI-агентов: события, ошибки, задержки, токены и переданную стоимость; сравнивает запуски, фильтрует и экспортирует отчёты

[CueGrid](https://github.com/GhosTnever-lkm/cuegrid) · [открыть приложение](https://ghostnever-lkm.github.io/cuegrid/) · [релиз v0.2.0](https://github.com/GhosTnever-lkm/cuegrid/releases/tag/v0.2.0) · [анонс](https://boosty.to/azizazimov/posts/c5059938-0164-4a0b-a9c0-e123470490a3) · [CueGrid Pro Pack за 50 ₽](https://boosty.to/azizazimov/posts/1d4a67a2-a1b8-477d-96f1-c92fd0c3f8c0) | Локальная cue-панель для стримов, настольных игр и выступлений: несколько звуковых панелей, клавиши, отдельная громкость, резервный экспорт и импорт библиотеки, слияние готовых панелей.

[Screenshot Diff Lab](https://github.com/GhosTnever-lkm/screenshot-diff-lab) · [демо](https://ghostnever-lkm.github.io/screenshot-diff-lab/) · [релиз v0.1.3](https://github.com/GhosTnever-lkm/screenshot-diff-lab/releases/tag/v0.1.3) · [ZIP](https://github.com/GhosTnever-lkm/screenshot-diff-lab/releases/download/v0.1.3/Screenshot-Diff-Lab-v0.1.3.zip) · [анонс](https://boosty.to/azizazimov/posts/a6d74238-0ae2-452f-b9e4-2efa606ad591) · Локальное сравнение скриншотов: side-by-side, overlay, heatmap различий и экспорт отчётов



[GameText Gate](https://github.com/GhosTnever-lkm/game-text-gate) · [релиз v0.1.14](https://github.com/GhosTnever-lkm/game-text-gate/releases/tag/v0.1.14) · [анонс](https://boosty.to/azizazimov/posts/6afc0d52-9578-474f-8909-1643e690e6d6) · [Locale Matrix Pro за 50 ₽](https://boosty.to/azizazimov/posts/3c8895d7-8a95-4622-9eb3-626a78d272b2) | Локально проверяет игровые переводы Unity/Godot CSV, gettext PO и вложенный JSON: ключи, пустые строки, плейсхолдеры и ограниченный набор разметки; CLI, GitHub Action, Markdown/JSON/SARIF без локальных родительских путей

[ShaderTriage](https://github.com/GhosTnever-lkm/shader-triage) · [открыть приложение](https://ghostnever-lkm.github.io/shader-triage/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/shader-triage/releases/tag/v0.1.0) · [анонс](https://boosty.to/azizazimov/posts/b4bca144-3cee-4373-8c29-72382b0cf69d) | Локально разбирает текстовые логи компиляции шейдеров Unity, Unreal Engine и Godot: группирует повторные диагностики, позволяет искать и экспортировать Markdown/JSON; лог остаётся в браузере

[Asset Sieve](https://github.com/GhosTnever-lkm/asset-sieve) · [анонс](https://boosty.to/azizazimov/posts/ba51430f-0012-413c-bffb-7d921d445b09) · [релиз v0.1.3](https://github.com/GhosTnever-lkm/asset-sieve/releases/tag/v0.1.3) · [wheel](https://github.com/GhosTnever-lkm/asset-sieve/releases/download/v0.1.3/asset_sieve-0.1.3-py3-none-any.whl) | Локальный аудит игровых ресурсов Unity, Unreal и Godot: точные дубликаты, крупные и повреждённые изображения, сводки по папкам и форматам; отчёты Markdown/JSON
| [PingScope](https://github.com/GhosTnever-lkm/ping-scope) · [анонс](https://boosty.to/azizazimov/posts/ddcfcbd7-b3bc-4691-8b2d-3d2f681738a4) · [релиз v0.2.2](https://github.com/GhosTnever-lkm/ping-scope/releases/tag/v0.2.2) · [скачать для Windows](https://github.com/GhosTnever-lkm/ping-scope/releases/download/v0.2.2/PingScope-v0.2.2-windows-x64.zip) | Измеряет задержку, джиттер и потерю пакетов, отображает график и сохраняет локальный CSV-отчёт; запускается на Windows без отдельной установки Python |
| Проект | Что делает |
|:--|:--|
| [CaptionLint](https://github.com/GhosTnever-lkm/subtitle-release-gate) · [анонс](https://boosty.to/azizazimov/posts/0a3f7a4e-d894-44f4-ad49-7023b96b6a4d) · [открыть приложение](https://ghostnever-lkm.github.io/subtitle-release-gate/) · [релиз v1.0.0](https://github.com/GhosTnever-lkm/subtitle-release-gate/releases/tag/v1.0.0) | Проверяет SRT/WebVTT перед выпуском: тайминги, читаемость и расхождения между двумя языковыми дорожками; файлы остаются в браузере |
| [FrameForge](https://github.com/GhosTnever-lkm/frameforge) · [скачать ZIP v1.18.1](https://github.com/GhosTnever-lkm/frameforge/releases/download/v1.18.1/FrameForge-1.18.1-windows-x64.zip) · [релиз v1.18.1](https://github.com/GhosTnever-lkm/frameforge/releases/tag/v1.18.1) · [анонс](https://boosty.to/azizazimov/posts/8013dede-3072-440e-ab74-052758b5a21b) | Windows-приложение для игровых профилей и A/B-бенчмарка; настраиваемый профиль CS:GO Legacy с консольным меню и отдельной desktop-панелью поверх окна игры в безрамочном оконном режиме; таймерный захват кадров через PresentMon и A/B-сравнение помогают измерять результат без обещания фиксированного прироста |
| [SaveHarbor](https://github.com/GhosTnever-lkm/saveharbor) · [релиз v1.1.0](https://github.com/GhosTnever-lkm/saveharbor/releases/tag/v1.1.0) · [скачать ZIP](https://github.com/GhosTnever-lkm/saveharbor/releases/download/v1.1.0/SaveHarbor-v1.1.0.zip) · [анонс](https://boosty.to/azizazimov/posts/33ddae94-fe23-42df-8060-610fd4d6cfa1) · [Pro Scheduler за 50 ₽](https://boosty.to/azizazimov/posts/a9829848-7552-4b9b-8e52-e6086e81765f) | Делает локальные резервные копии и сравнивает как снимки, так и две выбранные папки по SHA-256; сохраняет отдельные снимки даже при совпадении времени создания |
| [RepoSignal](https://github.com/GhosTnever-lkm/repo-signal) · [открыть приложение](https://ghostnever-lkm.github.io/repo-signal/) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/repo-signal/releases/tag/v1.0.1) · [исходный код](https://github.com/GhosTnever-lkm/repo-signal) | Проверяет понятность и готовность публичного GitHub-репозитория: README, лицензия, темы, CI, релизы и документы сообщества |
| [BugBundle](https://ghostnever-lkm.github.io/bugbundle/) · [релиз v1.0.10](https://github.com/GhosTnever-lkm/bugbundle/releases/tag/v1.0.10) · [исходный код](https://github.com/GhosTnever-lkm/bugbundle) | Собирает отчёт о сбое локально, маскирует секреты и показывает невидимые символы в именах |
| [CSV Compass](https://github.com/GhosTnever-lkm/csv-compass) · [открыть приложение](https://ghostnever-lkm.github.io/csv-compass/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/csv-compass/releases/tag/v0.1.0) | Проверяет и очищает CSV-таблицы локально в браузере; файлы не загружаются на сервер |
| [CSV Key Diff](https://github.com/GhosTnever-lkm/csv-key-diff) · [релиз v0.1.1](https://github.com/GhosTnever-lkm/csv-key-diff/releases/tag/v0.1.1) · [ZIP](https://github.com/GhosTnever-lkm/csv-key-diff/releases/download/v0.1.1/csv-key-diff-v0.1.1.zip) | Сравнивает CSV-снимки по уникальному ключу, показывает добавленные/удалённые записи и изменённые поля; JSON/Markdown и CI exit code |
| [CSV Merge Review](https://github.com/GhosTnever-lkm/csv-merge-review) · [пример](https://github.com/GhosTnever-lkm/csv-merge-review/tree/v0.1.0/examples) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/csv-merge-review/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/csv-merge-review/releases/download/v0.1.0/csv-merge-review-v0.1.0.zip) | Объединяет два изменённых CSV-снимка относительно общей базы по ключу: автоматически применяет независимые правки и блокирует неоднозначные конфликты до записи результата |
| [Git Churn Map](https://github.com/GhosTnever-lkm/git-churn-map) · [пример отчёта](https://github.com/GhosTnever-lkm/git-churn-map/blob/v0.1.0/examples/sample-report.md) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/git-churn-map/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/git-churn-map/releases/download/v0.1.0/git-churn-map-v0.1.0.zip) | Локально ранжирует часто изменяемые файлы в Git-истории по добавленным/удалённым строкам; Markdown/JSON, временной фильтр и excludes. Churn — сигнал для ревью, не показатель качества |
| [RiftUnpack](https://github.com/GhosTnever-lkm/RiftUnpack) · [релиз v1.0.0](https://github.com/GhosTnever-lkm/RiftUnpack/releases/tag/v1.0.0) | Быстрое офлайн-извлечение архивов для игроков и моддеров (CLI + GUI): защита от небезопасных путей, корректные права для ZIP-записей без режима, 23 теста и Ruff в CI |
| [License Lint](https://github.com/GhosTnever-lkm/license-lint) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/license-lint/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/license-lint/releases/download/v0.1.0/license-lint-v0.1.0.zip) | Офлайн-проверка лицензии репозитория: определяет LICENSE по тексту, сверяет с полем лицензии в pyproject/Cargo/package.json, блокирует запрещённые лицензии; 14 тестов, CI на Python 3.10–3.13 |
| [dotenv-check](https://github.com/GhosTnever-lkm/dotenv-check) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/dotenv-check/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/dotenv-check/releases/download/v0.1.0/dotenv-check-v0.1.0.zip) | Сверяет `.env` с `.env.example`: пропущенные, пустые, заглушечные и лишние ключи; значения никогда не выводятся; 13 тестов, CI на Python 3.10–3.13 |
| [md-link-check](https://github.com/GhosTnever-lkm/md-link-check) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/md-link-check/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/md-link-check/releases/download/v0.1.0/md-link-check-v0.1.0.zip) | Офлайн-проверка Markdown-документации: битые относительные ссылки, якоря `#…` и пути за пределами репозитория; внешние URL не трогает; 15 тестов, CI на Python 3.10–3.13 |
| [codeowners-lint](https://github.com/GhosTnever-lkm/codeowners-lint) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/codeowners-lint/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/codeowners-lint/releases/download/v0.1.0/codeowners-lint-v0.1.0.zip) | Проверяет CODEOWNERS по дереву репозитория: неверные владельцы, правила без совпадений, дубликаты и файлы без владельца; офлайн; 14 тестов, CI на Python 3.10–3.13 |
| [dockerfile-lint](https://github.com/GhosTnever-lkm/dockerfile-lint) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/dockerfile-lint/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/dockerfile-lint/releases/download/v0.1.0/dockerfile-lint-v0.1.0.zip) | Офлайн-линтер Dockerfile: плавающие теги, запуск от root, `curl \| sh`, секреты в ENV, гигиена apt; 16 тестов, CI на Python 3.10–3.13 |
| [changelog-lint](https://github.com/GhosTnever-lkm/changelog-lint) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/changelog-lint/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/changelog-lint/releases/download/v0.1.0/changelog-lint-v0.1.0.zip) | Проверяет `CHANGELOG.md` по Keep a Changelog: разделы, даты, порядок версий, ссылки; 11 тестов, CI на Python 3.10–3.13 |
| [todo-scan](https://github.com/GhosTnever-lkm/todo-scan) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/todo-scan/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/todo-scan/releases/download/v0.1.0/todo-scan-v0.1.0.zip) | Находит TODO/FIXME/XXX/HACK в репозитории, провально завершает CI на выбранных тегах и на маркерах без владельца; офлайн; 8 тестов, CI на Python 3.10–3.13 |
| [tracked-artifacts-check](https://github.com/GhosTnever-lkm/tracked-artifacts-check) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/tracked-artifacts-check/releases/tag/v0.1.0) · [ZIP](https://github.com/GhosTnever-lkm/tracked-artifacts-check/releases/download/v0.1.0/tracked-artifacts-check-v0.1.0.zip) | Ищет в git-индексе `.env`, ключи, `node_modules`, `__pycache__`, логи, архивы, бинарники и крупные файлы; офлайн; 10 тестов, CI на Python 3.10–3.13 |
| [JSON Compass](https://github.com/GhosTnever-lkm/json-compass) · [открыть приложение](https://ghostnever-lkm.github.io/json-compass/) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/json-compass/releases/tag/v1.0.1) · [анонс](https://boosty.to/azizazimov/posts/2acc32dd-8940-4a05-b30b-1cf4c188be8d) | Форматирует и сравнивает JSON, показывает структуру и точные пути; данные остаются в браузере |
| [ContrastKit](https://github.com/GhosTnever-lkm/contrastkit) · [открыть приложение](https://ghostnever-lkm.github.io/contrastkit/) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/contrastkit/releases/tag/v1.0.1) · [анонс](https://boosty.to/azizazimov/posts/edabf228-6560-4d30-80b5-337ddad3fa26) | Проверяет контрастность текста и цвета фона по WCAG AA/AAA, показывает палитру и экспортирует CSS-переменные |
| [CommitCraft](https://github.com/GhosTnever-lkm/commitcraft) · [ZIP v1.0.1](https://github.com/GhosTnever-lkm/commitcraft/releases/download/v1.0.1/CommitCraft-v1.0.1.zip) · [исходный код](https://github.com/GhosTnever-lkm/commitcraft) | Формирует changelog после последнего Git-тега и группирует коммиты по типам |
| [DiffShield](https://github.com/GhosTnever-lkm/diffshield-action) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/diffshield-action/releases/tag/v1.0.1) | Проверяет pull request на распространённые риски в GitHub Actions |
| [ModLocale](https://github.com/GhosTnever-lkm/clausewitz-loc-guard) · [релиз v1.0.2](https://github.com/GhosTnever-lkm/clausewitz-loc-guard/releases/tag/v1.0.2) · [ZIP](https://github.com/GhosTnever-lkm/clausewitz-loc-guard/releases/download/v1.0.2/ModLocale-v1.0.2.zip) · [демо](https://ghostnever-lkm.github.io/clausewitz-loc-guard/?demo) | Проверяет ключи, дубли, BOM и игровые маркеры в локализации модов Clausewitz и Paradox |
| [ModPack Inspector](https://github.com/GhosTnever-lkm/modpack-inspector) · [демо](https://ghostnever-lkm.github.io/modpack-inspector/?demo) · [релиз v0.1.1](https://github.com/GhosTnever-lkm/modpack-inspector/releases/tag/v0.1.1) · [ZIP](https://github.com/GhosTnever-lkm/modpack-inspector/releases/latest/download/ModPack-Inspector-0.1.1.zip) | Проверяет структуру ZIP-архива мода перед установкой; отмечает опасные пути, дубли и лишние папки |
| [ModRelease Studio](https://github.com/GhosTnever-lkm/modrelease-studio) · [релиз v0.3.62](https://github.com/GhosTnever-lkm/modrelease-studio/releases/tag/v0.3.62) · [скачать ZIP](https://github.com/GhosTnever-lkm/modrelease-studio/releases/download/v0.3.62/ModRelease-Studio-v0.3.62.zip) | Ищет ошибки упаковки и секреты, сравнивает сборки и формирует отчёт перед выпуском без локальных родительских путей |
| [ModRelease Gate](https://github.com/GhosTnever-lkm/modrelease-studio-action) · [релиз v1.0.48](https://github.com/GhosTnever-lkm/modrelease-studio-action/releases/tag/v1.0.48) | Запускает ModRelease Studio v0.3.62, добавляет безопасные annotations, выгружаемые JSON/Markdown/SARIF отчёты и checkout-относительные пути для GitHub Actions; загрузка в Code Scanning включается отдельно |
| [Mod Observatory](https://github.com/GhosTnever-lkm/mod-observatory) · [открыть приложение](https://ghostnever-lkm.github.io/mod-observatory/) · [скачать v0.2.0](https://github.com/GhosTnever-lkm/mod-observatory/releases/download/v0.2.0/mod-observatory-0.2.0.zip) · [релиз](https://github.com/GhosTnever-lkm/mod-observatory/releases/tag/v0.2.0) | Анализирует коллекции модов, зависимости, порядок загрузки, общие пути и изменения между снимками |
| [ModForge Studio](https://github.com/GhosTnever-lkm/modforge-studio) · [открыть приложение](https://ghostnever-lkm.github.io/modforge-studio/) · [релиз v0.1.2](https://github.com/GhosTnever-lkm/modforge-studio/releases/tag/v0.1.2) | Локальная мастерская для проверки модов, зависимостей и сборки релизного ZIP; экспериментальная версия |
| [Mod Conflict Map](https://github.com/GhosTnever-lkm/paradox-mod-conflict-map) · [открыть приложение](https://ghostnever-lkm.github.io/paradox-mod-conflict-map/) · [релиз v0.4.1](https://github.com/GhosTnever-lkm/paradox-mod-conflict-map/releases/tag/v0.4.1) · [ZIP](https://github.com/GhosTnever-lkm/paradox-mod-conflict-map/releases/download/v0.4.1/Mod-Conflict-Map-v0.4.1.zip) · [анонс](https://boosty.to/azizazimov/posts/7c97d8ec-ea1e-458d-8848-4ec9c0e22725) | Находит потенциальные пересечения файловых путей в ZIP-архивах и папках модов Paradox; поиск по пути, названию мода и ZIP-файлу; CI проверяет синтаксис и регрессионные тесты на Node.js 22/24 |
| [Workshop Page Studio](https://ghostnever-lkm.github.io/workshop-page-studio/) · [ZIP v0.2.1](https://github.com/GhosTnever-lkm/workshop-page-studio/releases/latest/download/Workshop-Page-Studio-v0.2.1.zip) · [исходный код](https://github.com/GhosTnever-lkm/workshop-page-studio) | Создаёт страницы модов с предпросмотром и экспортом в Steam BBCode или Markdown |
| [Paradox Mod Workbench](https://github.com/GhosTnever-lkm/paradox-mod-workbench) · [релиз v0.2.4](https://github.com/GhosTnever-lkm/paradox-mod-workbench/releases/tag/v0.2.4) | CLI для диагностики конфликтов, зависимостей, локализации и скриптов с JSON/SARIF-отчётами |
| [Paradox Mod Quality Gate](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate) · [релиз v1.0.45](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate/releases/tag/v1.0.45) · [Windows Pro за 50 ₽](https://boosty.to/azizazimov/posts/761380dd-5d2d-45d1-ad6d-452b123d11b3) | Объединяет ModRelease Studio v0.3.62 и Paradox Mod Workbench v0.2.4 в GitHub Action с экспортом SARIF 2.1.0; Pro добавляет Windows GUI и HTML/SARIF-отчёты |
| [WorkflowGuard](https://github.com/GhosTnever-lkm/workflowguard) · [релиз v1.0.4](https://github.com/GhosTnever-lkm/workflowguard/releases/tag/v1.0.4) · [Pro Kit за 50 ₽](https://boosty.to/azizazimov/posts/5c87f36c-8306-462e-85a8-a4facd470adb) | Локально проверяет GitHub Actions и экспортирует результаты в текст, JSON или SARIF; Pro Kit содержит стартовые workflow-шаблоны |
| [LogSieve](https://github.com/GhosTnever-lkm/logsieve) · [открыть приложение](https://ghostnever-lkm.github.io/logsieve/) · [релиз v0.1.0](https://github.com/GhosTnever-lkm/logsieve/releases/tag/v0.1.0) | Локально очищает игровые и системные логи от типовых токенов и личных данных перед отправкой в поддержку |
| [VOIDFALL](https://github.com/GhosTnever-lkm/voidfall) · [играть](https://ghostnever-lkm.github.io/voidfall/) · [релиз v1.0.3](https://github.com/GhosTnever-lkm/voidfall/releases/tag/v1.0.3) | Браузерный roguelite-шутер с волнами врагов, боссами, способностями, контрактами и локальным сохранением прогресса |

### 🧩 Плагины и наборы

| Проект | Назначение |
|:--|:--|
| [GhosTnever Mega Toolkit](https://github.com/GhosTnever-lkm/ghosTnever-codex-toolkit/tree/main/plugins/ghostnever-mega-toolkit) · [релиз v1.1.3](https://github.com/GhosTnever-lkm/ghosTnever-codex-toolkit/releases/tag/v1.1.3) | Один плагин Codex с 41 рабочим навыком и локальными настройками включения/выключения |
| [Repository Onboarding](https://github.com/GhosTnever-lkm/repo-onboarding) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/repo-onboarding/releases/tag/v1.0.1) · [ZIP](https://github.com/GhosTnever-lkm/repo-onboarding/releases/download/v1.0.1/repo-onboarding-v1.0.1.zip) | Помогает освоиться в незнакомом репозитории |
| [Change Review](https://github.com/GhosTnever-lkm/change-review) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/change-review/releases/tag/v1.0.1) | Ищет ошибки и возможные регрессии в изменениях |
| [CI Failure Guide](https://github.com/GhosTnever-lkm/ci-failure-guide) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/ci-failure-guide/releases/tag/v1.0.1) | Помогает разбирать сбои сборки и CI |
| [Release Checklist](https://github.com/GhosTnever-lkm/release-checklist) · [релиз v1.0.1](https://github.com/GhosTnever-lkm/release-checklist/releases/tag/v1.0.1) · [ZIP](https://github.com/GhosTnever-lkm/release-checklist/releases/download/v1.0.1/release-checklist-v1.0.1.zip) | Помогает подготовить проект к выпуску |
| [Docs from Code](https://github.com/GhosTnever-lkm/docs-from-code) · [релиз v1.0.0](https://github.com/GhosTnever-lkm/docs-from-code/releases/tag/v1.0.0) · [архив плагина](https://github.com/GhosTnever-lkm/docs-from-code/releases/download/v1.0.0/Docs-from-Code-v1.0.0.zip) | Помогает писать инструкции, архитектурные заметки и API-документацию по текущему исходному коду |
| [DSH GhostNever Toolkit](https://github.com/GhosTnever-lkm/dsh-ghostnever-toolkit) · [релиз v1.0.2](https://github.com/GhosTnever-lkm/dsh-ghostnever-toolkit/releases/tag/v1.0.2) · [ZIP](https://github.com/GhosTnever-lkm/dsh-ghostnever-toolkit/releases/download/v1.0.2/GhosTnever-DSH-Toolkit-v1.0.2.zip) | Набор из 21 отдельно устанавливаемого плагина для DeepSeek Harness / Cordis |

### ☕ Поддержать GhosTnever

Если мои проекты оказались полезны, поддержать их можно на [Buy Me a Coffee](https://buymeacoffee.com/azizazimov8) или [Gumroad](https://azimovian22.gumroad.com/).

<details>
<summary>Криптовалютные адреса для получения</summary>

Отправляйте только активы в указанной сети.

| Сеть | Адрес |
|:--|:--|
| Bitcoin | `bc1qn75pj4n7gyl2k5kf2f97elvyenz52q6nn2g30u` |
| TRON | `TCBSy38X57hA6w2onJcxom24x1febc1mP1` |
| BNB Smart Chain | `0xD431a917961E0b086B96D9F72b5C8fF19b19068a` |

</details>

### ✦ Как я работаю

- Проверяю факты по исходному коду и документации проекта.
- Публикую открытые инструменты с инструкциями и лицензией.
- Описываю ограничения и не обещаю того, чего проект пока не умеет.

---

<p align="center"><i>Спасибо, что заглянули ✨</i></p>

