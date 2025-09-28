# 📘 Evoflow
Esse trabalho faz parte da Sprint de Agilidade 
## 📊 Cenário de Negócio (Hipotético)
O EvoFlow nasce em uma empresa pública de tecnologia que apoia diferentes órgãos do governo no desenvolvimento de soluções digitais.  

**Problema atual:** os times usam o GitLab, mas de formas diferentes, com boards heterogêneos e sem métricas comparáveis. Isso gera baixa previsibilidade, dificuldade de priorização e sobrecarga em Product Owners.  

**Oportunidade:** fornecer uma plataforma integrada ao GitLab que transforma os dados de issues e merge requests em insights de fluxo e maturidade KMM, ajudando times a evoluírem de forma contínua, desde iniciantes (nível 1) até avançados (nível 6).  

---

## 👥 Mapeamento de Stakeholders
- **Alta Gestão / Diretoria de TI:** precisa de relatórios executivos e visão consolidada de performance entre equipes.  
- **Gestores Intermediários (Ex.: Eduardo):** tomam decisões de alocação, negociam prazos e precisam de informações rápidas.
- **Product Owners (Ex.: Carla):** acumulam funções de backlog, priorização e acompanhamento do time → precisam de métricas claras.  
- **Equipe de Desenvolvimento (Ex.: Rogério):** busca clareza no fluxo, redução de multitarefa e feedback sobre produtividade.  
- **Agile Coaches / Consultores externos:** (quando existem) apoiam evolução em práticas de fluxo e maturidade organizacional.  

---

## 👩‍💻 Time Scrum (enxuto para o MVP)
- **PO:** define backlog, alinha stakeholders, garante valor de negócio.  
- **Scrum Master (opcional, pode ser acumulado pelo PO):** facilita cerimônias e remoção de impedimentos.  
- **2 Devs Fullstack (incluindo Rogério):** responsáveis por integração GitLab, board Kanban e dashboard.  
- **1 UX Designer:** cria wireframes e garante usabilidade.  

👉 **Time total:** 3 a 4 pessoas, entrega enxuta em 3–4 semanas por MVP.  


## 🎯 Board do Board do  - Lean Inception
👉 [Link do Miro](https://miro.com/app/board/uXjVJCEiDYY=/?share_link_id=946748718869)
---

## 🎯 MVP Canvas
**MVP 1 – Visibilidade de Fluxo**  

**Problema:** falta de visibilidade ponta a ponta e métricas confiáveis.  

**Solução:** integração com GitLab, board Kanban simplificado, limite de WIP e métricas básicas.  

**Personas Impactadas:** devs (operacional), PO (tático), gestor intermediário (estratégico).  

**Hipóteses a Validar:**  
- Times adotam o board simplificado para alinhar fluxo.  
- POs usam métricas básicas em reuniões semanais.  
- Gestores consultam o dashboard em até 2 min para tomar decisão.  

**Métricas de Sucesso:** nº de equipes usando, tempo médio de login → board, acessos semanais ao dashboard.  

---

## 📌 Backlog Inicial *Nao esquecer de atualizar ids das historias antes da entrega final do trabalho

### Épico 1 – Integração com GitLab
- [História S1 – Conectar repositório GitLab](imagens/S1.png)  
- [História S2 – Issues atualizadas em tempo real](imagens/S2.png)  

### Épico 2 – Dashboard de Métricas Básicas
- [História S3 – Visualizar métricas (lead time, throughput, aging WIP)](imagens/S3.png)  
- [História S4 – Acompanhar aging WIP para priorização](imagens/S4.png)  

### Épico 3 – Visualização Kanban Simplificada
- [História S5 – Board Kanban (To Do, In Progress, Done)](imagens/S5.png)  
- [História S6 – Fluxo ponta a ponta com filtros](imagens/S6.png)  

### Épico 4 – Roadmap de Maturidade (KMM)
- [História S7 – Roadmap de práticas evolutivas (KMM)](imagens/S7.png)  
- [História S8 – Comparar maturidade entre times](imagens/S8.png)  

### Épico 5 – Alertas Automáticos
- [História S9 – Alertas de bloqueios](imagens/S9.png)  
- [História S10 – Alertas de gargalos de fluxo](imagens/S10.png)  
- [História S11 – Alertas de WIP acima do limite](imagens/S11.png)  

### Épico 6 – Relatórios Executivos
- [História S12 – Relatórios executivos resumidos](imagens/S12.png)  

### Épico 7 – Previsibilidade
- [História S13 – Previsões de entrega por histórico](imagens/S13.png)  
- [História S14 – Previsibilidade de roadmap estratégico](imagens/S14.png)  

### Épico 8 – Integração com OKRs
- [História S15 – Vincular métricas de fluxo a OKRs](imagens/S15.png)  

### Épico 9 – Exportação de Relatórios
- [História S16 – Exportar relatórios em PDF/Excel](imagens/S16.png)  

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
- História S1 – Conexão inicial com GitLab.  
- História S2 – Atualização em tempo real das issues.  
- História S3 – Dashboard com métricas principais (lead time, throughput, aging WIP).  
- Enablers técnicos: API GitLab, banco de dados inicial, pipeline CI/CD.  

---

## 🎨 Protótipo
👉 [Link do Figma](https://www.figma.com/)*Nao esquecer de atualizar o link antes da entrega final do trabalho
