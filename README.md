# AI Agent Platform (Self-hosted)

Полная платформа автоматизации и локальных LLM на Docker.

## Установка

```bash
git clone https://github.com/yourusername/ai-agent-platform.git
cd ai-agent-platform
docker-compose up -d
```

## Сервисы

| Сервис     | Порт   |
|------------|--------|
| n8n        | 5678   |
| Flowise    | 3001   |
| Open WebUI | 3000   |
| Ollama     | 11434  |
| Supabase   | 5432   |
| Qdrant     | 6333   |
| SearXNG    | 8080   |
| Langfuse   | 3002   |
| Caddy      | 80/443 |

## Настройки

- `.env` файл для DOMAIN и паролей
- `docker-compose.yml` содержит конфигурации
- `Caddyfile` настраивает HTTPS