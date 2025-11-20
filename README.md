<img width="1536" height="994" alt="image" src="https://github.com/user-attachments/assets/e5e6cfb5-9681-4f37-9685-bc78b4686b67" />

###  Data Analitycs and Visualization  | Kubernetes ☸️
Data-analytics-visualization refers to the process where data analytics uncovers insights from datasets, and data visualization communicates those insights through graphical means like charts, graphs, and maps to help people understand trends, patterns, and outliers quickly. Together, data analytics and visualization empower organizations to make better-informed, data-driven decisions by transforming complex raw data into a strategic, accessible asset.


#### 🧱 Architecture Components :
   - **Longhorn (StorageClass):**: distributed block storage.
   - **MinIO (S3 Object Storage):**: object storage,Used for storing raw data files.
   - **Apache Druid**: is a high performance real-time analytics database.
   - **SuperSet**: is a modern data exploration and data visualization platform.



🔨 Workflow Overview
```
✅ Coordinator,processes manage data availability on the cluster.
✅ Overlord,processes control the assignment of data ingestion workloads.
✅ Broker,processes handle queries from external clients.
✅ Router,processes are optional; they route requests to Brokers, Coordinators, and Overlords.
✅ Historical,processes store queryable data.
✅ MiddleManager,Processes ingest data.
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```
