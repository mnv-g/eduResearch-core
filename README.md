# eduResearch Core

Standalone research and deployment repository for a FastAPI-based network service management panel.

## Components

- FastAPI / Uvicorn backend
- Web management interface
- User and subscription management
- Node and worker orchestration
- Network scanning and health checks
- Telegram automation
- Railway / Docker deployment support

## Deployment

The application listens on port `8080`.

### Docker / Railway

The repository includes `Dockerfile` and `railway.toml` for deployment.

### VPS

Run the included installer:

```bash
curl -fsSL https://raw.githubusercontent.com/mnv-g/eduResearch-core/main/start.sh | bash
```

## Security

Keep tokens, passwords, API keys and deployment credentials outside the repository and provide them through protected environment or server configuration.
