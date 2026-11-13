# Коды — штрих-код и Data Matrix

Сайт: https://theultranilla.github.io/codes/

Одна страница: создать штрих-код (Code 128) или Data Matrix из текста и прочитать их камерой или с фото.
Всё работает в браузере, без сервера.

- `index.html` — страница и вся логика.
- `lib/zxing.js`, `lib/zxing_full.wasm` — [zxing-wasm](https://github.com/Sec-ant/zxing-wasm) (MIT): создаёт и читает коды.

Локально: `python -m http.server` в этой папке → http://localhost:8000 (с file:// браузер не загрузит .wasm).
