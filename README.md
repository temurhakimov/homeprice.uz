# KMT HomePrice.uz

Онлайн-оценка квартир в Ташкенте от KMT — первый пользовательский продукт платформы **KMT Real Estate Analytics**.
Сайт: https://homeprice.uz

Стоимость определяют математические модели оценки на рыночных данных по ЕНСО / НСО № 10, а не AI. AI — только ассистент.

Начать чтение: [docs/00_Overview/00_Project_Overview.md](docs/00_Overview/00_Project_Overview.md)

## Структура документации

| Папка | Что внутри |
|---|---|
| [00_Overview](docs/00_Overview) | Концепция, цели, глоссарий, журнал решений, дорожная карта |
| [01_Product](docs/01_Product) | PRD, три уровня продукта, сценарии, портреты пользователей |
| [02_Methodology](docs/02_Methodology) | Методология оценки, стандарты, корректировки, местоположение |
| [03_Data](docs/03_Data) | Источники, модель данных, обработка, качество, историческая база |
| [04_Valuation_Engine](docs/04_Valuation_Engine) | Подбор аналогов, математические модели, достоверность |
| [05_Validation](docs/05_Validation) | Бэктесты, метрики точности, калибровка, торг |
| [06_Architecture](docs/06_Architecture) | Архитектура, ADR, API, инфраструктура, безопасность |
| [07_AI_Assistant](docs/07_AI_Assistant) | Границы и сценарии AI-ассистента |
| [08_UX_UI](docs/08_UX_UI) | Пути пользователя, экраны, тексты RU/UZ, дизайн |
| [09_Reporting](docs/09_Reporting) | Страница результата, мини-отчёт, профессиональный отчёт, индекс цен |
| [10_Operations_CRM](docs/10_Operations_CRM) | CRM, процесс заказа оценки, поддержка |
| [11_Marketing_Growth](docs/11_Marketing_Growth) | Аналитика, SEO/SEM/GEO, контент, Telegram, PR |
| [12_Business](docs/12_Business) | Монетизация, конкуренты, рынок, B2B, финансовая модель |
| [13_Legal_Compliance](docs/13_Legal_Compliance) | Оферта, персональные данные, права на данные, регулирование |
| [14_Testing_QA](docs/14_Testing_QA) | Тестирование ПО |
| [15_Releases](docs/15_Releases) | MVP, план релизов, changelog, аудиты сайта |
| [99_Archive](docs/99_Archive) | Устаревшие версии |
| [_templates](docs/_templates) | Шаблоны документов |

## Правила

- Имена файлов — латиницей, с номером, если важен порядок: `01_Product_Requirements.md`.
- У каждого документа сверху: версия, дата, автор, статус (черновик / на согласовании / утверждён).
- Старые версии не удаляются, а переносятся в `99_Archive` с датой.
- Решения фиксируются в `docs/00_Overview/Decision_Log.md`.
