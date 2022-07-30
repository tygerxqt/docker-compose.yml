
# Supabase + Docker compose

The `docker-compose.yml` config assumes you have a domain (lofu.studio) and the ports `80` and `443` open for the proxy. An .env file has already been made but I strongly recommend using a secrets manager when deploying to production. Plain text files like dotenv lead to accidental costly leaks.

## Docs

[Supabase Docker Page](https://supabase.com/docs/guides/hosting/docker)