## Tech Stack
Docker, Docker Compose  
AWS EC2, VPC, Security Groups  
Nginx, Flask  
Prometheus, Grafana  
ELK (design-level)

User
 ↓
Nginx Proxy (8601)
 ↓
Frontend (8702)
 ↓
Backend (8602)
 ↓
Observability:
   Prometheus (9090)
   Grafana (3000)
Logging:
   Elasticsearch (9200)
   Kibana (5601)
