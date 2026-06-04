# Homelab - Secure Server

## Objetivo

Este projeto documenta a evolução de um servidor doméstico (homelab) focado em serviços self-hosted. O objetivo do projeto é, iniciando com uma infraestrutura mínima, transformar o homelab em um ambiente seguro, aplicando técnicas de hardening, monitoramento e segurança em camadas.

## Informações do Servidor
- Notebook antigo
- 2 núcleos, 4GB RAM
- Ubuntu Server 24.04 LTS
- CasaOS

## 🔎 Pilar 0: Análise de Riscos
- [ ] **Modelagem de Ameaças:** análise de ativos críticos e superfície de ataque.
- [ ] **Inventário de Serviços:** mapeamento de portas abertas e contêiners ativos.

## 🛡️ Pilar 1: Hardening de Sistema Operacional e Rede
- [ ] **Firewall Local:**

## 🌐 Pilar 2: Acesso Remoto Seguro
- [ ] **Criptografia em Trânsito:** certificado (HTTPS) via Tailscale como prevenção de Man-In-The-Middle durante uso remoto do CasaOS.

## 📊 Pilar 3: Monitoramento & Defesa Ativa
- [ ] **Defesa Ativa:** configuração de Fail2Ban em SSH para banimento automático de IPs maliciosos.
- [ ] **Gerenciamento de logs (SIEM):** centralização e auditoria do sistema em repositório seguro.
