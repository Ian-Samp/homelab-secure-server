# Modelagem de Ameaças

## Introdução
Este documento é um relatório de modelagem de ameaças de um servidor caseiro, desenvolvido para colocar em prática minhas habilidades de documentação e análise de riscos. Neste relatório, pretendo responder às quatro perguntas de Adam Shostack:

1. Em que estamos trabalhando?
2. O que pode dar errado?
3. O que vamos fazer a respeito?
4. Fizemos um bom trabalho?

---

### 1. Em que estamos trabalhando?

*   **Descrição:** O homelab é um servidor doméstico que hospeda serviços para o usuário. Sua principal função é servir como nuvem, guardando informações pessoais sensíveis. Por estar em início de desenvolvimento, o servidor está limitado a um único usuário (administrador).

#### Dependências Externas
| ID | Nome | Descrição |
| :--- | :--- | :--- |
| 1 | Provedor de Internet (ISP) | Fornece o link de internet e o roteamento inicial da rede doméstica. |
| 2 | Serviços do CasaOS | Plataformas externas integradas via AppStore do CasaOS. |

#### Pontos de Entrada
| ID | Nome | Descrição | Quem tem acesso |
| :--- | :--- | :--- | :--- |
| **1** | **Painel de Controle** | **Painel do CasaOS que permite controlar o sistema pelo navegador.** | |
| 1.1 | Página de login via IP | O painel do CasaOS exige um login de usuário que pode ser acessado pelo IP do servidor. | (1) Qualquer dispositivo conectado na LAN; <br>(2) Qualquer dispositivo conectado na rede de VPN. |
| 1.2 | Página de login via MagicDNS | O painel do CasaOS exige um login de usuário que pode ser acessado pelo DNS configurado pelo Tailscale. | (1) Qualquer dispositivo conectado na rede de VPN. |
| **2** | **Portas Abertas** | |
| 2.1 | 

#### Ativos
Análise de ativos que possuem valor para o proprietário ou que possam ser de interesse para um atacante.

| ID | Nome | Descrição |
| :--- | :--- | :--- |
| **1** | **Usuário** | **Recursos relacionados à identidade e dados do usuário.** |
| 1.1 | Credenciais de usuário | Credenciais de login usadas pelo usuário para acessar os serviços e painéis. |
| 1.2 | Informações pessoais | Dados sensíveis armazenados no serviço de nuvem do servidor. |
| **2** | **Sistema** | **Recursos relacionados aos softwares e hardwares do sistema.** |
| 2.1 | Disponibilidade de serviços | Garantia de que os serviços do homelab permaneçam online e operacionais. |
| 2.2 | Acesso remoto do terminal | Capacidade do usuário de executar comandos no terminal Linux através do painel do CasaOS. |
| 2.3 | Acesso físico do terminal | Capacidade de interagir diretamente com o hardware e a CLI do servidor localmente. |

---

### 2. O que pode dar errado?


### 3. O que vamos fazer a respeito?


### 4. Fizemos um bom trabalho?
