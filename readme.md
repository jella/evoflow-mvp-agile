# 📊 Evoflow
Trabalho MVP Sprint de Gestão Ágil de Projetos e Produtos do Curso de Pos graduação em engenharia de software da PUC-RIO

## 🎯 Cenário de Negócio
O EvoFlow nasce em uma empresa pública de tecnologia que apoia diferentes órgãos do governo no desenvolvimento de soluções digitais.  

**Problema atual:** os times usam o GitLab, mas de formas diferentes, com boards heterogêneos e sem métricas comparáveis. Isso gera baixa previsibilidade, dificuldade de priorização e sobrecarga em Product Owners.  

**Oportunidade:** fornecer uma plataforma integrada ao GitLab que transforma os dados de issues e merge requests em insights de fluxo e maturidade KMM, ajudando times a evoluírem de forma contínua, desde iniciantes (nível 1) até avançados (nível 6).  

---

## 👥 Mapeamento de Stakeholders
- **Gestores  (Ex.: Eduardo):** tomam decisões de alocação, negociam prazos e precisam de informações rápidas, relatórios executivos e visão consolidada de performance entre equipes. 
- **Product Owners (Ex.: Carla):** acumulam funções de backlog, priorização e acompanhamento do time → precisam de métricas claras.  
- **Equipe de Desenvolvimento (Ex.: Rogério):** busca clareza no fluxo, redução de multitarefa e feedback sobre produtividade.  
- **Agile Coaches / Consultores externos:** (quando existem) apoiam evolução em práticas de fluxo e maturidade organizacional.  

---

## 👩‍💻 Time Scrum (time enxuto para o MVP)
- **PO:** define backlog, alinha stakeholders, garante valor de negócio.  
- **Scrum Master (opcional, pode ser acumulado pelo PO):** facilita cerimônias e remoção de impedimentos.  
- **2 Devs Fullstack (incluindo Rogério):** responsáveis por integração GitLab, board Kanban e dashboard.  
- **1 UX Designer:** cria wireframes e garante usabilidade.  

👉 **Time total:** 3 a 4 pessoas, entrega enxuta em 3–4 semanas por MVP.  

## ▶️ Link da Apresentação Youtube  - Lean Inception
👉 [Clique aqui Apresentação Youtube](https://tinyurl.com/evoflow-mvp)

## 🎯 Link do Board  - Lean Inception
👉 [Clique aqui Board Miro](https://miro.com/app/board/uXjVJCEiDYY=/?share_link_id=946748718869)
---

## 🎯 MVP Canvas
**MVP 1 – Visibilidade de Fluxo**  

**Problema:** falta de visibilidade ponta a ponta e métricas confiáveis.  

**Solução:** integração com GitLab, ashboard de Métricas Básicas, Visualização Kanban Simplificada básicas.  

**Personas Impactadas:** devs (operacional), PO (tático), gestor intermediário (estratégico).  

**Hipóteses a Validar:**  
- Times adotam o board simplificado para alinhar fluxo.  
- POs usam métricas básicas em reuniões semanais.  
- Gestores consultam o dashboard em até 2 min para tomar decisão.  

**Métricas de Sucesso:** nº de equipes usando, tempo médio de login / board, acessos semanais ao dashboard.  

---

## 📌 Backlog Inicial 

👉 [Backlog do Jira](backlog/backlog-jira.pdf)

### Épico 1 – Integração com GitLab
- [PME-10– Conectar repositório GitLab](backlog/img/PME-10.png)  
- [PME-11– eIssues atualizadas em tempo ral](backlog/img/PME-11.png)  

### Épico 2 – Dashboard de Métricas Básicas
- [PME-12– Visualizar métricas (lead time, throughput, aging WIP)](backlog/img/PME-12.png)  
- [PME-13– Acompanhar aging WIP para priorização](backlog/img/PME-13.png)  


### Épico 3 – Visualização Kanban Simplificada
- [PME-14– Board Kanban (To Do, In Progress, Done)](backlog/img/PME-14.png)
- [PME-15- Fluxo ponta a ponta com filtros](backlog/img/PME-15.png)

### Épico 4 – Roadmap de Maturidade (KMM)
- PME-16 – Roadmap de práticas evolutivas (KMM)
- PME-17 – Comparar maturidade entre times  

### Épico 5 – Alertas Automáticos
- PME-18 – Alertas de bloqueios  
- PME-19 – Alertas de gargalos de fluxo 
- PME-20 – Alertas de WIP acima do limite  

### Épico 6 – Relatórios Executivos
- [PME-21 – Relatórios executivos resumidos]  

### Épico 7 – Previsibilidade
- [PME-22 – Previsões de entrega por histórico]  
- [PME-23 – Previsibilidade de roadmap estratégico]  

### Épico 8 – Integração com OKRs
- PME-24 – Vincular métricas de fluxo a OKRs  

### Épico 9 – Exportação de Relatórios
- PME-25 – Exportar relatórios em PDF/Excel 

---

## 📏 Definições

### ✅ Definition of Ready (DoR)
- História clara (“Como [persona], quero [funcionalidade] para [benefício]”)  
- Critérios de aceite definidos  
- Dependências identificadas  
- Estimativa de esforço pelo time  
- Valor de negócio validado pelo PO  
- UI/UX disponível (quando aplicável)  
- Sem impedimentos conhecidos  
- Métricas de sucesso definidas  

### 🔵 Definition of Done (DoD)
- Código implementado, revisado e integrado  
- Atende 100% dos critérios de aceite  
- Testes automatizados (mín. 80% cobertura)  
- Testes de usabilidade validados UX/QA  
- Telas principais carregam em até 3s  
- Autenticação segura e LGPD/GDPR  
- Usabilidade validada com ≥3 usuários reais  
- Suporte a 5 times / 100 usuários no MVP  
- Deploy em produção realizado  
- Documentação técnica e de usuário atualizada  
- Review com stakeholders realizado  
- Métricas de uso habilitadas (telemetria)  

---

## 🗓 Planejamento da Sprint 1
**Objetivo da Sprint:** disponibilizar integração básica com GitLab e dashboard inicial de métricas.  

**Itens planejados:**  
[Imagem do Backlog Sprint 1 exportado do JIRA](backlog/img/sprint-1-backlog.png)
- [PME-10 – Conexão inicial com GitLab.](backlog/img/PME-10.png)   
- [PME-11 – Atualização em tempo real das issues.](backlog/img/PME-11.png)   
- [PME-12 – Dashboard com métricas principais (lead time, throughput, aging WIP).](backlog/img/PME-12.png)   
- Enablers técnicos: API GitLab, banco de dados inicial, pipeline CI/CD.  


[Imagem do backlog restante para as proximas Sprints.](backlog/img/backlog-restante.png)
---

## 🎨 Protótipo

[Prototipo em PDF - Todas Telas](prototipo-wireframes/prototipo.pdf) 

[Tela de Login](prototipo-wireframes/Login-Wireframe.jpg) 

[Tela Conexao Gitlab](prototipo-wireframes/Conexao-Gitlab-Wireframe.jpg)

[Tela de Dashboard](prototipo-wireframes/Dashboard-Metrica-Wireframe.jpg)

[Tela de Board Simplificado](prototipo-wireframes/Kanban-Board-Simplificado.jpg)

[Tela Board End-to-End](prototipo-wireframes/Board-End-to-End-Wireframe.jpg)

[Tela de Roadmap de Maturidade](prototipo-wireframes/Roadmap-Maturidade-Wireframe.jpg)
[Tela Comparativo Maturidade Times](prototipo-wireframes/Comparativo-de-Maturidade-Wireframe.jpg)
