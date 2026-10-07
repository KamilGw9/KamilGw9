# Kamil Gwóźdź

I build data pipelines and the cloud infrastructure they run on, mostly on Azure Databricks and GCP.

Day to day that means Python, SQL and Spark (PySpark, some Scala), Terraform for the infrastructure, and GitHub Actions for deployments.

## Projects

**[BinanceStream](https://github.com/KamilGw9/BinanceStream)**: Binance trades, order book and 1-minute klines read over WebSocket and written to Bronze / Silver / Gold Delta tables on Azure Databricks. The ingest job is in Scala and the DLT pipeline is in Python. Infrastructure is Terraform, the Databricks side is an Asset Bundle, and both deploy from GitHub Actions.

**[gcp-devops-pipeline](https://github.com/KamilGw9/gcp-devops-pipeline)**: a small Flask API for crypto prices. The API is only there to justify the setup around it: GKE provisioned with Terraform, an NGINX ingress with Let's Encrypt certificates, network policies, Prometheus and Grafana, and CI/CD.

**[logistics-data-proj](https://github.com/KamilGw9/logistics-data-proj)**: Terraform for a GCP data lake for transport data, with GCS bronze/silver/gold buckets, Pub/Sub, a BigQuery mart and a single-node Dataproc cluster with Delta. So far it is infrastructure only.

**[Players_stats_analysis](https://github.com/KamilGw9/Players_stats_analysis)**: an older pandas notebook on La Liga 2023/24 player stats.
