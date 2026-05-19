# Aurora White List — geosite.dat

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Size](https://img.shields.io/badge/size-2.65%20MB-brightgreen)](geosite.dat)

Минималистичный и лёгкий файл `geosite.dat` для Happ (iOS) и других V2Ray-совместимых клиентов.

**Вес: всего 2.65 МБ** — помещается в строгий лимит памяти Happ (50 МБ) и не вызывает ошибок.

---

## 📦 Что внутри

Файл содержит **только необходимые категории** доменов:

| Категория | Назначение |
|-----------|------------|
| `category-ru` | Российские сайты (Yandex, VK, Ozon, Wildberries, Госуслуги и др.) |
| `category-ads-all` | Рекламные домены (блокировка) |
| `geolocation-!cn` | Все домены, не относящиеся к Китаю |

Это **white list** подход:
- Российские сайты → **DIRECT** (напрямую, быстро)
- Реклама → **BLOCK** (полная блокировка)
- Всё остальное → **PROXY** (через VPN/туннель)

---

