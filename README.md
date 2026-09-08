---

## 🔌 Integrações Previstas

Para pleno funcionamento no ambiente hospitalar, o sistema prevê integração com as seguintes plataformas:
1. **CRM (Customer Relationship Management):** Gestão do relacionamento e histórico do cliente.
2. **Prontuário Eletrônico (PEP):** Sincronização do histórico clínico do paciente.
3. **Gateway de Pagamentos:** Processamento de pagamentos de consultas e exames particulares.

---

## 📊 Matriz de Prioridade dos Requisitos

| Item | Funcionalidade | Prioridade | Entrega |
| :---: | :--- | :---: | :---: |
| **1** | Marcar consultas e atendimentos | **Crítico** | Fase 1 |
| **2** | Bate-papo / Chat com equipe médica | **Importante** | Fase 1 |
| **3** | Notificações e lembretes de consultas (15d / 1d) | **Útil** | Fase 2 |

---

## 👥 Autores & Créditos

Projeto desenvolvido como parte do programa acadêmico / de extensão do **Senac**.

### 👨‍🏫 Orientador
* **Hudson Neves**

### 👨‍💻 Equipe de Desenvolvimento
* **Fernando Tavares** - *Revisão Geral e Levantamento de Requisitos* 
* **Gustavo David** - *Levantamento de Requisitos e Documentação* [cite: 1, 2]
* **Rhaony Alves** - *Levantamento de Requisitos e Documentação* [cite: 1, 2]

---
*Documento de Visão Versão 1.2 — Atualizado em Setembro/2026* [cite: 1]
"""

readme_path = "README.md"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

print("README.md atualizado com sucesso!")
