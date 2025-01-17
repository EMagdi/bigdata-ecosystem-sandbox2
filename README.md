# bigdata-ecosystem-sanbox
BES (Bigdata Ecosystem Sandbox) is an all-in-one development and learning environment designed to simplify the exploration, experimentation, and development of big data technologies.

# Prerequisites

- Docker & Docker Compose
- RAM: 10 GB
- CPU: 4 Cores
- Storage: 40 GB

# Sandbox Components

This platform contains the following tools:

- PostgreSQL
- MinIO
- Hadoop
- Hive
- Spark
- Trino
- NiFi
- Kafka
- Flink
- Iceberg
- Airflow

# Getting Started

### Setup ALL the Sandbox Tools

“Make sure that you have enough CPU and RAM”

To Setup all the sandbox tools use the following script

```bash
git clone https://github.com/amhhaggag/bigdata-ecosystem-sandbox.git
cd bigdata-ecosystem-sandbox

./bes-setup.sh
```

This command will do the following:

1. Pull the necessary Docker images from Docker Hub
   - amhhaggag/hadoop-base-3.1.1
   - amhhaggag/hive-base-3.1.2
   - amhhaggag/spark-3.5.1
2. Prepare the PostgreSQL Database for Hive-Metastore Service
3. Add the Trino Configurations to it’s specific mounted volume (Local Directory)
4. Create and Start all the containers



# Currently Working On
- Building a Command Line Interface for the Sandbox.

# Future Plans for the Sandbox
- Adding the Following Tools
   - MongoDB
   - Druid
   - Superset
  
Let's Connect if you are interested!
