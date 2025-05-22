# Mini Azure in a Box

A fully local, Docker-powered, fake cloud provider that simulates VM provisioning, container orchestration, load balancing, and service discovery. Think of it as your own DIY Azure built entirely with open-source tools.

## Stack
- Docker
- NGINX (Load Balancer / Reverse Proxy)
- Bash scripts (Orchestration)
- SQLite (Service Registry)
- (Optional) VirtualBox + Vagrant (Infrastructure simulation)

## What Can You Learn
- Provisioning and orchestration logic
- Service discovery with SQLite
- Load balancing and reverse proxying
- Local resource monitoring and lifecycle management

## Getting Started

```bash
git clone https://github.com/your-user/mini-azure-in-a-box.git
cd mini-azure-in-a-box
chmod +x scripts/*.sh
./scripts/start_mini_azure.sh
