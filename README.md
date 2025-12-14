# devsecops-ci-cd-pipeline-with-automated-security-and-monitoring
Architecture 
Developer → GitLab → CI Pipeline (Build → Test → Trivy Scan → Push)
                           ↓
                      Jenkins orchestration
                           ↓
              Blue-Green Deployment (Zero downtime)
                           ↓
User → Nginx → Node.js Microservice → PostgreSQL
                           ↓
              Prometheus → Grafana (Monitoring)
                           ↓
                  Docker Compose (Ubuntu VM)
<img width="16292" height="14530" alt="Image" src="https://github.com/user-attachments/assets/cf3b3c1b-0205-47c1-b4d1-516bdd752610" />
