![](assets/homelab_banner.png)
## Visão Geral
### Objetivo
O servidor **moony** foi construido a partir de um hardware reaproveitado com a finalidade de hostear serviços auto-hospedados e servir como um ambiente controlado para laboratórios de cibersegurança. Espero conseguir demonstrar a evolução, não apenas do servidor, mas principalmente dos meus conhecimentos em relação a redes de computadores, hardware, terminal Linux e defesa em profundidade.

### Informações do Servidor
- **Hardware:** Notebook Samsung antigo
  - **Processador:** Intel i3 (2 núcleos)
  - **Memória RAM:** 4 GB
  - **Armazenamento:** 1TB (HD)
- **Sistema Operacional:** Ubuntu Server 24.04 LTS
- **Gerenciador de Serviços:** CasaOS
- **Hostname:** moony
- **Início do Desenvolvimento:** Abril, 2026

## Destaques do Projeto
| Ação | Descrição |
| :--- |   :---    |
| Redução de Overhead | Conversão para Headless resultando na economia de 10% de memória RAM desperdiçada pela GUI |
| Acesso Remoto Seguro | VPN Mesh via Tailscale permitindo acesso remoto sem necessidade de port forwarding do roteador |
| Detector de Brute Force (SSH) | Mini-SIEM gera alerta imediatamente ao detectar múltiplas falhas de acesso remoto via SSH |
