# ZerocoderTest

Тестовый репозиторий, созданный через **GitHub MCP Server**.

## Как это было сделано

Подключение настроено локальным сервером `github-mcp-server` (stdio), так как
хостед-сервер `api.githubcopilot.com` недоступен из текущего региона (HTTP 403).

- Бинарник: `github-mcp-server` v2.0.2
- Авторизация: Personal Access Token через переменную окружения `GITHUB_PERSONAL_ACCESS_TOKEN`
- Хост-приложение: opencode

## Команды MCP, использованные для создания

| Инструмент | Что делает |
| --- | --- |
| `github_create_repository` | Создал репозиторий с автозаполнением README |
| `github_get_file_contents` | Прочитал содержимое `README.md` |
| `github_create_or_update_file` | Записал этот текст в `README.md` |

## Полезные ссылки

- [Документация GitHub MCP Server](https://github.com/github/github-mcp-server)
- [API GitHub](https://docs.github.com/en/rest)
