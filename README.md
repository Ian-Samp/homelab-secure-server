![](assets/homelab_banner.png)
## Visão Geral
### Objetivo
Este projeto visa documentar o processo de desenvolvimento, proteção e otimização de um servidor Linux caseiro (home lab) de serviços auto-hospedados construído a partir de um notebook antigo. Espero conseguir demonstrar a evolução, não apenas do servidor, mas principalmente de meus conhecimentos em relação à redes de computador, hardware, terminal Linux e defesa em profundidade.

### Informações do Servidor
- **Hardware:** notebook Samsung antigo
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
| Redução de Overhead | Conversão para Headless resiultando na economia de 10% de memória RAM desperdiçada pela GUI |
| Acesso Remoto Seguro | VPN Mesh via Tailscale permitindo acesso remoto sem necessidade de abrir portas do roteador para internet |
| Detector de Brute Force (SSH) | Mini-SIEM gera alerta imediatamente ao detectar múltiplas falhas de acesso remoto via SSH |
