# 🚀 PORTFÓLIO DE LABORATÓRIOS PRÁTICOS: INFRAESTRUTURA E SERVICE DESK

**Profissional:** Fabiana Soares  
**Objetivo:** Demonstração de competências técnicas aplicadas em suporte N1/N2, Redes, Virtualização e Administração de Identidades.

---

### 📂 PROJETO 1: Provisionamento de Ambiente Virtualizado (Hypervisor)
* **Tecnologia Utilizada:** Oracle VirtualBox.
* **Escopo Prático:** 
  * Criação, dimensionamento de hardware virtual (Memória RAM, VDI Dinamicamente Alocado) e provisionamento de sistemas operacionais corporativos do zero.
  * Instalação e calibração de drivers avançados (**VirtualBox Guest Additions**) para habilitar o controle de Área de Transferência Compartilhada Bidirecional.
  * Configuração e segmentação de placas de rede virtuais (Modo NAT para isolamento seguro e Rede Interna para simulação de infraestrutura corporativa isolada).

### 🏛️ PROJETO 2: Implementação e Governança de Active Directory (AD DS)
* **Tecnologia Utilizada:** Windows Server 2022, Active Directory Users and Computers (ADUC).
* **Escopo Prático:**
  * Instalação da Role de **Active Directory Domain Services (AD DS)** via Server Manager.
  * Promoção do servidor a **Controlador de Domínio (Domain Controller)** configurando uma nova floresta de rede sob o domínio raiz `empresa.local`.
  * Estruturação de Governança de Dados através da criação de **Unidades Organizacionais (OUs)** para segmentação de departamentos (Criação da OU `TI`).
  * Provisionamento de contas de usuários seguindo padrões rigorosos de mercado (Logon Name padronizado em letras minúsculas: `fabiana.soares`).

### 🔒 PROJETO 3: Rotinas Operacionais de Service Desk e Segurança (LGPD)
* **Tecnologia Utilizada:** Painel ADUC, Diretrizes de Governança e Proteção de Dados.
* **Escopo Prático:**
  * Execução de **Reset de Senha (Password Reset)** corporativo com aplicação mandatória do parâmetro *“User must change password at next logon”*.
  * Tratamento de incidentes de bloqueio de segurança por força bruta através do procedimento de **Desbloqueio de Conta (Unlock Account)**.
  * Alinhamento com a **LGPD (Lei Geral de Proteção de Dados)**: Processo de dupla checagem de identidade do usuário antes da manipulação de credenciais ou senhas temporárias complexas.

### 🖥️ PROJETO 4: Automação e Troubleshooting de Redes via Terminal
* **Tecnologia Utilizada:** Windows PowerShell e CMD.
* **Escopo Prático:**
  * Diagnóstico de resolução de nomes e falhas na camada de aplicação através da limpeza física do cache de DNS (`ipconfig /flushdns`).
  * Testes lógicos e validação de comunicação em portas de segurança específicas (Teste de handshake TCP na porta segura `443` contra o host `google.com` e servidores do AnyDesk) utilizando o cmdlet `Test-NetConnection`.
  * Domínio de manipulação de buffer do terminal e tratamento de travamentos de linhas de execução utilizando interrupções por hardware (`Ctrl + C`).

### 📊 PROJETO 5: Alinhamento de Processos de Negócio (ITIL v4 & Jira)
* **Tecnologia Utilizada:** Jira Service Management e Framework ITIL v4.
* **Escopo Prático:**
  * Gerenciamento do ciclo de vida de tickets em fila de atendimento técnico Home Office de alta performance.
  * Classificação analítica de demandas com base no impacto de negócio: Triagem precisa entre **Incidentes** (interrupções não planejadas de serviço) e **Requisições de Serviço** (demandas de concessão/rotina padrão).
  * Controle operacional focado em criticidade de chamados para o cumprimento rigoroso de **SLAs (Acordo de Nível de Serviço)** acordados com a empresa.

---

## 🚀 Novos Laboratórios Práticos (Novembro/2026)

### 🛠️ 1. Troubleshooting de Redes e Gestão de Credenciais (Windows)
**Data de Execução:** 11/2026  
**Objetivo:** Simular rotinas de Service Desk N1, diagnosticando conectividade de hosts e gerenciando acessos.

*   **Comandos de Diagnóstico:** `ipconfig /all`, `ping 8.8.8.8`, `nslookup google.com` para analisar endereçamentos, rotas e resolução de nomes DNS.
*   **Administração de Usuários (Active Directory):** Localização de objetos na árvore de diretório, execução de **Reset de Senha** corporativa e aplicação de **Unlock Account** (Desbloqueio de Conta).

<p align="center">
  <img src="imagens/print-redes.png" alt="Terminal Windows" width="80%">
</p>
<p align="center">
  <img src="imagens/print-ad.png" alt="Active Directory" width="80%">
</p>

---

### 🛠️ 2. Gerenciamento de Pacotes e Atualização de Sistemas (Linux Mint)
**Data de Execução:** 11/2026  
**Objetivo:** Praticar a manutenção de ambientes Linux via terminal usando o gerenciador avançado (`apt`).

*   **Atualização do Sistema:** Uso do `sudo apt update` para sincronizar os repositórios oficiais e `sudo apt upgrade -y` para instalar updates pendentes de forma segura.
*   **Manipulação de Softwares:** Comandos `sudo apt install` e `sudo apt remove` para o controle limpo de aplicações necessárias para a operação da empresa.

<p align="center">
  <img src="imagens/print-linux1.png" alt="Terminal Linux" width="80%">
</p>

---

### 🛠️ 3. Manipulação de Arquivos, Permissões e Redes (Linux Mint)
**Data de Execução:** 11/2026  
**Objetivo:** Praticar navegação estruturada de arquivos e validação de interfaces de rede em ambiente Unix-like corporativo.

*   **Comandos de Arquivos:** Uso de `mkdir` para criação de diretórios, `touch` para novos arquivos de texto, e comandos corporativos essenciais como `cp`, `mv` e `rm`.
*   **Redes no Linux:** Uso do comando `ip a` para listagem e validação das placas de rede ativas e `ping -c 4` para conferência de estabilidade.

<p align="center">
  <img src="imagens/print-linux2.png" alt="Redes Linux" width="80%">
</p>

---

### 📊 4. Análise de Dados e Construção de Dashboards (Microsoft Excel)
**Data de Execução:** 11/2026  
**Objetivo:** Estruturar relatórios operacionais dinâmicos para controle de métricas de atendimento e volumetria de incidentes.

*   **Fórmulas Avançadas:** Aplicação de `PROCX` / `PROCV` para cruzamento de dados de ativos, e funções lógicas como `SE`, `CONT.SE` e `SOMASE` para controle estrito de **SLAs**.
*   **Visualização (Dashboards):** Criação de **Tabelas Dinâmicas** integradas a **Gráficos Dinâmicos** e botões de **Segmentação de Dados (Slicers)** para relatórios de desempenho gerenciais interativos.

<p align="center">
  <img src="imagens/print-excel.png" alt="Dashboard Excel" width="80%">
</p>
