# USGS Global Earthquake Monitor | Kafka Â· PySpark Â· Elasticsearch Â· Kibana

> **Type:** Streaming | **Stack:** USGS API â†’ Kafka â†’ PySpark â†’ Elasticsearch â†’ Kibana â†’ Airflow

## Key Metrics
- **10,000â€“15,000 earthquakes/month** monitored globally
- **Geo-distance queries:** earthquakes within 2,000km of any location
- **Tsunami risk detection:** magnitude â‰¥6.5 + shallow + coastal
- **Real-time Kibana:** geospatial heatmaps + magnitude timelines

## Elasticsearch Geospatial Query
```json
{ "geo_distance": { "distance": "2000km",
    "location": { "lat": -6.2, "lon": 106.8 } } }
```

## Tech Stack
Python Â· Apache Kafka Â· PySpark Â· Elasticsearch 8 Â· Kibana Â· Airflow Â· Docker

## Author
**Ahmad Zulham Hamdan** | [LinkedIn](https://linkedin.com/in/ahmad-zulham-hamdan-665170279) | [GitHub](https://github.com/zulham-tech)
