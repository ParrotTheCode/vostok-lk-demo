# Демо ЛК Восток-Лизинг

`index.html` плюс папка `fonts/` (Golos Text лежит локально, Google Fonts не нужен). Без сборки и зависимостей. При размещении копировать папку `demo` целиком.

## Запуск локально
```bash
python -m http.server 5173 --directory demo
```
Открыть http://localhost:5173

## Бесплатное размещение

**GitHub Pages** (как у конкурента, ссылка вида `user.github.io/repo`):
1. Создать публичный репозиторий на github.com, например `vostok-lk-demo`.
2. Положить `index.html` в корень и запушить:
```bash
cd demo && git init && git add index.html && git commit -m "demo" && git branch -M main
git remote add origin https://github.com/<ЛОГИН>/vostok-lk-demo.git && git push -u origin main
```
3. Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save. Через минуту ссылка появится там же.

**Netlify Drop** (без git): app.netlify.com/drop → перетащить папку `demo`. Ссылка сразу, можно задать своё имя `*.netlify.app`.

**Cloudflare Pages / Vercel**: Create project → Upload assets → папка `demo`. Тоже бесплатно и без сборки.

**Свой домен** можно привязать на любом из вариантов бесплатно (CNAME).
