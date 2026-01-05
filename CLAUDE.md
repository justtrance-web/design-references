# CLAUDE.md — Design References

## Обзор
База дизайн-референсов Artvision — профили с Awwwards, лучшие практики UI/UX.
Используется для создания КП и дизайна клиентов.

## Структура
```
design-references/
├── index.json          # Индекс всех референсов
├── awards/             # Сайты с наградами
│   └── {site-slug}/
│       ├── profile.yaml
│       ├── tokens.json
│       └── screenshots/
└── clients/            # Профили клиентов
    └── {client-slug}/
        └── design-profile.yaml
```

## Формат profile.yaml
```yaml
name: Site Name
url: https://example.com
colors:
  primary: "#1a1a1a"
  accent: "#ff6b35"
typography:
  heading: "Inter"
  body: "Inter"
style: minimal | luxury | corporate | playful
```

## Использование
При запросе "как у X" — найти профиль в этом репо и взять точные цвета/шрифты.

## Важные правила
1. НЕ использовать Inter по умолчанию
2. НЕ фиолетовые градиенты
3. Всегда давать ссылку на оригинал

## Контакты
Владелец: Кирилл (@justtrance)
