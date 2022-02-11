# Prestashop Sarah shop
This is for university task purpose

# Requirements
- [Docker](https://docs.docker.com/get-docker/)
- Prestashop 1.7
- MariaDB 10.4

# installation
1. Install [Docker](https://docs.docker.com/get-docker/)
2. Clone this project
3. Copy `.env.example` and paste as `.env`
4. Then fill appropriate your environment
5. Run in terminal `docker compose -f docker-compose.migration.yml up` for create new database
5. Run in terminal `docker compose up -d` to running in development server
6. Wait for new images downloaded. Check logs for futher
7. Open in browser http://localhost:8080

