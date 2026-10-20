<p align="center">
  <a href="https://ghostnever-lkm.github.io/">🌐 Портфолио</a> ·
  <a href="https://github.com/GhosTnever-lkm?tab=repositories">Все репозитории</a>
</p>

<h1 align="center">Привет, я GhosTnever 👋</h1>

<p align="center"><strong>Создаю инструменты проверки качества и выпуска игровых модов.</strong></p>

<p align="center">Мой основной проект — ModRelease Studio: локальный сканер перед публикацией. Вокруг него я собираю инструменты для GitHub Actions и более глубокой диагностики модов Paradox.</p>

<p align="center">
  <a href="https://github.com/GhosTnever-lkm/modrelease-studio/releases/latest"><img src="https://img.shields.io/github/v/release/GhosTnever-lkm/modrelease-studio?label=ModRelease%20Studio" alt="Последний релиз ModRelease Studio"></a>
  <a href="https://github.com/GhosTnever-lkm/modrelease-studio/actions/workflows/preflight.yml"><img src="https://img.shields.io/github/actions/workflow/status/GhosTnever-lkm/modrelease-studio/preflight.yml?label=CI" alt="Статус CI ModRelease Studio"></a>
  <a href="https://github.com/GhosTnever-lkm/modrelease-studio/blob/main/LICENSE"><img src="https://img.shields.io/github/license/GhosTnever-lkm/modrelease-studio" alt="Лицензия ModRelease Studio"></a>
</p>

## Флагман · ModRelease Studio

Проверь папку или ZIP мода до публикации. Сканер выявляет проблемы упаковки, метаданных, локализации и известные шаблоны секретов; сравнивает сборки и формирует отчёт для исправления находок. Сканирование запускается локально, а значения секретов не включаются в отчёты.

**Попробовать:** [страница проекта](https://ghostnever-lkm.github.io/modrelease-studio/) · [исходный код](https://github.com/GhosTnever-lkm/modrelease-studio) · [релиз v0.3.86](https://github.com/GhosTnever-lkm/modrelease-studio/releases/tag/v0.3.86) · [скачать ZIP](https://github.com/GhosTnever-lkm/modrelease-studio/releases/download/v0.3.86/ModRelease-Studio-v0.3.86.zip) · [SHA-256](https://github.com/GhosTnever-lkm/modrelease-studio/releases/download/v0.3.86/ModRelease-Studio-v0.3.86.zip.sha256)

<p align="center">
  <a href="https://ghostnever-lkm.github.io/modrelease-studio/"><img src="https://raw.githubusercontent.com/GhosTnever-lkm/modrelease-studio/v0.3.86/docs/demo.png" alt="Пример отчёта ModRelease Studio с результатами проверки мода" width="760"></a>
</p>

### Быстрый старт

```bash
python -m pip install "modrelease-studio @ git+https://github.com/GhosTnever-lkm/modrelease-studio.git@v0.3.86"
modrelease scan ./my-mod --md-out report.md --json-out report.json
```

## Связанные инструменты

| Инструмент | Для чего нужен | Код и версия |
|:--|:--|:--|
| **ModRelease Gate** | Запускает проверку в GitHub Actions, показывает находки в журнале и сохраняет отчёты как артефакты workflow. | [Код](https://github.com/GhosTnever-lkm/modrelease-studio-action) · [v1.0.68](https://github.com/GhosTnever-lkm/modrelease-studio-action/releases/tag/v1.0.68) |
| **Paradox Mod Quality Gate** | Объединяет проверки ModRelease Studio и Paradox Mod Workbench в единый preflight для модов Paradox. | [Код](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate) · [v1.0.71](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate/releases/tag/v1.0.71) |
| **Paradox Mod Workbench** | Локально исследует конфликты и зависимости модпака, таблицы локализации и Clausewitz-скрипты; экспортирует текстовые, JSON и SARIF-отчёты. | [Код](https://github.com/GhosTnever-lkm/paradox-mod-workbench) · [v0.2.8](https://github.com/GhosTnever-lkm/paradox-mod-workbench/releases/tag/v0.2.8) |

## Как связаны проекты

```text
ModRelease Studio → ModRelease Gate в GitHub Actions
        └──────────→ Paradox Mod Quality Gate
                         └── ModRelease Studio + Paradox Mod Workbench
```

Анализаторы помогают находить известные проблемы до выпуска, но не гарантируют запуск мода в игре или совместимость со всеми модами и версиями игры.

## Проверка изменений

- [CI ModRelease Studio](https://github.com/GhosTnever-lkm/modrelease-studio/actions/workflows/preflight.yml)
- [CI ModRelease Gate](https://github.com/GhosTnever-lkm/modrelease-studio-action/actions/workflows/ci.yml)
- [CI Paradox Mod Quality Gate](https://github.com/GhosTnever-lkm/paradox-mod-quality-gate/actions/workflows/ci.yml)
- [CI Paradox Mod Workbench](https://github.com/GhosTnever-lkm/paradox-mod-workbench/actions/workflows/ci.yml)

Больше моих работ — в [репозиториях GitHub](https://github.com/GhosTnever-lkm?tab=repositories) и на [сайте-портфолио](https://ghostnever-lkm.github.io/).
