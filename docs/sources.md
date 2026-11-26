# Источники и границы исследования

Все источники просмотрены 26 ноября 2026 года.

## Объект документации

- [Репозиторий backend, закреплённый коммит](https://github.com/MarkovFedor/mvp-delivery-backend/tree/89a3abe1c0ff8a86bf2aad9f09bc91669c58941f): README, `docker-compose.yml`, `Makefile`, конфигурация, маршруты, схемы и сервис заказов. Источник фактов о продукте.
- [Обработчик статусов](https://github.com/MarkovFedor/mvp-delivery-backend/blob/89a3abe1c0ff8a86bf2aad9f09bc91669c58941f/app/api/v1/endpoints/restaurant_orders.py) и [сервис заказов](https://github.com/MarkovFedor/mvp-delivery-backend/blob/89a3abe1c0ff8a86bf2aad9f09bc91669c58941f/app/services/order_service.py): источник пути, ответов и ограничений.

## Примеры и методология

- [Стайлгайд Travel Buddy Finder](https://xsini.github.io/style-guide-project/): изучены главная страница и конфигурация навигации. Полезны явная область применения, приоритет фактов о версии, терминология, шаблоны и протокол апробации. В этом проекте подход адаптирован к backend и API; особенности Travel Buddy Finder не перенесены как факты о доставке еды.
- [Google developer documentation style guide: Highlights](https://developers.google.com/style/highlights): активный залог, понятные действия, осмысленные ссылки и оформление кода. Англоязычные орфографические нормы не переносятся в русский текст.
- [Diátaxis](https://diataxis.fr/): разделение документации по потребности читателя на обучение, практические инструкции, справочник и объяснение.

## Инструменты

- [MkDocs: публикация](https://www.mkdocs.org/user-guide/deploying-your-docs/): сборка статического сайта и публикация.
- [GitHub Pages: собственные workflows](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages): публикация артефакта через Actions с отдельным заданием deploy.
- [PyMarkdown](https://pymarkdown.readthedocs.io/): проверка структуры Markdown.

## Недоступные материалы

Презентация из папки лабораторной не предоставлена. Сохранённый текст исходного задания обрывается на пункте 11.4. Поэтому изучение этой презентации и выполнение неизвестных подпунктов не заявляются. Теория подготовлена по открытым источникам выше и явным требованиям пользователя.
