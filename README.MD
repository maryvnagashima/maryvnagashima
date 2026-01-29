<div align="center">
  <img src="https://github.com/maryvnagashima.png" width="150" style="border-radius:50%"/>
  
  <h1>Marina Nagashima</h1>
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=AI%2FML+Engineer+%7C+Marketing+%E2%86%92+Tech;Building+AI+Agents+%26+Data+Pipelines;2+Years+Shipping+LLMs+to+Production" alt="Typing SVG" />
  
  <p><b>Transformando processos manuais em sistemas inteligentes com IA Generativa, automação e engenharia de dados</b></p>
  
  <br/>
  
  <!-- BADGES PRINCIPAIS -->
  <div>
    <img src="https://img.shields.io/badge/LLMs-Groq%20%7C%20Gemini%20%7C%20Cortex-6366F1?style=flat-square&logo=openai&logoColor=white" alt="LLMs"/>
    <img src="https://img.shields.io/badge/Cloud-GCP%20%7C%20AWS%20%7C%20Azure-0EA5E9?style=flat-square&logo=googlecloud&logoColor=white" alt="Cloud"/>
    <img src="https://img.shields.io/badge/Data-BigQuery%20%7C%20Snowflake%20%7C%20Databricks-FF6B35?style=flat-square&logo=databricks&logoColor=white" alt="Data"/>
    <img src="https://img.shields.io/badge/Stack-Python%20%7C%20TypeScript%20%7C%20React-0D9488?style=flat-square&logo=python&logoColor=white" alt="Stack"/>
  </div>
  
  <br/>
  
  <!-- LINKS -->
  <a href="https://linkedin.com/in/marinanagashina" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:marina_vborges@hotmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0VVe_zVPlqTkd9FqHPKjLr5YRqMhqH65JqTmMqOX4XkYj8Mf6uPjhJ9WjNQfnKHW0T9KY8kLxz" target="_blank">
    <img src="https://img.shields.io/badge/Schedule_Meeting-4285F4?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Calendar"/>
  </a>
  
</div>

---

## 👋 Sobre Mim

**AI/ML Engineer** em transição estruturada de **Marketing Digital → Engenharia de IA**, com **2 anos** entregando soluções de IA Generativa em produção que geram impacto mensurável de negócio.
```python
class MarinaNagashima:
    def __init__(self):
        self.role = "AI/ML Engineer"
        self.background = "10+ anos Performance Marketing → Data & AI"
        self.education = ["MBA Big Data Analytics", "Data Engineer AI (DataCamp)"]
        self.certifications = ["AWS Cloud Practitioner", "Databricks GenAI", "GA4"]
        
    def skills(self):
        return {
            "ai_ml": ["LLMs (Groq, Gemini, Cortex)", "Prompt Engineering", "RAG"],
            "data": ["BigQuery", "Snowflake", "Databricks", "SQL", "ETL Pipelines"],
            "cloud": ["GCP (2 anos)", "AWS (1 ano)", "Azure Databricks (1 ano)"],
            "dev": ["Python", "TypeScript", "React", "n8n", "Git/GitHub"],
            "focus": ["MLOps", "Agent Orchestration", "Data Apps", "LGPD Compliance"]
        }
    
    def current_projects(self):
        return [
            "🤖 Lead Qualification AI (48% conversion, 50k+ interactions/month)",
            "📊 BudgetMind SaaS (R$500k+ managed, 3.2x ROAS)",
            "💬 Snowflake Cortex Chatbot (SQL-free natural language queries)"
        ]
```

---

## 🚀 Projetos em Produção

### 🤖 Sistema de Qualificação de Leads com IA
**Chatbot inteligente via WhatsApp que qualifica leads em tempo real com conformidade LGPD**

<div align="center">

| Stack | Resultados |
|:-----:|:----------:|
| ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-000000?logo=ai&logoColor=white) ![Meta](https://img.shields.io/badge/Meta_API-0668E1?logo=meta&logoColor=white) ![Airtable](https://img.shields.io/badge/Airtable-18BFFF?logo=airtable&logoColor=white) | **48%** taxa de conversão<br/>**94%** opt-in LGPD<br/>**5 min** tempo de resposta<br/>**50k+** interações/mês |

</div>

**Destaques Técnicos:**
- ✅ Orquestração n8n (Render.com serverless)
- ✅ Groq/Llama 3 para classificação em tempo real
- ✅ Retry logic com exponential backoff
- ✅ Conformidade total LGPD (consentimento explícito)

<details>
<summary>📐 Ver Arquitetura</summary>
```mermaid
graph LR
    A[Mídia Paga] --> B[Landing Page]
    B --> C[WhatsApp Meta API]
    C --> D[n8n Workflow]
    D --> E[Groq/Llama 3]
    E --> F{Score IA}
    F -->|Alta| G[CRM - Imediato]
    F -->|Média| H[Nutrição]
    F -->|Baixa| I[Remarketing]
```
</details>

[📂 Ver Documentação](./projects/lead-qualification-ai/)

---

### 📊 BudgetMind - Plataforma SaaS de Otimização de Budget
**Sistema que usa Gemini AI para sugerir redistribuição de investimento em mídia paga**

<div align="center">

| Stack | Resultados |
|:-----:|:----------:|
| ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TS-3178C6?logo=typescript&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?logo=googlecloud&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=google&logoColor=white) | **R$500k+**/mês gerenciado<br/>**3.2x** ROAS médio<br/>**2h → 10min** análise<br/>**+15-30%** ROAS com IA |

