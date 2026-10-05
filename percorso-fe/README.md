# Bootcamp Docker & DevOps — Project work

## Setup
```bash
# Scegli il tuo percorso
cd percorso-be    # oppure: cd percorso-fe
Avvio stack locale
docker compose up -d --build
docker compose ps
docker compose logs -f
Smoke test
BE: curl http://localhost:3000/healthz
FE: aprire http://localhost:8080 nel browser
Tear down
docker compose down
docker compose down -v   # con rimozione volumi
```