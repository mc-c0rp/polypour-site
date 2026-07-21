# Poly Pour — сайт разработчика (для GitHub Pages)

Эта папка — готовый статический сайт. Он нужен Google Play (privacy policy URL)
и рекламным сетям (app-ads.txt).

## Как опубликовать (5 минут, бесплатно)

1. Создай на GitHub публичный репозиторий, например `polypour-site`.
2. Залей туда СОДЕРЖИМОЕ этой папки (index.html в корень репозитория).
3. В репозитории: Settings → Pages → Source: `main` branch, папка `/ (root)` → Save.
4. Через минуту страница будет доступна по адресу
   `https://<твой-логин>.github.io/polypour-site/` — это и есть **privacy policy URL**
   для Google Play Console (Policy → App content → Privacy policy).

## app-ads.txt (ПОСЛЕ релиза)

Когда приложение опубликовано и в Play Console указан сайт разработчика
`https://<твой-логин>.github.io/polypour-site/`:

1. В дашборде LevelPlay (platform.ironsrc.com) найди раздел **app-ads.txt**
   (обычно в настройках приложения) — он выдаст готовые строки вида
   `ironsrc.com, <id>, DIRECT, ...` и строки Unity Ads.
2. Создай в репозитории файл `app-ads.txt` с этими строками (рядом с index.html).
3. Проверка: файл должен открываться по
   `https://<твой-логин>.github.io/polypour-site/app-ads.txt`.

Примечание: email в privacy policy — dmitriiursachi@gmail.com; если email
разработчика в Play Console будет другой, поменяй его и в index.html.
