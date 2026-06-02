# Deployment

## GitHub Pages

1. Создать репозиторий.
2. Загрузить содержимое папки `Maryvill`, а не сам архив.
3. Перейти в Settings → Pages.
4. Выбрать:
   - Source: Deploy from branch
   - Branch: main
   - Folder: /root
5. Сохранить.

## Локальная проверка

```bash
python3 -m http.server 8000
```

Затем открыть:

```text
http://localhost:8000
```

## Важно

Не открывать сайт только двойным кликом по `index.html`, если нужно проверить поведение как на реальном сайте. Локальный сервер ближе к настоящей публикации.
