# apache-airflow
Instructions to install Apache-Airflow on Docker Container

Firstly, in the root directory create three more directories: dags, logs, and scripts. Further, create following files: .env, docker-compose.yml, entrypoint.sh and dummy_dag.py. Please make sure those files and directories follow the structure below.
#project structure
root/
├── dags/
│   └── dummy_dag.py
├── scripts/
│   └── entrypoint.sh
├── logs/
├── .env
└── docker-compose.yml
