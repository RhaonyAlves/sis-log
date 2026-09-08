# 🚛 Sistema de Controle de Frotas e Manutenção Preventiva

![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![Versão](https://img.shields.io/badge/Vers%C3%A3o-1.2-blue)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=flat&logo=mysql&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

> Dashboard operacional e plataforma centralizada para controle de veículos, telemetria em tempo real, gestão de manutenções preventivas, controle de estoque e segurança remota de frotas corporativas.

---

## 📌 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [Problemas Identificados & Solução](#-problemas-identificados--solução)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Requisitos do Sistema](#-requisitos-do-sistema)
  - [Requisitos Funcionais (RF)](#requisitos-funcionais-rf)
  - [Requisitos Não-Funcionais (RNF)](#requisitos-não-funcionais-rnf)
- [Perfis de Usuário & Permissões](#-perfis-de-usuário--permissões)
- [Arquitetura & Tecnologias](#-arquitetura--tecnologias)
- [Integrações Previstas](#-integrações-previstas)
- [Matriz de Prioridade dos Requisitos](#-matriz-de-prioridade-dos-requisitos)
- [Autores & Créditos](#-autores--créditos)

---

## 📖 Sobre o Projeto
O projeto foi desenvolvido para atender às necessidades operacionais de empresas de transporte, logística e locação de máquinas que sofrem com a desorganização de dados descentralizados. A solução substitui o uso de planilhas de controle, apontamentos manuais e aplicativos de terceiros não integrados por um dashboard unificado em tempo real. O sistema permite acompanhar telemetria/GPS, gerenciar ordens de serviço de manutenção, controlar abastecimentos e executar bloqueios remotos de veículos em situações de emergência.

---

## 🛑 Problemas Identificados & Solução

### ❌ Cenário Atual (Dores do Cliente)
* **Processos Manuais e Fragmentados:** Uso de planilhas em Excel e cadernos para controle de entregas, estoque e agendamentos de manutenção, aumentando a margem de erro e o retrabalho.
* **Falta de Rastreamento Preciso:** Dependência exclusiva de aplicativos externos de seguro com baixa precisão para localização de veículos.
* **Comunicação Falha:** Falhas e atrasos na comunicação operacional via WhatsApp/e-mail entre motoristas, mecânicos e gestores.
* **Insegurança Operacional:** Ausência de mecanismos imediatos para bloqueio remoto em caso de imprevistos, acidentes ou suspeitas de irregularidades.

### ✅ Solução Proposta
* **Dashboard Operacional em Tempo Real:** Visualização consolidada de veículos em trânsito, manutenções pendentes e status de uso das frotas.
* **Telemetria e GPS Integrados:** Atualização instantânea da localização geográfica e identificação do condutor responsável.
* **Gestão de Manutenção Preventiva:** Abertura e acompanhamento de Ordens de Serviço (O.S.) para evitar interrupções não planejadas.
* **Segurança e Treinamento:** Bloqueio remoto de combustível/veículo, checklist para condutores e registros auditáveis (logs) de acesso.

---

## 🚀 Funcionalidades Principais

* **🏎️ Ficha do Veículo:** Consulta completa de histórico, documentação, especificações e status do veículo.
* **📊 Dashboard Operacional:** Painel central para monitoramento da frota, emissão de alertas e indicadores operacionais.
* **📍 Rastreamento GPS em Tempo Real:** Localização contínua dos veículos e identificação do motorista em operação.
* **🛠️ Gestão de Manutenção:** Abertura, acompanhamento e histórico de Ordens de Serviço (O.S.) preventivas e corretivas.
* **🚨 Bloqueio Remoto:** Comando de controle remoto para bloqueio preventivo/emergencial de combustível do veículo.
* **⛽ Módulo de Abastecimento & Custos:** Registro de notas fiscais, abastecimentos e relatórios consolidadores de custos por veículo.
* **📝 Checklist e Treinamento:** Checklist para capacitação/inspeção dos motoristas e registro de entrada/saída de veículos.
* **📑 Emissão de Notas Fiscais:** Emissão integrada de documentos fiscais para prestação de serviços.

---

## 📋 Requisitos do Sistema

### Requisitos Funcionais (RF)
| ID | Descrição |
| :--- | :--- |
| **RF01** | **Gestão de Veículos:** Cadastro, edição, exclusão e consulta à ficha detalhada do veículo. |
| **RF02** | **Abertura de O.S.:** Módulo para registro e controle de manutenções pendentes, corretivas e preventivas. |
| **RF03** | **Telemetria/GPS:** Exibição da localização em tempo real da frota e do motorista responsável. |
| **RF04** | **Bloqueio Remoto:** Recurso de segurança para bloqueio/interrupção remota de combustível dos veículos. |
| **RF05** | **Abastecimento e Custos:** Registro de abastecimentos, notas de combustível e emissão de relatórios de custos por veículo. |
| **RF06** | **Emissão Fiscal:** Módulo para geração e emissão de Notas Fiscais (NFe/CT-e). |
| **RF07** | **Checklist e Treinamento:** Ferramenta de verificação para motoristas antes da liberação de veículos. |
| **RF08** | **Log de Auditoria:** Registro detalhado de logs de entrada e saída (login/logout) e ações dos usuários no sistema. |

### Requisitos Não-Funcionais (RNF)
| ID | Descrição |
| :--- | :--- |
| **RNF01** | **Tempo Real:** Atualização contínua e sem latência dos dados de GPS e status da frota. |
| **RNF02** | **Notificações Críticas:** Emissão imediata de alertas visuais e sonoros para manutenções urgentes e pendentes. |
| **RNF03** | **Performance e Desempenho:** Interface rápida e otimizada para respostas instantâneas na operação. |
| **RNF04** | **Avisos de Vencimento:** Notificação automática sobre vencimento de cadastros e documentos de veículos. |
| **RNF05** | **Controle de Acesso (RBAC):** Níveis de permissão rígidos baseados no cargo/perfil de cada usuário. |

---

## 👥 Perfis de Usuário & Permissões

* **👔 Diretor:** Acesso a relatórios estratégicos, custos gerais da frota e métricas do negócio.
* **🎯 Gestor da Frota:** Cadastro e alocação de veículos, gestão de motoristas, controle de frotas e liberação de viagens.
* **👨‍🔧 Mecânico:** Abertura e baixa de Ordens de Serviço, registro de manutenções e verificação técnica.
* **🚛 Motorista:** Preenchimento de checklist de inspeção, reporte de problemas operacionais e consulta de rotas.
* **⚙️ Administrador de TI:** Gerenciamento de usuários, concessão de permissões, segurança e auditoria de logs.
* **📦 Reestoque / Estoque:** Controle do estoque de peças/suprimentos e realização de pedidos de reposição.

---

## 🛠️ Arquitetura & Tecnologias

### Ambientes e Ferramentas
* **Linguagem Principal:** Java
* **Banco de Dados:** MySQL / SQL Server Enterprise
* **IDE Recomendada:** Visual Studio Code (VS Code)
* **Hospedagem:** Cloud Service (Serviços em Nuvem)
* **Sistemas Operacionais Suportados:** Windows / Linux

### Visão Arquitetural
```
+-------------------------------------------------------+
|                    INTERFACE (UI)                     |
|            Dashboard Operacional / Mobile             |
+---------------------------+---------------------------+
                            |
                            v
+-------------------------------------------------------+
|                 APLICAÇÃO / SERVIÇOS                  |
|    - Módulo de Telemetria/GPS - Gestão de Manutenção  |
|    - Bloqueio Remoto          - Emissão Fiscal (NFe)  |
+---------------------------+---------------------------+
                            |
                            v
+-------------------------------------------------------+
|                  CAMADA DE DADOS                      |
|           Banco de Dados Relacional (MySQL)           |
+-------------------------------------------------------+
```

---

## 🔌 Integrações Previstas

1. **Rastreadores GPS / Satélite:** Integração com hardware de telemetria veicular para localização precisa.
2. **Sistemas Fiscais (NFe / CT-e):** Emissão e validação de notas fiscais de transporte e serviço.
3. **Gateways de Pagamento:** Processamento financeiro e controle de abastecimentos.

---

## 📊 Matriz de Prioridade dos Requisitos

| Item | Funcionalidade | Prioridade |
| :---: | :--- | :---: |
| **1** | Gestão e Cadastro de Veículos | **Crítico** |
| **2** | Rastreamento e Telemetria em Tempo Real | **Crítico** |
| **3** | Controle de Frotas e Ordens de Manutenção | **Importante** |
| **4** | Bloqueio Remoto e Checklist de Segurança | **Importante** |
| **5** | Relatórios de Custos e Roteirização Prefrencial | **Útil** |

---

## 👥 Autores & Créditos

Projeto desenvolvido como parte do programa acadêmico / de extensão do **Senac**.

### 👨‍🏫 Orientador
* **Hudson Neves**

### 👨‍💻 Equipe de Desenvolvimento
* **Fernando Tavares** - *Revisão Geral e Levantamento de Requisitos*
* **Gustavo David** - *Levantamento de Requisitos e Documentação*
* **Rhaony Alves** - *Levantamento de Requisitos e Documentação*

---
*Documento de Visão Versão 1.2 — Atualizado em Agosto/2026*
