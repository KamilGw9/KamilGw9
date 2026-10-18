# Kamil Gwóźdź

I work in data engineering. I'm especially interested in modern data platforms, cloud infrastructure, lakehouse architectures and streaming. The projects here are where I try things out and learn by building.

I work with Python, SQL, dbt, Airflow, Azure and Databricks. I also have some experience with AWS, GCP, Terraform and Spark.

## Projects

**[BinanceStream](https://github.com/KamilGw9/BinanceStream)**: Binance trades, order book and 1-minute klines read over WebSocket and written to Bronze / Silver / Gold Delta tables on Azure Databricks. The ingest job is in Scala and the DLT pipeline is in Python. Infrastructure is Terraform, the Databricks side is an Asset Bundle, and both deploy from GitHub Actions.

**[gcp-devops-pipeline](https://github.com/KamilGw9/gcp-devops-pipeline)**: a small Flask API for crypto prices. The API is only there to justify the setup around it: GKE provisioned with Terraform, an NGINX ingress with Let's Encrypt certificates, network policies, Prometheus and Grafana, and CI/CD.

**[Players_stats_analysis](https://github.com/KamilGw9/Players_stats_analysis)**: an older pandas notebook on La Liga 2023/24 player stats.
