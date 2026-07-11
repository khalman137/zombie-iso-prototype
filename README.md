# NewEngine 2.5D v1.4 direct archives

## Структура репозитория

```text
index.html
README.md
maps/
  test_map.zip
templates/
  plot_small_south_01.zip
  plot_small_south_02.zip
  plot_small_east_01.zip
  plot_medium_north_01.zip
```

В каталогах `maps` и `templates` находятся только самостоятельные ZIP-архивы. PNG и JSON не лежат в репозитории россыпью.

Движок загружает архивы напрямую:

- `maps/test_map.zip`
- `templates/<template_id>.zip`

Вложенных ZIP больше нет.

## Запуск

Загрузить содержимое папки в корень GitHub-репозитория и открыть `index.html` через GitHub Pages или raw.githack.

При добавлении нового шаблона его ZIP нужно положить в `templates/` и добавить ID в каталог шаблонов внутри `index.html`.
