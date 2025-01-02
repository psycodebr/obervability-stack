### Projeto de Observability GPT Challenge ###

observability-stack/
├── docker-compose.yml                # Arquivo de orquestração para rodar os containers do projeto
├── prometheus/
│   └── prometheus.yml                # Configuração do Prometheus, incluindo regras de scraping e alertas
├── grafana/
│   └── provisioning/                 # Diretório de provisionamento do Grafana
│       ├── datasources/              # Diretório para configuração das fontes de dados
│       │   └── datasource.yml        # Configuração da fonte de dados (Prometheus)
│       ├── dashboards/               # Diretório para configuração dos dashboards
│       │   └── dashboard.json        # Configuração do dashboard inicial
├── README.md                         # Documentação do projeto
