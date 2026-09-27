# Карта зон поражения

Статическое веб-приложение: `index.html` загружает список станций из `nuclear-plants.json`.

## Каталог атомных электростанций

`nuclear-plants.json` содержит по одной записи на площадку, где в исходном наборе есть хотя бы один энергоблок со статусом `operating`. В файле указаны координаты, страна, число действующих по источнику блоков и точность координат. Российские станции подписаны по-русски; остальные сгруппированы по стране.

- **Источник данных:** [Global Nuclear Power Tracker, Global Energy Monitor](https://globalenergymonitor.org/projects/global-nuclear-power-tracker/), через [KAPSARC Data Portal](https://datasource.kapsarc.org/explore/assets/global-nuclear-power-tracker/).
- **Снимок источника:** 11 мая 2026 года; лицензия набора на портале — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- Билибинская АЭС исключена: последние действовавшие энергоблоки станции остановлены 30 декабря 2025 года ([источник](https://www.world-nuclear-news.org/articles/all-four-bilibino-units--permanently-shut-down)).
- Статусы в статическом списке могут отставать от реального положения дел; список не обновляется автоматически и не является оперативным справочником.

CSV-экспорт исходного каталога: <https://datasource.kapsarc.org/api/explore/v2.1/catalog/datasets/global-nuclear-power-tracker/exports/csv/?delimiter=%3B&lang=en&timezone=UTC&use_labels=true>.
