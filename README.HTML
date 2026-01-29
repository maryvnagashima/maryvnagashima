import { useState, useEffect } from 'react';

export default function App() {
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);
  
  // Projects data based on Marina's information
  const projects = [
    {
      id: 1,
      title: "🤖 Sistema de Qualificação de Leads com IA (WhatsApp)",
      description: "Chatbot que captura, qualifica e distribui leads em tempo real, com conformidade LGPD.",
      details: [
        "Pede consentimento LGPD automático",
        "Usa IA (Llama 3 em Groq) para dar score de intenção (0–100)",
        "Roteia leads: alta intenção → time comercial, média → nutrição, baixa → remarketing"
      ],
      stack: ["n8n", "Meta Cloud API", "Groq (Llama 3)", "Airtable/Sheets", "GA4"],
      impact: [
        "48% de conversão de lead qualificado em venda",
        "94% de opt-in LGPD",
        "Tempo de resposta de dias para minutos",
        "~35% de redução no CPA vs. fluxo manual"
      ]
    },
    {
      id: 2,
      title: "📊 BudgetMind – SaaS de Otimização de Budget de Mídia",
      description: "Plataforma que consolida dados de mídia e usa IA para sugerir como redistribuir investimento entre canais.",
      details: [
        "Conecta Google Ads, Meta Ads, Shopee Ads, GA4 (e outros)",
        "Normaliza métricas (ROAS, CPA, CAC, LTV) em um modelo único",
        "Mostra saturação por canal, campanha e região (País → Estado → Cidade)",
        "Gera alertas inteligentes (críticos, oportunidades, sistema)",
        "Usa Gemini para sugerir redistribuição de budget (com validação humana)"
      ],
      stack: ["React", "TypeScript", "Google Cloud Functions", "BigQuery", "Firestore", "Gemini"],
      impact: [
        "R$500k+/mês de budget gerenciado",
        "ROAS médio ~3,2x",
        "~11,2k conversões/mês consolidadas",
        "92% menos tempo de análise (2h/dia → 10 min)",
        "15–30% de aumento de ROAS em contas com recomendações aplicadas"
      ]
    },
    {
      id: 3,
      title: "📈 Chatbot de Dados com Snowflake Cortex Analyst",
      description: "Agente conversacional que responde perguntas sobre dados de vendas em linguagem natural, sem SQL.",
      details: [
        "Usa Semantic View no Snowflake para mapear tabelas em conceitos de negócio",
        "Recebe perguntas como 'qual o total de vendas brutas por loja?'",
        "Entrega: Query SQL gerada, execução no Snowflake, gráfico + tabela + resposta em texto"
      ],
      stack: ["Snowflake", "Cortex Analyst", "Snowflake Intelligence"],
      impact: [
        "POC funcional em minutos com dados estruturados",
        "Democratiza acesso a dados para times não técnicos, com governança"
      ]
    },
    {
      id: 4,
      title: "🎯 Cases de Marketing & Performance",
      description: "Exemplos de estratégia + resultado:",
      cases: [
        {
          title: "Black Friday 2024",
          description: "Planejamento em 3 fases (pré, pico, pós) + orquestração multicanal.",
          results: ["~-42% CPC vs. média do período", "+67% conversões", "ROAS ~5,2x vs. baseline ~3,8x"]
        },
        {
          title: "Lançamento de Máscara com budget limitado",
          description: "Testes simultâneos em Google, Meta, TikTok; foco em encontrar canal com melhor CAC.",
          results: ["Meta de 1.500 peças em 30 dias superada (1.847 unidades)", "CAC ~R$5,50 no Google", "Storytelling orgânico em TikTok/Instagram + remarketing"]
        },
        {
          title: "Insight de LTV – Shampoo vs Paleta",
          description: "Análise de coortes mostrou que clientes adquiridos via shampoo de reposição têm LTV 3,5x maior que via paleta de maquiagem.",
          results: ["Redistribuição de budget para produtos de alta recorrência", "Redução de CAC médio", "Aumento de LTV e margem anual"]
        }
      ]
    }
  ];

  // Skills organized by categories
  const skillsCategories = [
    {
      title: "IA Generativa & Modelos de Linguagem",
      items: [
        "LLMs: Groq (Llama 3), Gemini, Snowflake Cortex",
        "Orquestração: n8n, Make, Zapier",
        "Agentes autônomos e RAG",
        "Fine-tuning e prompt engineering"
      ]
    },
    {
      title: "Data Engineering & Analytics",
      items: [
        "SQL (BigQuery, Snowflake, Postgres)",
        "Python (automação, ETL, análise)",
        "BigQuery como data warehouse",
        "GA4, Looker Studio, Data Studio",
        "Modelagem de dados, coortes, LTV, CAC payback"
      ]
    },
    {
      title: "Marketing Tech & Automação",
      items: [
        "Mídia paga: Google Ads, Meta Ads, TikTok Ads, Shopee Ads, Amazon Ads",
        "Integração com APIs: Google Ads, Meta, Shopee, GA4",
        "Criação de chatbots (WhatsApp, web)",
        "Automação de fluxos de leads e nutrição"
      ]
    },
    {
      title: "Engenharia & Produto",
      items: [
        "Frontend: React, TypeScript, HTML/CSS",
        "Backend leve: Node.js / Cloud Functions",
        "Git/GitHub, deploy em Netlify, Vercel, Render, GCP",
        "Pensamento de produto: roadmaps, MVP, feedback loops",
        "Governança: KPIs, observabilidade, padrões de qualidade"
      ]
    }
  ];

  // Academic education
  const academicEducation = [
    {
      institution: "Faculdade UniBF",
      degree: "Pós-graduação Lato Sensu - MBA, DATA WAREHOUSE E BUSINESS INTELLIGENCE",
      period: "Jan 2025 - Ago 2026"
    },
    {
      institution: "DataCamp",
      degree: "Postgraduate Degree, Data Engineer de IA Python",
      period: "Ago 2025 - Dez 2026"
    },
    {
      institution: "Universidade Paulista",
      degree: "Análise e Desenvolvimento de Sistemas, Tecnologia da Informação",
      period: "2013 - 2015"
    }
  ];

  // Certifications grouped by category
  const certificationCategories = [
    {
      title: "IA Generativa & Modelos de Linguagem",
      items: [
        "Databricks Academy Accreditation – Generative AI Fundamentals (OpenAI) — Out 2024",
        "DataCamp – AI Engineer for Data Scientists Associate — Jul 2025",
        "Escola Conquer – Inteligência Artificial"
      ]
    },
    {
      title: "Data Warehouse & Arquitetura (Data Engineering)",
      items: [
        "Salesforce – Data Stream Fundamentals Superbadge — Jan 2026 (NOVO)",
        "Databricks – Certified in Lakehouse Architecture — Jan 2026 (NOVO)",
        "FIAP – Business Intelligence — Jun 2024",
        "FIAP – Big Data — Mai 2024",
        "DataCamp – Introduction to SQL — Jan 2025"
      ]
    },
    {
      title: "Mídia Paga com IA",
      items: [
        "Google – High Performance Ads with AI — Set 2024",
        "Google – Shopping Ads with AI Technology — Jan 2025",
        "Amazon – Amazon DSP Certification — Abr 2025"
      ]
    },
    {
      title: "Estratégia & Liderança",
      items: [
        "University of Illinois – Estratégia de Negócios (97.14%) — Fev 2025",
        "Fast MBA – Liderança e Gestão de Pessoas — Jan 2025",
        "Senac – Scrum & Kanban — Jan 2026"
      ]
    },
    {
      title: "Soft Skills & Comunicação",
      items: [
        "LinkedIn Learning (vários cursos) — Jan 2025",
        "PM3 – Storytelling para Negócios — Jan 2024"
      ]
    }
  ];

  // Smooth scrolling for anchor links
  const handleNavClick = (e, targetId) => {
    e.preventDefault();
    const element = document.getElementById(targetId);
    if (element) {
      window.scrollTo({
        top: element.offsetTop - 80,
        behavior: 'smooth'
      });
      if (isMobileMenuOpen) {
        setIsMobileMenuOpen(false);
      }
    }
  };

  // Close mobile menu when clicking outside
  useEffect(() => {
    const handleClickOutside = (event) => {
      if (isMobileMenuOpen && !event.target.closest('#mobile-menu')) {
        setIsMobileMenuOpen(false);
      }
    };

    document.addEventListener('mousedown', handleClickOutside);
    return () => {
      document.removeEventListener('mousedown', handleClickOutside);
    };
  }, [isMobileMenuOpen]);

  return (
    <div className="min-h-screen bg-gray-50 font-sans">
      {/* Header com navegação */}
      <header className="bg-white shadow-sm sticky top-0 z-50">
        <div className="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between items-center py-4">
            <div className="flex items-center">
              <div className="bg-indigo-600 text-white font-bold text-xl w-10 h-10 rounded-full flex items-center justify-center mr-3">
                MN
              </div>
              <h1 className="text-xl font-bold text-gray-900">Marina Nagashima</h1>
            </div>
            
            {/* Desktop Navigation */}
            <nav className="hidden md:block">
              <ul className="flex space-x-8">
                <li><a href="#sobre" onClick={(e) => handleNavClick(e, 'sobre')} className="text-gray-700 hover:text-indigo-600 font-medium transition-colors">Sobre</a></li>
                <li><a href="#habilidades" onClick={(e) => handleNavClick(e, 'habilidades')} className="text-gray-700 hover:text-indigo-600 font-medium transition-colors">Habilidades</a></li>
                <li><a href="#projetos" onClick={(e) => handleNavClick(e, 'projetos')} className="text-gray-700 hover:text-indigo-600 font-medium transition-colors">Projetos</a></li>
                <li><a href="#formacao" onClick={(e) => handleNavClick(e, 'formacao')} className="text-gray-700 hover:text-indigo-600 font-medium transition-colors">Formação</a></li>
                <li><a href="#contato" onClick={(e) => handleNavClick(e, 'contato')} className="text-gray-700 hover:text-indigo-600 font-medium transition-colors">Contato</a></li>
              </ul>
            </nav>
            
            {/* Mobile menu button */}
            <button 
              onClick={() => setIsMobileMenuOpen(!isMobileMenuOpen)}
              className="md:hidden p-2 rounded-md text-gray-700 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-indigo-500"
              aria-expanded={isMobileMenuOpen}
              aria-label="Toggle menu"
            >
              {isMobileMenuOpen ? (
                <span className="text-2xl">×</span>
              ) : (
                <span className="text-2xl">☰</span>
              )}
            </button>
          </div>
          
          {/* Mobile Navigation */}
          {isMobileMenuOpen && (
            <div 
              id="mobile-menu"
              className="md:hidden pb-4 border-t border-gray-200"
            >
              <ul className="flex flex-col space-y-3 mt-4">
                <li><a href="#sobre" onClick={(e) => handleNavClick(e, 'sobre')} className="block py-2 text-gray-700 hover:text-indigo-600 font-medium transition-colors">Sobre</a></li>
                <li><a href="#habilidades" onClick={(e) => handleNavClick(e, 'habilidades')} className="block py-2 text-gray-700 hover:text-indigo-600 font-medium transition-colors">Habilidades</a></li>
                <li><a href="#projetos" onClick={(e) => handleNavClick(e, 'projetos')} className="block py-2 text-gray-700 hover:text-indigo-600 font-medium transition-colors">Projetos</a></li>
                <li><a href="#formacao" onClick={(e) => handleNavClick(e, 'formacao')} className="block py-2 text-gray-700 hover:text-indigo-600 font-medium transition-colors">Formação</a></li>
                <li><a href="#contato" onClick={(e) => handleNavClick(e, 'contato')} className="block py-2 text-gray-700 hover:text-indigo-600 font-medium transition-colors">Contato</a></li>
              </ul>
            </div>
          )}
        </div>
      </header>

      {/* Hero Section - Estilo README */}
      <section className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div className="bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
          <div className="bg-gray-800 text-green-400 font-mono text-sm p-4 overflow-x-auto">
            <div className="flex items-center mb-2">
              <span className="bg-green-500 rounded-full h-3 w-3 inline-block mr-2"></span>
              <span className="bg-yellow-400 rounded-full h-3 w-3 inline-block mr-2"></span>
              <span className="bg-red-500 rounded-full h-3 w-3 inline-block mr-4"></span>
              <span>marina@portfolio:~$</span>
            </div>
            <div className="space-y-1">
              <p><span className="text-blue-400">whoami</span></p>
              <p className="text-green-400">👋 Oi, eu sou a Marina Nagashima</p>
              <p className="text-cyan-300 mt-2">AI Tools · GenAI · Data & Automation · Marketing Tech</p>
              <p className="mt-2">marina@portfolio:~$ <span className="text-blue-400">focus</span></p>
              <p className="text-green-400">Criando agentes, automações e data apps com IA e dados</p>
              <p className="text-green-400">para resolver problemas de negócio em aquisição, leads, budget e analytics.</p>
              <p className="mt-2">marina@portfolio:~$ <span className="text-blue-400">stack</span></p>
              <p className="text-green-400">✓ LLMs: Groq, Gemini, Snowflake Cortex</p>
              <p className="text-green-400">✓ Orquestração: n8n, Make, Zapier</p>
              <p className="text-green-400">✓ Dados: GA4, BigQuery, Snowflake, Looker</p>
              <p className="text-green-400">✓ Engenharia: React, TypeScript, Python, SQL</p>
              <p className="mt-2">marina@portfolio:~$ <span className="text-blue-400">cat</span> &gt; README.md</p>
            </div>
          </div>
          
          <div className="p-6 md:p-8 bg-[#f8f9fa] border-t border-gray-200">
            <div className="prose prose-indigo max-w-none">
              <h1 className="text-3xl font-bold mb-4 flex items-center">
                <span className="mr-3">✨</span> Sobre Mim
              </h1>
              
              <p className="text-lg mb-6">
                Trabalho criando <strong>agentes, automações e data apps</strong> que usam IA e dados para resolver problemas de negócio – especialmente em aquisição, qualificação de leads, orçamento de mídia e analytics.
              </p>
              
              <div className="flex flex-wrap gap-3 mb-8">
                <span className="bg-indigo-100 text-indigo-800 text-xs font-medium px-3 py-1 rounded-full">AI Tools</span>
                <span className="bg-purple-100 text-purple-800 text-xs font-medium px-3 py-1 rounded-full">GenAI</span>
                <span className="bg-blue-100 text-blue-800 text-xs font-medium px-3 py-1 rounded-full">Data & Automation</span>
                <span className="bg-cyan-100 text-cyan-800 text-xs font-medium px-3 py-1 rounded-full">Marketing Tech</span>
                <span className="bg-teal-100 text-teal-800 text-xs font-medium px-3 py-1 rounded-full">LLMs</span>
                <span className="bg-emerald-100 text-emerald-800 text-xs font-medium px-3 py-1 rounded-full">Data Engineering</span>
              </div>
              
              <div className="grid grid-cols-1 md:grid-cols-3 gap-4 mb-8">
                <div>
                  <p className="font-bold">🧠 Foco</p>
                  <p>Agentes, Automações, Data Apps</p>
                </div>
                <div>
                  <p className="font-bold">⚙️ Stack</p>
                  <p>LLMs, Pipelines, Governança</p>
                </div>
                <div>
                  <p className="font-bold">🎯 Resultado</p>
                  <p>Sistemas robustos, seguros e mensuráveis</p>
                </div>
              </div>
              
              <div className="flex flex-col sm:flex-row gap-3">
                <a 
                  href="#projetos" 
                  onClick={(e) => handleNavClick(e, 'projetos')}
                  className="inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 transition-colors"
                >
                  Ver Projetos
                </a>
                <a 
                  href="#contato" 
                  onClick={(e) => handleNavClick(e, 'contato')}
                  className="inline-flex items-center justify-center px-5 py-3 border border-gray-300 text-base font-medium rounded-md text-gray-700 bg-white hover:bg-gray-50 transition-colors"
                >
                  Entrar em Contato
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Sobre Mim Section */}
      <section id="sobre" className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div className="bg-white rounded-lg shadow-md p-6 md:p-8 border border-gray-200">
          <h2 className="text-2xl font-bold mb-6 flex items-center">
            <span className="mr-3 text-indigo-600">✨</span> Minha Abordagem
          </h2>
          <div className="prose prose-indigo max-w-none space-y-6">
            <p>
              Meu foco é combinar:
            </p>
            
            <ul className="list-disc list-inside space-y-2 ml-4">
              <li><strong>LLMs e orquestração</strong> (n8n, Groq, Gemini, Snowflake Cortex)</li>
              <li><strong>Pipelines de dados</strong> (GA4, BigQuery, Snowflake, Looker)</li>
              <li><strong>Boas práticas de produto e governança</strong> (KPIs, observabilidade, padrões)</li>
            </ul>
            
            <p>
              para entregar sistemas que são <strong>robustos, seguros e mensuráveis</strong>.
            </p>
            
            <div className="bg-indigo-50 rounded-lg p-5 border border-indigo-100 mt-4">
              <p className="font-medium italic">
                "Acredito que a integração entre inteligência artificial, engenharia de dados e práticas de produto é a chave para criar soluções escaláveis e de alto impacto no mundo do marketing e negócios."
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Habilidades Section */}
      <section id="habilidades" className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div className="bg-white rounded-lg shadow-md p-6 md:p-8 border border-gray-200">
          <h2 className="text-2xl font-bold mb-8 flex items-center">
            <span className="mr-3 text-indigo-600">🛠️</span> Stack & Habilidades
          </h2>
          
          <div className="space-y-8">
            {skillsCategories.map((category, index) => (
              <div key={index}>
                <h3 className="text-xl font-bold mb-4 flex items-center text-indigo-700">
                  <span className="mr-2">●</span> {category.title}
                </h3>
                <ul className="space-y-2 pl-5 border-l-2 border-indigo-100 ml-3">
                  {category.items.map((item, itemIndex) => (
                    <li key={itemIndex} className="text-gray-700">{item}</li>
                  ))}
                </ul>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Projetos Section */}
      <section id="projetos" className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div className="bg-white rounded-lg shadow-md p-6 md:p-8 border border-gray-200">
          <h2 className="text-2xl font-bold mb-8 flex items-center">
            <span className="mr-3 text-indigo-600">🚀</span> Projetos em Destaque
          </h2>
          
          <div className="space-y-10">
            {projects.map((project) => (
              <div key={project.id} className="border border-gray-200 rounded-lg p-6 hover:shadow-lg transition-shadow">
                <h3 className="text-xl font-bold mb-3 flex items-center">
                  {project.title}
                </h3>
                
                <p className="text-gray-700 mb-4">{project.description}</p>
                
                {project.details && (
                  <div className="mb-5">
                    <h4 className="font-bold mb-2 text-indigo-700">Funcionalidades:</h4>
                    <ul className="list-disc list-inside space-y-1 text-gray-700">
                      {project.details.map((detail, index) => (
                        <li key={index}>{detail}</li>
                      ))}
                    </ul>
                  </div>
                )}
                
                {project.stack && (
                  <div className="mb-5">
                    <h4 className="font-bold mb-2 text-indigo-700">Stack:</h4>
                    <div className="flex flex-wrap gap-2">
                      {project.stack.map((tech, index) => (
                        <span 
                          key={index} 
                          className="bg-indigo-50 text-indigo-700 text-xs font-medium px-2.5 py-0.5 rounded"
                        >
                          {tech}
                        </span>
                      ))}
                    </div>
                  </div>
                )}
                
                {project.impact && (
                  <div className="bg-indigo-50 rounded-lg p-4 border border-indigo-100">
                    <h4 className="font-bold mb-2 text-indigo-700">Impacto:</h4>
                    <ul className="list-disc list-inside space-y-1 text-gray-700">
                      {project.impact.map((result, index) => (
                        <li key={index} className="font-medium">{result}</li>
                      ))}
                    </ul>
                  </div>
                )}
                
                {project.cases && (
                  <div className="space-y-4 mt-4">
                    {project.cases.map((caso, caseIndex) => (
                      <div key={caseIndex} className="border border-gray-200 rounded-lg p-4">
                        <h4 className="font-bold text-lg mb-2 text-indigo-700">{caso.title}</h4>
                        <p className="text-gray-700 mb-2">{caso.description}</p>
                        <div className="bg-gray-50 rounded p-3">
                          <h5 className="font-bold mb-1">Resultados:</h5>
                          <ul className="list-disc list-inside space-y-1">
                            {caso.results.map((result, resultIndex) => (
                              <li key={resultIndex} className="font-medium">{result}</li>
                            ))}
                          </ul>
                        </div>
                      </div>
                    ))}
                  </div>
                )}
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Formação Section */}
      <section id="formacao" className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div className="bg-white rounded-lg shadow-md p-6 md:p-8 border border-gray-200">
          <h2 className="text-2xl font-bold mb-8 flex items-center">
            <span className="mr-3 text-indigo-600">🎓</span> Formação & Certificações
          </h2>
          
          <div className="space-y-10">
            {/* Academic Education */}
            <div>
              <h3 className="text-xl font-bold mb-4 text-indigo-700">Formação Acadêmica</h3>
              <div className="space-y-5">
                {academicEducation.map((item, index) => (
                  <div key={index} className="border-l-4 border-indigo-200 pl-4 py-2">
                    <h4 className="text-lg font-bold text-gray-900">{item.institution}</h4>
                    <p className="font-medium text-gray-800">{item.degree}</p>
                    <p className="text-indigo-600 font-medium">{item.period}</p>
                  </div>
                ))}
              </div>
            </div>
            
            {/* Certifications */}
            <div>
              <h3 className="text-xl font-bold mb-4 text-indigo-700">Certificações</h3>
              <div className="space-y-6">
                {certificationCategories.map((category, index) => (
                  <div key={index}>
                    <h4 className="font-bold text-lg mb-3 text-indigo-700">{category.title}</h4>
                    <ul className="list-disc list-inside space-y-2 text-gray-700 border-l-2 border-indigo-100 pl-4 ml-2">
                      {category.items.map((item, itemIndex) => (
                        <li key={itemIndex}>{item}</li>
                      ))}
                    </ul>
                  </div>
                ))}
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Contato Section */}
      <section id="contato" className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div className="bg-white rounded-lg shadow-md p-6 md:p-8 border border-gray-200">
          <h2 className="text-2xl font-bold mb-6 flex items-center">
            <span className="mr-3 text-indigo-600">📬</span> Onde me encontrar
          </h2>
          
          <div className="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div>
              <p className="mb-6 text-lg">
                Se quiser trocar ideia sobre <strong>IA, dados e automação no marketing</strong>, adoro conversar sobre como transformar processos manuais em sistemas inteligentes, automatizados e sustentáveis. 🚀
              </p>
              
              <div className="space-y-5">
                <div className="flex items-start">
                  <span className="text-indigo-600 mr-3 mt-1 text-xl">🔗</span>
                  <div>
                    <p className="font-bold">LinkedIn</p>
                    <a 
                      href="https://linkedin.com/in/marinanagashina" 
                      target="_blank" 
                      rel="noopener noreferrer"
                      className="text-indigo-600 hover:underline break-words"
                    >
                      linkedin.com/in/marinanagashina
                    </a>
                  </div>
                </div>
                
                <div className="flex items-start">
                  <span className="text-indigo-600 mr-3 mt-1 text-xl">💻</span>
                  <div>
                    <p className="font-bold">GitHub</p>
                    <a 
                      href="https://github.com/maryvnagashima" 
                      target="_blank" 
                      rel="noopener noreferrer"
                      className="text-indigo-600 hover:underline break-words"
                    >
                      github.com/maryvnagashima
                    </a>
                  </div>
                </div>
                
                <div className="bg-indigo-50 rounded-lg p-4 border border-indigo-100 mt-4">
                  <p className="font-bold mb-2">Agendamento de conversa:</p>
                  <p>Disponível para consultorias e parcerias estratégicas. Entre em contato pelo LinkedIn para agendar uma conversa.</p>
                </div>
              </div>
            </div>
            
            <div className="bg-gray-50 rounded-lg p-6">
              <h3 className="text-lg font-bold mb-4 text-indigo-700">Mande uma Mensagem</h3>
              <form className="space-y-4">
                <div>
                  <label htmlFor="name" className="block text-sm font-medium text-gray-700 mb-1">Nome</label>
                  <input
                    type="text"
                    id="name"
                    className="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500"
                    placeholder="Seu nome"
                  />
                </div>
                <div>
                  <label htmlFor="email" className="block text-sm font-medium text-gray-700 mb-1">Email</label>
                  <input
                    type="email"
                    id="email"
                    className="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500"
                    placeholder="seu@email.com"
                  />
                </div>
                <div>
                  <label htmlFor="message" className="block text-sm font-medium text-gray-700 mb-1">Mensagem</label>
                  <textarea
                    id="message"
                    rows="4"
                    className="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500"
                    placeholder="Sua mensagem sobre IA, dados ou automação..."
                  ></textarea>
                </div>
                <button
                  type="submit"
                  className="w-full bg-indigo-600 text-white font-medium py-2 px-4 rounded-md hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition-colors"
                >
                  Enviar Mensagem
                </button>
              </form>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-12">
        <div className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <div className="flex justify-center space-x-8 mb-6">
            <a href="https://linkedin.com/in/marinanagashina" target="_blank" rel="noopener noreferrer" className="text-gray-400 hover:text-white transition-colors text-2xl">🔗</a>
            <a href="https://github.com/maryvnagashima" target="_blank" rel="noopener noreferrer" className="text-gray-400 hover:text-white transition-colors text-2xl">💻</a>
            <a href="mailto:contato@marinanagashima.com" className="text-gray-400 hover:text-white transition-colors text-2xl">✉️</a>
          </div>
          <p className="text-gray-400 mb-4">
            &copy; {new Date().getFullYear()} Marina Nagashima. Todos os direitos reservados.
          </p>
          <p className="text-gray-500 text-sm">
            Criando agentes, automações e data apps com IA e dados
          </p>
        </div>
      </footer>
    </div>
  );
}