</div>

**Destaques Técnicos:**
- ✅ React + TypeScript (type-safe, componentizado)
- ✅ Google Cloud Functions (serverless, auto-scaling)
- ✅ BigQuery para consolidação multicanal (Google, Meta, TikTok, Shopee)
- ✅ Gemini AI para recomendações preditivas
- ✅ Análise geográfica granular (País → Estado → Cidade)

[📂 Ver Documentação](./projects/budgetmind/)

---

### 💬 Chatbot de Dados com Snowflake Cortex
**Agente conversacional que responde perguntas sobre dados em linguagem natural**

<div align="center">

| Stack | Resultados |
|:-----:|:----------:|
| ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white) ![Cortex](https://img.shields.io/badge/Cortex_AI-29B5E8?logo=snowflake&logoColor=white) | **POC em minutos**<br/>**Zero SQL** necessário<br/>Democratiza dados |

</div>

**Caso de Uso:** Executivos fazem perguntas como *"Qual o ROAS do Google Ads em SP no último trimestre?"* e recebem respostas instantâneas sem conhecer SQL.

[📂 Ver Documentação](./projects/snowflake-cortex-chatbot/)

---

## 🏆 Certificações

### 🤖 IA & Machine Learning
![Databricks GenAI](https://img.shields.io/badge/Databricks_Generative_AI-FF6B35?logo=databricks&logoColor=white)
![DataCamp AI](https://img.shields.io/badge/DataCamp_AI_Engineer-20B26C?logo=datacamp&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_Cloud_Practitioner-FF9900?logo=amazonaws&logoColor=white)

### 📊 Data Engineering
![Databricks Lakehouse](https://img.shields.io/badge/Databricks_Lakehouse-FF6B35?logo=databricks&logoColor=white)
![Salesforce Data](https://img.shields.io/badge/Salesforce_Data_Stream-00A1E0?logo=salesforce&logoColor=white)
![SQL](https://img.shields.io/badge/DataCamp_SQL-20B26C?logo=datacamp&logoColor=white)

### ☁️ Cloud & Analytics
![GA4](https://img.shields.io/badge/Google_Analytics_4-E37400?logo=googleanalytics&logoColor=white)
![Google Ads](https://img.shields.io/badge/Google_Ads_Certified-4285F4?logo=googleads&logoColor=white)

**→ [Ver todas as certificações](./certifications/)**

---

## 💻 Stack Técnico

### **Linguagens & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### **IA & LLMs**
![Groq](https://img.shields.io/badge/Groq-000000?style=for-the-badge&logo=ai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![Cortex](https://img.shields.io/badge/Snowflake_Cortex-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)

### **Data & Analytics**
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlecloud&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)
![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white)

### **Cloud & DevOps**
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### **Orquestração & Automação**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=maryvnagashima&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=maryvnagashima&theme=tokyonight&hide_border=true" width="49%"/>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=maryvnagashima&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="49%"/>
</div>

---

## 📚 Formação Acadêmica

| 🎓 Instituição | 📖 Curso | 📅 Período |
|:--------------|:---------|:-----------|
| **Faculdade UniBF** | MBA em Data Warehouse e Business Intelligence | Jan/2025 – Ago/2026 |
| **DataCamp** | Postgraduate: Data Engineer de IA (Python) | Ago/2025 – Dez/2026 |
| **Universidade Paulista** | Análise e Desenvolvimento de Sistemas | 2013 – 2015 |

---

## 🎯 O Que Me Diferencia
```diff
+ 2 anos entregando IA em PRODUÇÃO (não só POCs)
+ Visão de negócio (10+ anos): traduzo requisitos em soluções técnicas viáveis
+ Projetos com métricas reais: 48% conversão, R$500k gerenciado, 50k+ interações/mês
+ Conformidade LGPD desde o design (não afterthought)
+ Stack moderno: LLMs, Cloud, MLOps, Data Engineering
```

---

## 📬 Vamos Conversar?

<div align="center">
  
  **Interessado em:**
  - 🤝 Consultorias em IA Generativa & Automação
  - 💼 Oportunidades full-time em AI/ML Engineering
  - 🎓 Parcerias em projetos de dados & IA para marketing
  
  <br/>
  
  <a href="https://linkedin.com/in/marinanagashina">
    <img src="https://img.shields.io/badge/Conectar_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:marina_vborges@hotmail.com">
    <img src="https://img.shields.io/badge/Enviar_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0VVe_zVPlqTkd9FqHPKjLr5YRqMhqH65JqTmMqOX4XkYj8Mf6uPjhJ9WjNQfnKHW0T9KY8kLxz">
    <img src="https://img.shields.io/badge/Agendar_Reuni%C3%A3o-4285F4?style=for-the-badge&logo=googlecalendar&logoColor=white" />
  </a>
  
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=maryvnagashima&color=6366f1&style=flat-square" alt="Profile views"/>
  <br/><br/>
  <sub>💜 Feito com IA Generativa • Atualizado Janeiro 2026</sub>
</div>
