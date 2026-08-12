# Misamo Capital
`Research and Execution`<br>
This repository is a modular quantitative research and execution system for RWA/Commodity related research and strategies.<br>
It will be designed to evolve from research notebooks into independent data, pricing, risk, signal, and execution microservices.

## Work In Progress
Building out the foundation, by starting with xU3O8 (tokenised RWA of Uranium Ore, yellowcake). Working towards a containerized pricing service, establishing the architecture for scalable, testable, and fault-isolated research and trading.

## First Milestone
```text
misamo_capital/
├── research/
│   └── xu3o8/
│       └── research.ipynb
│
├── services/
│   └── pricing/
│       ├── app/
│       │   ├── main.py
│       │   └── pricing.py
│       ├── tests/
│       ├── Dockerfile
│       └── requirements.txt
│
├── docker-compose.yml
├── README.md
└── .gitignore
```
