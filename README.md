# Gerçek Zamanlı Büyük Veri Tabanlı Adaptif Trafik Sinyal Kontrol Sistemi

SUMO, Apache Kafka, Spark Structured Streaming, ClickHouse, Grafana ve Docker Compose
kullanarak eşik tabanlı adaptif trafik sinyal kontrolü prototipi.

## Mimari

SUMO (TraCI) → Kafka producer → Kafka → Spark Streaming → ClickHouse → Grafana
                    ↑                                  ↓
                    └──────── Karar servisi ◄──────────┘

## Çalıştırma

Çalıştırma adımları proje ilerledikçe eklenecektir.

```bash
docker compose up
```

## Kullanılan Araçlar

SUMO, OpenStreetMap, Python + TraCI, Apache Kafka, Spark Structured Streaming,
ClickHouse, Grafana, Docker Compose, Git.
