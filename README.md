# noukwe
Corporate multilingual WordPress website for a medical technology company – custom theme, structured content, scalable architecture.

## Docker (WordPress + MySQL 8)

Prerequis: Docker Desktop.

1) Demarrer les services

```powershell
cd C:\Users\jnoumia\Docker\noukwe
docker compose up -d
```

2) Ouvrir WordPress

- http://localhost:8080

Notes:
- Les sources WordPress sont montees depuis `./wordpress`.
- Le fichier `.env` contient les identifiants MySQL (a adapter).
- `wp-config.php` sera genere au premier demarrage si absent.
