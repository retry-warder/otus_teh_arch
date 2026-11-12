# Каталог tools

Настройки инструментов проекта.

| Файл | Назначение |
| --- | --- |
| `JSON/va-config.json` | Vanessa Automation: регресс `features/ТО`, два тест-клиента (`Основной`, `ТолькоЧтение`), тег `@demo` исключён |
| `JSON/va-config-demo.json` | Vanessa Automation: демо-сценарий `features/demo`, окна после прогона не закрываются |
| `JSON/va-config-video.json` | Vanessa Automation: автозапись видео с озвучкой `features/video` |
| `JSON/yaxunit.json` | YAxUnit: расширение `YAXUNIT`, теги `ТО`, `ОП`, `RMQ`, отчёт junit |

Пути в конфигах Vanessa заданы от корня репозитория: фичи — `./features/...`, библиотека шагов — `./build/epf`, отчёты — `./build/reports/...`. Путь к базе в `КлиентыТестирования` и путь к отчёту в `yaxunit.json` зависят от рабочего места и правятся под него.
