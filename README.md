# Стайлгайд документации MVP доставки еды

Лабораторная работа 3: полный цикл Docs as Code для [mvp-delivery-backend](https://github.com/MarkovFedor/mvp-delivery-backend).

[Опубликованный стайлгайд](https://markovfedor.github.io/style-guide-project/) · [Отчёт](docs/lab-report.md) · [Правила участия](CONTRIBUTING.md)

## Локальная проверка

Требуется Python 3.12 с модулем `venv`. Выполняйте команды из корня репозитория.

```bash
python3 -m venv .venv
. .venv/bin/activate
python -m pip install -r requirements.txt
python -m pymarkdown --config .pymarkdown.json scan --recurse README.md CONTRIBUTING.md docs
mkdocs build --strict
mkdocs serve
```

После запуска откройте <http://127.0.0.1:8000>. Остановите сервер сочетанием Ctrl+C.

## Публикация

Workflow `Docs` проверяет Markdown и собирает сайт для push и Pull Request. Только успешная сборка `main` публикуется через GitHub Pages. В Settings → Pages выберите Source → GitHub Actions.

Раздел доступности развивается в отдельной ветке `docs/accessibility` и проходит реальное независимое ревью. Слияние до одобрения запрещено договорённостью проекта; автоматическое одобрение не заменяет ревью студента.

## Состав

- `docs/guide/` — правила с идентификаторами и способами проверки.
- `docs/examples/` — два отредактированных фрагмента и протокол апробации.
- `docs/lab-report.md` — теория, выбор объекта, соответствие заданию и ограничения.
- `.github/workflows/docs.yml` — линтинг, строгая сборка и деплой.
