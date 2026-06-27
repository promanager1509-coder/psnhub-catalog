# PSNHUB GitHub Pages upload kit

Это готовый комплект файлов для загрузки в GitHub-репозиторий `psnhub-catalog`.

Загружать нужно содержимое этой папки, а не саму папку.

В корне репозитория должны лежать:

- `index.html`
- `.nojekyll`
- `README.md`
- `tilda-psnhub-catalog-block.html`
- папка `data`

После загрузки включить GitHub Pages:

`Settings → Pages → Deploy from branch → main → /root`

Проверить сайт:

`https://ВАШ_ЛОГИН.github.io/psnhub-catalog/`

Проверить JSON:

`https://ВАШ_ЛОГИН.github.io/psnhub-catalog/data/psnhub_objects_public.json`

Затем заменить `DATA_URL` в `tilda-psnhub-catalog-block.html` на реальный GitHub Pages JSON URL и вставить код в Tilda T123.

Если в репозитории уже есть старый `psnhub_objects_public.json` в корне, его лучше удалить или оставить неиспользуемым. Рабочий JSON должен лежать в `data/psnhub_objects_public.json`.
