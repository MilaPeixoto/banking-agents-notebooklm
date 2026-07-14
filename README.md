# banking-agents-notebooklm
Este caderno temático foi desenvolvido utilizando o Google NotebookLM como ferramenta de aprendizagem ativa, reunindo uma curadoria de fontes especializadas para estudar os fundamentos, a arquitetura e as aplicações dos agentes de IA no contexto bancário. Projeto desenvolvido como parte do Bootcamp Bradesco – GenAI, Dados & Cyber, promovido pela DIO.


## Caderno Temático: Agentes de IA no Setor Bancário
**Acesse o caderno:** [Acessar Livro](https://notebooklm.google.com/notebook/ad18b35d-b606-42cc-8d3b-5582761f4910)

## Contexto
A evolução da Inteligência Artificial Generativa deu origem a uma nova categoria de sistemas inteligentes: os **Agentes de IA (AI Agents)**. Diferentemente dos chatbots tradicionais, esses agentes são capazes de interpretar objetivos, planejar ações, utilizar ferramentas externas, acessar bases de conhecimento e executar tarefas de forma autônoma.

No setor bancário, essa tecnologia vem transformando processos de atendimento, análise de crédito, prevenção a fraudes, automação operacional e apoio à tomada de decisão, tornando-se um dos principais pilares da transformação digital das instituições financeiras. 

Este caderno temático foi desenvolvido utilizando o Google NotebookLM como ferramenta de aprendizagem ativa, reunindo uma curadoria de fontes especializadas para estudar os fundamentos, a arquitetura e as aplicações dos agentes de IA no contexto bancário.

## Objetivo Geral
Compreender como agentes de Inteligência Artificial são projetados, implementados e aplicados no setor bancário, desde seus fundamentos técnicos até casos reais de uso em atendimento ao cliente, automação de processos, análise de riscos e apoio à tomada de decisão.

## Objetivos Específicos
- Compreender o conceito de Agentes de IA e sua evolução em relação aos chatbots tradicionais, com foco no setor bancário.
- Estudar os componentes fundamentais de um agente inteligente (LLM, planejamento, memória e ferramentas).
- Entender como agentes utilizam ferramentas externas para executar tarefas.
- Analisar aplicações práticas de agentes no setor financeiro.
- Investigar desafios relacionados à segurança, privacidade, ética e governança de IA.
- Desenvolver uma base de conhecimento reutilizável para futuras pesquisas sobre IA Generativa aplicada ao setor bancário.

---

## Curadoria de Fontes
Para contemplar o tema, com o máximo de fontes permitidas (5 fontes), de forma mais completa possível, elas foram selecionadas para construir uma trilha de aprendizagem progressiva, dividida em 2 blocos. 

O 1° bloco reúne materiais voltados aos fundamentos e à arquitetura dos agentes de IA, enquanto o 2° apresenta estudos de caso e aplicações práticas no setor bancário. Essa organização permite compreender tanto os aspectos técnicos da tecnologia quanto seu impacto na transformação digital das instituições financeiras.

### Bloco 1 — Fundamentos dos Agentes de IA
**Objetivo:** Construir uma base sólida sobre os conceitos, arquitetura e desenvolvimento de agentes de Inteligência Artificial, compreendendo seus componentes, funcionamento e implementação prática.

1. **Hands-On Large Language Models**
   - **Tipo:** Livro (PDF) 
   - **Link:** [Acessar Livro](https://drive.google.com/file/d/1ROBDsSJUqKrEu4sul9io7JRrrjHyuNRu/view?usp=sharing)
   - **Descrição:** Apresenta os fundamentos dos LLMs, embeddings, RAG e IA Generativa, fornecendo a base técnica para compreender como agentes de IA são construídos.

2. **LangChain – Agents**
   - **Tipo:** Documentação Oficial 
   - **Link:** [Acessar Documentação](https://docs.langchain.com/oss/python/langchain/agents)
   - **Descrição:** Explica a arquitetura e o funcionamento de agentes de IA, incluindo planejamento, uso de ferramentas e execução de tarefas.

3. **OpenAI's Agents SDK | Tutorial Completo**
   - **Tipo:** Vídeo (Youtube) 
   - **Link:** [Assistir Vídeo](https://www.youtube.com/watch?v=35nxORG1mtg)
   - **Descrição:** Demonstra, na prática, como criar agentes utilizando o OpenAI Agents SDK, conectando teoria e implementação.

### Bloco 2 — Aplicações dos Agentes de IA no Setor Bancário
**Objetivo:** Explorar como agentes de IA estão transformando processos, atendimento e tomada de decisão nas instituições financeiras.

4. **IBM – Generative AI in Banking**
   - **Tipo:** Artigo Técnico 
   - **Link:** [Acessar Artigo](https://www.ibm.com/think/topics/generative-ai-banking)
   - **Descrição:** Apresenta aplicações reais da IA Generativa no setor bancário, com foco em automação, atendimento, análise de risco e prevenção a fraudes.

5. **Transforming Banking with AI at Oracle AI World 2025**
   - **Tipo:** Vídeo (Youtube) 
   - **Link:** [Assistir Vídeo](https://www.youtube.com/watch?v=8-AaqvmM_-w)
   - **Descrição:** Mostra casos e tendências da aplicação de IA no mercado financeiro, destacando a evolução dos agentes inteligentes nos bancos.

---

## Engenharia de Prompts e "Cicatrizes"
**Objetivo:**
A estratégia de engenharia de prompts foi estruturada para conduzir o NotebookLM por uma trilha de aprendizagem progressiva em diferentes níveis, explorando as fontes fornecidas ao caderno. A capacidade da IA foi testada com 2 modelos de prompt: simples (genérico) e complexo. O Notebook foi configurado para apresentar respostas curtas.

### Prompts:

| Nível | Objetivo | Prompt Simples | Prompt Complexo |
| --- | --- | --- | --- |
| **1. Exploração (Conceito)** | Entender o conceito básico | O que é um agente de IA? | "Explique a arquitetura completa de um agente de IA moderno, detalhando LLM, memória, planejamento, ferramentas e ciclo de execução." |
| **2. Comparação** | Comparar tecnologias | Como um agente difere de um chatbot tradicional? | "Compare um chatbot bancário tradicional com um agente de IA autônomo, destacando diferenças em autonomia, memória, uso de ferramentas e tomada de decisão." |
| **3. Funcionamento** | Compreender o mecanismo interno | Como um agente toma decisões? | "Explique como um agente utiliza o ciclo Reason → Act → Observe para tomar decisões em um ambiente bancário, incluindo mecanismos para evitar erros e alucinações." |
| **4. Aplicação** | Aplicar o conceito a um contexto real | Como um banco pode utilizar agentes? | "Projete uma estratégia de implementação de agentes de IA em um banco, identificando os principais processos que podem ser automatizados e os benefícios esperados." |
| **5. Projeto (Arquitetura)** | Projetar uma solução completa | Como agentes ajudam na análise de crédito? | "Projete a arquitetura de um agente bancário para aprovação de crédito, indicando LLM, memória, ferramentas, fontes de dados e mecanismos de segurança." |
| **6. Avaliação Crítica** | Identificar riscos e limitações | Como garantir segurança e LGPD? | "Quais seriam os principais riscos de segurança ao implantar agentes de IA em bancos brasileiros e quais estratégias mitigariam esses riscos considerando a LGPD?" |
| **7. Visão Estratégica (Síntese)** | Projetar tendências futuras | Como será o futuro dos bancos com Agentic AI? | "Analise como o Agentic AI poderá transformar a operação dos bancos na próxima década, considerando impactos tecnológicos, regulatórios e no atendimento ao cliente." |

### Extra - Prompts de aprofundamento:

| Tema | Prompt Simples | Prompt Complexo |
| --- | --- | --- |
| **Uso de Ferramentas** | Como um agente utiliza ferramentas? | "Descreva como um agente decide qual ferramenta utilizar, como executa a chamada e valida o resultado antes de responder ao usuário." |
| **Integração** | Como agentes conversam com sistemas bancários? | "Explique uma arquitetura de integração entre agentes de IA e sistemas bancários legados utilizando APIs, ferramentas e mecanismos de autenticação." |

---

## Análises, resultados e conclusão final
Durante o desenvolvimento deste projeto, foi aplicada uma estratégia de **Engenharia de Prompts baseada em níveis de complexidade**, com o objetivo de avaliar como diferentes formas de formular perguntas influenciam a qualidade das respostas produzidas pelo NotebookLM.

Os prompts foram organizados em uma sequência evolutiva, iniciando com perguntas exploratórias (conceitos básicos), avançando para comparações, explicações de funcionamento, aplicações práticas, projeto de arquiteturas, avaliação de riscos e, por fim, análises estratégicas sobre o futuro da Agentic AI no setor bancário. Para cada nível, foram elaborados um **prompt simples** e um **prompt avançado**, permitindo comparar diretamente o impacto do refinamento das instruções.

Em seguida, as respostas obtidas foram analisadas criticamente, identificando informações ausentes, pontos que poderiam ser aprofundados e oportunidades de melhoria. Com base nessa análise, foram criadas novas versões dos prompts, incorporando instruções mais específicas para direcionar o NotebookLM à produção de respostas mais completas e contextualizadas.

Os testes demonstraram que perguntas abertas e genéricas tendem a gerar respostas corretas, porém excessivamente descritivas e focadas na síntese das fontes. Em muitos casos, o NotebookLM privilegiou definições conceituais, deixando de abordar aspectos arquiteturais, integração entre componentes, aplicações práticas, limitações ou critérios de decisão.

À medida que os prompts passaram a especificar exatamente quais elementos deveriam ser contemplados, como arquitetura, fluxo de execução, memória, RAG, ferramentas, mecanismos de segurança, exemplos de aplicação e organização em tópicos ou tabelas comparativas, as respostas tornaram-se significativamente mais completas, técnicas e estruturadas.

Outro aprendizado importante foi que o NotebookLM apresenta melhor desempenho quando recebe orientações explícitas sobre **como organizar a resposta**. Solicitações como "organize em tópicos", "apresente uma tabela comparativa", "descreva o fluxo completo da arquitetura", "utilize exclusivamente as fontes do notebook" e "finalize com um exemplo aplicado ao setor bancário" contribuíram para aumentar a consistência, reduzir ambiguidades e incentivar a síntese de informações provenientes de diferentes documentos.

### Troubleshooting ("Cicatrizes")
Ao longo do processo, foram identificadas algumas dificuldades recorrentes para extrair respostas mais completas do NotebookLM:
- Os primeiros prompts produziram respostas corretas, porém superficiais, concentrando-se apenas nos conceitos mais evidentes das fontes.
- Em diversas situações, o NotebookLM descrevia os componentes de um agente de IA, mas não explicava como esses componentes se relacionavam ao longo do fluxo de execução.
- Algumas respostas apresentavam apenas parte das informações disponíveis nas fontes, exigindo prompts mais específicos para estimular a integração entre diferentes documentos do notebook.
- Em perguntas comparativas, o modelo respondia apenas às diferenças principais, omitindo critérios relevantes como vantagens, limitações, cenários de uso, integração com sistemas e nível de autonomia.
- Em prompts arquiteturais, a IA tendia a listar componentes isoladamente, sendo necessário solicitar explicitamente o fluxo completo da arquitetura, desde a entrada do usuário até a resposta final.
- Aspectos como memória, RAG, governança, integração com APIs, múltiplos agentes e mecanismos de mitigação de alucinações frequentemente precisaram ser solicitados de forma explícita para serem abordados com maior profundidade.
- Respostas inicialmente apresentadas em texto corrido tornaram-se mais claras e completas quando os prompts passaram a solicitar organização em tópicos, tabelas comparativas ou exemplos práticos.

Como resultado desse processo iterativo, foi possível observar que a qualidade das respostas não depende apenas da qualidade das fontes utilizadas, mas também da precisão, do contexto e do nível de detalhamento dos prompts. A evolução gradual das perguntas permitiu explorar melhor o potencial do NotebookLM e demonstrou, na prática, a importância da Engenharia de Prompts como ferramenta para orientar modelos de IA na geração de respostas mais completas, consistentes e alinhadas aos objetivos do usuário.

*Para o acesso à análise detalhada de todos os prompts, solicitar à autora.*

---

## Analisando as respostas do Notebook LM e refinamento final de prompts
Para que o trabalho não fique muito extenso, transcrevi na íntegra as respostas do Notebook para os níveis de prompt 1, 2 e 3. Para os demais, trouxe uma análise técnica geral dos resultados obtidos, no próximo item, conclusão.

### Nível 1 - Exploração
**Prompt Simples:** O que é um agente de IA?
**Resposta Notebook:** Um agente de IA é um sistema que utiliza um modelo de linguagem (LLM) como seu "cérebro" para determinar autonomamente quais ações tomar e em que ordem para concluir uma tarefa. Diferente de sistemas tradicionais que seguem passos pré-definidos, o agente opera em um loop, chamando ferramentas e processando informações até que o objetivo seja alcançado.
Os principais componentes e características de um agente incluem:
- **Modelo + Harness:** O agente combina um modelo de IA com um "harness" (suporte), que fornece ao modelo o contexto e as ferramentas certas no momento certo.
- **Uso de Ferramentas:** Agentes podem interagir com o mundo real através de ferramentas externas, como calculadoras, mecanismos de busca ou APIs.
- **Raciocínio e Planejamento:** Muitos agentes utilizam o framework ReAct (Reasoning and Acting).
- **Autonomia e Autocorreção:** Eles são capazes de criar e corrigir seu próprio roteiro para atingir uma meta.

**Análise da resposta:** A resposta do NotebookLM está boa, mas não está completa. Ela responde corretamente "o que é", porém enfatiza mais o funcionamento do agente do que sua definição. Faltou a definição conceitual, a diferença de um assistente e exemplos práticos, especialmente no contexto bancário.

**Prompt Complexo:** Explique a arquitetura completa de um agente de IA moderno, detalhando LLM, memória, planejamento, ferramentas e ciclo de execução.
**Resposta Notebook:** A arquitetura moderna de um agente de IA é definida pela fórmula Agente = Modelo + Harness (Suporte) , onde o "harness" fornece ao modelo o contexto, a memória e as ferramentas necessárias para agir.
- **LLM (Cérebro):** Mecanismo central de raciocínio.
- **Memória:** Transforma o modelo para "stateful", permitindo que recorde interações anteriores.
- **Planejamento:** Cria e autocorrige seu roteiro.
- **Ferramentas:** Permitem interagir com o mundo real (APIs externas).
- **Ciclo de Execução (ReAct):** Loop de Pensamento, Ação e Observação.

**Análise da resposta:** Embora bem estruturada, poderia ser mais completa ao apresentar o fluxo integrado, detalhar o RAG, e abordar governança e exemplos.

**Prompt melhorado (Final):** Explique de forma abrangente o que caracteriza um agente de IA, apresentando sua definição conceitual, os componentes... (com respostas detalhadas sobre Memória, RAG, e Exemplos no Setor Bancário como Varejo, Corporativo, Operações e Experiência).

### Nível 2 - Comparação
**Prompt Simples:** Como um agente difere de um chatbot tradicional?
**Resposta Notebook:** A principal diferença entre um agente de IA e um chatbot tradicional reside na autonomia e na capacidade de ação. Chatbots seguem fluxos pré-definidos, agentes operam em ciclos:
1. Autonomia na Tomada de Decisão
2. Uso de Ferramentas Externas
3. Ciclo de Raciocínio (ReAct)
4. Gestão de Tarefas Complexas

**Análise da resposta:** A resposta cobre os principais pilares, mas omitiu a gestão de Memória, Objetivo (Goal-oriented) e nível de intervenção humana.

**Prompt Complexo:** Compare um chatbot bancário tradicional com um agente de IA autônomo, destacando diferenças em autonomia, memória, uso de ferramentas e tomada de decisão.
**Resposta Notebook:** Distinções detalhadas entre Autonomia e Planejamento, Memória e Contexto ("stateless" vs "stateful"), Uso de Ferramentas e Tomada de Decisão (ReAct). O agente passa de consultas de saldo para refinanciamento de hipotecas ou investigações de crimes.

*(As demais análises para níveis subsequentes, como detalhado no documento...)*
- **Memória:** "Explique a função de um 'checkpointer' na manutenção da memória de longo prazo em conversas bancárias persistentes."
- **Ferramentas:** "Crie uma definição de ferramenta (Tool) em formato JSON para um agente que consulta o saldo de uma conta corrente."
- **RAG e Vetores:** "Por que os 'Vector Stores' são essenciais para agentes de IA que precisam processar regulamentações financeiras em tempo real?"
- **Human-in-the-loop:** "Em quais etapas de um processo de análise de crédito corporativo a intervenção humana (HITL) é indispensável em um fluxo de trabalho agentizado?"
- **Futuro:** "Descreva como o 'Model Context Protocol' (MCP) pode ajudar na exposição de dados bancários privados para modelos de linguagem de forma segura."

---

## 5. Conclusão
Os Agentes de IA representam o ápice da Inteligência Artificial Generativa aplicada, movendo o setor bancário de sistemas de resposta passiva para operações proativas e integradas. Ao combinar o raciocínio dos LLMs com a capacidade de execução de ferramentas e memórias persistentes, os bancos podem finalmente oferecer serviços que "têm as costas do cliente" em cada passo do seu dia financeiro.

A transição para agentes não é apenas uma mudança técnica, mas uma evolução na **confiança**. Com a governança correta e a supervisão humana adequada, essa tecnologia permitirá que as instituições financeiras operem com uma agilidade sem precedentes, transformando o que antes levava meses em processos de apenas alguns minutos.
