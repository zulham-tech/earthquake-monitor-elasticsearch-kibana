# USGS Global Earthquake Monitor | Elasticsearch, Kibana

**Stack:** USGS API -> Kafka -> PySpark -> Elasticsearch -> Kibana -> Airflow

## Key Metrics
- 10,000-15,000 earthquakes/month monitored globally
- Geo-distance radius queries: earthquakes within 2,000km of any location
- Tsunami risk detection: magnitude >= 6.5 + shallow depth + coastal location
- Real-time Kibana: geospatial heatmaps + magnitude timelines

## Elasticsearch Geospatial Query
```json
{ "geo_distance": { "distance": "2000km",
    "location": { "lat": -6.2, "lon": 106.8 } } }
```

## Tech Stack
Python, Apache Kafka, PySpark, Elasticsearch 8, Kibana, Airflow, Docker

## Author
Ahmad Zulham Hamdan | https://linkedin.com/in/ahmad-zulham-665170279
