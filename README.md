# Продуктовая и проектная документация: примеры

*Product and project management artifacts: a PRD for a B2B govtech/fintech marketplace MVP, a technical specification for a retail hiring automation system, and a full project pack for launching a private label product (charter, WBS, Gantt, RACI, risk register, budget, status report).*

**Роли:** продакт-менеджер, проджект-менеджер · **Формат:** Markdown, Mermaid (диаграммы рендерятся прямо на GitHub)

Три документа по проектам, в которых я участвовала. Компании обезличены, цифры в коммерческих документах изменены.

## 1. PRD: платформа аналитики госзакупок с витриной финансирования

[`01-prd-tender-analytics/PRD.md`](01-prd-tender-analytics/PRD.md)

B2B-платформа для участников госзакупок: показывает, сколько денег потребует тендер, и передаёт заявку на финансирование операторам инвестиционных платформ.

- проблема и JTBD двух сторон рынка;
- регуляторные ограничения как требования к продукту: справочный сервис вне контура финансового посредника, минимум персональных данных, подтверждение организации подписью без хранения подписи на платформе;
- объём MVP с приоритетами MoSCoW и RICE, пользовательский путь;
- North Star и воронка метрик, гипотезы с экспериментами, дорожная карта с критериями перехода, риски.

## 2. ТЗ: автоматизация найма в рознице

[`02-tz-hiring-automation/TZ.md`](02-tz-hiring-automation/TZ.md)

Техническое задание для команды разработки: сбор откликов с hh.ru, Avito, SuperJob, анкета и отбор в чат-боте ВКонтакте и Telegram, запись на собеседование, воронка по каналам.

- AS IS / TO BE, роли, 25 функциональных требований с приоритетами;
- интеграции только через официальные API площадок;
- требования 152-ФЗ: состав данных, согласие, сроки хранения;
- этапы с пилотом на 3 магазинах, критерии приёмки, открытые вопросы;
- приложения: анкета и статусная модель кандидата.

## 3. Проектный пакет: запуск собственной торговой марки

[`03-project-private-label/`](03-project-private-label)

Вывод на полку первого SKU собственной марки сети через контрактного производителя: от анализа рынка до товара в 18 магазинах.

| Устав | WBS и Гант | RACI | Риски | Бюджет | Статус-отчёт |
|---|---|---|---|---|---|
| [01](03-project-private-label/01-charter.md) | [02](03-project-private-label/02-wbs-schedule.md) | [03](03-project-private-label/03-raci.md) | [04](03-project-private-label/04-risks.md) | [05](03-project-private-label/05-budget.md) | [06](03-project-private-label/06-status-report.md) |

## Другие кейсы

- [procurement-price-control](https://github.com/Marylink27/procurement-price-control): пакет системного аналитика, BPMN, use cases, user stories, SQL, OpenAPI, интеграция с 1С
- [purchase-budget-allocation](https://github.com/Marylink27/purchase-budget-allocation): распределение закупочного бюджета, AS IS / TO BE, перебор планов
- [marketplace-unit-economics](https://github.com/Marylink27/marketplace-unit-economics): юнит-экономика товара на WB и Ozon
