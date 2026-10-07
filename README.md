# Kamil Gwóźdź

I'm interested in data engineering, especially in how data platforms are built: lakehouse and streaming architectures and the infrastructure underneath them. Lately I'm also interested in how AI tools like Claude change the way these systems get built.

The repos here are where I try those ideas out, mostly on Azure Databricks and GCP. I use Python, SQL, Spark, Terraform and GitHub Actions the most.

## Projects

**[BinanceStream](https://github.com/KamilGw9/BinanceStream)**: Binance trades, order book and 1-minute klines read over WebSocket and written to Bronze / Silver / Gold Delta tables on Azure Databricks. The ingest job is in Scala and the DLT pipeline is in Python. Infrastructure is Terraform, the Databricks side is an Asset Bundle, and both deploy from GitHub Actions.

**[gcp-devops-pipeline](https://github.com/KamilGw9/gcp-devops-pipeline)**: a small Flask API for crypto prices. The API is only there to justify the setup around it: GKE provisioned with Terraform, an NGINX ingress with Let's Encrypt certificates, network policies, Prometheus and Grafana, and CI/CD.

**[Players_stats_analysis](https://github.com/KamilGw9/Players_stats_analysis)**: an older pandas notebook on La Liga 2023/24 player stats.
