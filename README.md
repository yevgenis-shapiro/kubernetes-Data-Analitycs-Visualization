<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/c0b42cf5-a98e-48ac-85d1-9788fd438dd7" />



###  Data Analitycs and Visualization  | Kubernetes ☸️
Delta Lake is an open-source storage framework that is used to build data lakes on top of object storage in a Lakehouse architecture. Delta Lake supports ACID transactions, scalable metadata handling and unified streaming and batch data processing. Delta Lake is commonly used to provide reliability, consistency, and scalability to Apache Spark applications. Delta Lake runs on the top of the existing data lake storage, such as MinIO, and is compatible with Apache Spark APIs.

Lakehouse architecture, Delta Lake in particular, brings key new functionality to data lakes built on object storage. Delta Lake works with a large and growing list of applications and compute engines such as Spark, Starburst, Trino, Flink, and Hive, and also includes APIs for Scala, Java, Rust, Ruby and Python. Built for the cloud, Kubernetes-native MinIO enables performant, resilient and secure data lake applications everywhere - at the edge, in the data center and in the public/private cloud.


#### 🧱 Architecture Components :
   - **MinIO (S3 Storage):**: object storage,Used for storing raw data files.
   - **Apache Druid**: (Table Format): Storage Layer
   - **SuperSet**: Data Integration Platform | ELT Tool
   - **Velero**: Disaster recovery, and migrate Kubernetes cluster resources



🔨 Workflow Overview
```
✅ ACID Guarantees:
✅ Scalable data and metadata handling
✅ Audit history and time travel
✅ Schema enforcement and schema evolution
✅ Support for deletes, updates and merges
✅ Streaming and batch unification
✅ Caching
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```
