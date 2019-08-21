# africa-geojson
Africa-geojson is a SQL script to enable you to create a database table in PostGres with African Continent GeoJSON data.

## Set Up

You need access to a PostGresql database instance. Download the file and run the following command in the terminal:
```bash
psql -U [database-username] countries < africa.geojson.sql
```

