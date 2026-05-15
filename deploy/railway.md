# Deploy to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/sourcebans-pp)

## Quick Deploy

Click the button above to deploy SourceBans++ to Railway.

## What gets deployed

- **Web Application**: PHP 8.2 + Apache
- **Database**: MySQL 8.0
- **Cache**: Redis (optional)

## Environment Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `DB_HOST` | MySQL hostname | (auto) |
| `DB_PORT` | MySQL port | 3306 |
| `DB_NAME` | Database name | sourcebans |
| `DB_USER` | Database user | root |
| `DB_PASS` | Database password | (auto) |
| `SB_URL` | Public URL | (auto) |

## Post-Deploy Steps

1. Visit your app URL
2. Follow the installation wizard
3. Configure your game server connections
4. Set up admin accounts

## Requirements

- Railway account
- Source game server (TF2, CS:S, GMod, etc.)

## Related

- [Docker Hub Image](https://hub.docker.com/r/sourcebans/sourcebans-pp)
- [Documentation](https://sbpp.dev)
