# Install

```sh
git clone -b dev https://github.com/Humans-Connexion/xivoglpi.git
docker-compose up -d
```

```sh
docker run --name glpi --hostname glpi --link mariadb:mariadb --volumes-from glpi-data -p 80:80 --env "TIMEZONE=Europe/Brussels" -d diouxx/glpi
```

# Config

log on http://localhost->install->Mysql/glpi_user/glpi->glpidb

Use cred : glpi/glpi
