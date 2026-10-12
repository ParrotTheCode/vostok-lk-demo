# Демо ЛК Восток-Лизинг

`index.html` плюс папка `fonts/` (Golos Text лежит локально, Google Fonts не нужен). Без сборки и зависимостей. При размещении копировать папку `demo` целиком.

## Запуск локально
```bash
python -m http.server 5173 --directory demo
```
Открыть http://localhost:5173

## Бесплатное размещение

**GitHub Pages**: репозиторий https://github.com/ParrotTheCode/vostok-lk-demo, сайт https://parrotthecode.github.io/vostok-lk-demo/ (ветка `gh-pages`, корень). Обновить после правок:
```bash
git add -A && git commit -m "update" && git push origin main && git push origin main:gh-pages
```
Если сайт не открывается: Settings → Pages → Source: Deploy from a branch → `gh-pages` / `/ (root)`.

**Netlify Drop** (без git): app.netlify.com/drop → перетащить папку `demo`. Ссылка сразу, можно задать своё имя `*.netlify.app`.

**Cloudflare Pages / Vercel**: Create project → Upload assets → папка `demo`. Тоже бесплатно и без сборки.

**Свой домен** можно привязать на любом из вариантов бесплатно (CNAME).
