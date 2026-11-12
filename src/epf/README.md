# Каталог src/epf

Исходники внешних обработок (выгрузка в XML).

| Файл | Назначение |
| --- | --- |
| `ТО_Шаги.xml`, `ТО_Шаги/` | библиотека шагов Vanessa Automation для сценариев из `features/` |

Собранный `.epf` в репозиторий не кладётся. Сборка в `build/epf`:

```
1cv8.exe DESIGNER /F "<база>" /N Администратор /LoadExternalDataProcessorOrReportFromFiles "src\epf\ТО_Шаги.xml" "build\epf\ТО_Шаги.epf"
```
