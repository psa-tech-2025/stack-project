# stack-project

✅ 1️⃣ Monorepo (Single Git Repo)

fullstack-project/
│── frontend/                # Angular app
│   ├── src/
│   ├── Dockerfile
│   └── package.json
│
│── backend/                 # Node.js app
│   ├── src/
│   ├── Dockerfile
│   └── package.json
│
│── database/
│   └── mongo-init.js        # Mongo config, seed data
│
│── infra/                   # Infrastructure & deployment
│   ├── docker-compose.yml
│   ├── ansible/
│   │   ├── playbooks.yml
│   │   └── inventory.ini
│   ├── k8s/
│   │   ├── frontend-deploy.yml
│   │   ├── backend-deploy.yml
│   │   └── mongo-deploy.yml
│   ├── terraform/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── outputs.tf
│   └── Jenkinsfile
│
└── README.md
