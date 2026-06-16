# DIO / Bradesco - Bootcamp GenAI & Dados - Desafio 01

## Contexto e Objetivos

Este projeto faz parte do Bootcamp DIO/Bradesco em IA e Dados e tem como objetivo explorar o uso da Inteligência Artificial Generativa como ferramenta de aprendizagem ativa, por meio da construção de um caderno temático no NotebookLM.

O tema escolhido foi a aplicação de IA Generativa na análise e resolução de problemas relatados por clientes do setor bancário, com foco no contexto de atendimento do Bradesco. O estudo parte da observação de que muitos clientes enfrentam dificuldades para encontrar rapidamente a solução adequada para suas demandas, frequentemente precisando transitar entre diferentes canais de atendimento, como aplicativo, agência, SAC, Ouvidoria e plataformas externas de reclamação.

A proposta é servir como base conceitual para o desenvolvimento futuro da **BIA Resolve**, um agente conversacional inteligente especializado em orientação e apoio à resolução de problemas bancários. Diferentemente de um chatbot tradicional baseado apenas em perguntas e respostas, a BIA Resolve busca compreender o contexto da solicitação do cliente, realizar perguntas complementares, identificar tentativas anteriores de resolução, fornecer orientações personalizadas e indicar o canal mais adequado para cada situação.

Além do suporte ao cliente, a solução também prevê a geração de conhecimento para o negócio por meio da coleta estruturada de feedback durante e após o atendimento. Dessa forma, o agente não apenas auxilia na resolução de problemas, mas também contribui para a identificação de oportunidades de melhoria nos processos e serviços oferecidos pela instituição.

### Objetivos de Estudo

* Compreender o cenário atual das reclamações e dificuldades enfrentadas por clientes do setor bancário.
* Identificar os principais motivos que levam consumidores a buscar canais formais de atendimento, reclamação e resolução de conflitos.
* Estudar o papel de canais como SAC, Ouvidoria, Consumidor.gov.br, Banco Central e atendimento presencial na jornada de resolução de problemas.
* Analisar como técnicas de IA Generativa podem ser utilizadas para compreender, classificar e orientar clientes em situações de reclamação ou dificuldade operacional.
* Investigar estratégias para reduzir a fricção na jornada do cliente, evitando transferências desnecessárias entre múltiplos canais de atendimento.
* Entender como informações de contexto, como histórico de tentativas de resolução e grau de satisfação do cliente, podem contribuir para uma experiência mais eficiente e personalizada.
* Avaliar formas de coletar feedback durante e após o atendimento para medir utilidade das orientações fornecidas, taxa de resolução e satisfação do cliente.
* Criar uma base de conhecimento que permita ao agente identificar padrões de problemas, sugerir próximos passos adequados e gerar resumos estruturados para facilitar a continuidade do atendimento humano quando necessário.

### Visão da Solução

A BIA Resolve será concebida como um agente conversacional capaz de interagir com o cliente por linguagem natural, compreender o problema relatado, conduzir uma investigação guiada por perguntas contextualizadas e oferecer orientações alinhadas ao tipo de ocorrência identificada.

Entre as funcionalidades previstas estão:

* Identificação automática da categoria do problema relatado.
* Coleta de contexto sobre tentativas anteriores de resolução.
* Orientação personalizada baseada na situação apresentada pelo cliente.
* Indicação do canal mais adequado para continuidade do atendimento.
* Escalonamento antecipado para atendimento humano em casos complexos ou recorrentes.
* Geração automática de resumos para SAC, Ouvidoria ou outros canais.
* Coleta de feedback sobre utilidade das orientações recebidas.
* Avaliação final da satisfação e da resolução do problema.

Dessa forma, o projeto busca demonstrar como a IA Generativa pode atuar não apenas como uma interface de atendimento, mas como uma ferramenta de apoio à resolução efetiva de problemas, contribuindo simultaneamente para a melhoria da experiência do cliente e para a geração de insights relevantes para o negócio.

## Referências Utilizadas

### Relatório da Ouvidoria Bradesco – 2º Semestre de 2025

Relatório institucional que apresenta o desempenho dos canais de atendimento do Bradesco, incluindo SAC, Ouvidoria, redes sociais, Consumidor.gov.br, Banco Central e Procon. O documento reúne indicadores de volume de atendimentos, satisfação dos clientes, resolutividade e iniciativas de melhoria contínua adotadas pela instituição.

**Importância para a pesquisa**

Esta referência foi utilizada para compreender a estrutura atual de atendimento ao cliente do Bradesco, identificar os principais canais disponíveis para resolução de problemas e analisar métricas relacionadas à satisfação, tempo de resposta e eficiência operacional. O documento também demonstra como a Ouvidoria transforma manifestações dos clientes em oportunidades de melhoria e evidencia a utilização de Inteligência Artificial Generativa em processos internos de atendimento.

---

### Boletim Sindec e ProConsumidor 2024

Publicação da Secretaria Nacional do Consumidor (Senacon) que apresenta estatísticas nacionais sobre reclamações registradas nos Procons brasileiros por meio dos sistemas Sindec e ProConsumidor. O relatório reúne informações sobre empresas mais reclamadas, problemas mais frequentes, perfil dos consumidores e principais assuntos demandados nos órgãos de defesa do consumidor.

**Importância para a pesquisa**

O documento foi utilizado para identificar padrões de reclamações de consumidores em âmbito nacional e compreender os principais motivos que levam clientes a buscar órgãos externos de defesa do consumidor. Os dados ajudam a mapear problemas recorrentes relacionados ao setor bancário, como cobranças indevidas, crédito consignado, cartões, contas correntes e falhas de atendimento, servindo como insumo para a construção das categorias de problemas que poderão ser tratadas pela solução proposta.

---

### Caderno de Educação Financeira – Banco Central do Brasil (2026)

Material educacional produzido pelo Banco Central do Brasil com foco em cidadania financeira, planejamento financeiro pessoal, orçamento familiar, uso consciente do crédito, prevenção ao endividamento, consumo responsável e investimentos. O conteúdo apresenta conceitos fundamentais para a tomada de decisões financeiras mais conscientes e sustentáveis.

**Importância para a pesquisa**

Esta referência contribui para compreender as principais dificuldades enfrentadas pelos consumidores na gestão de suas finanças e oferece uma base conceitual para a elaboração de orientações educativas que podem ser fornecidas pela BIA Resolve. Além da resolução de problemas, o agente poderá atuar como instrumento de apoio à educação financeira, auxiliando clientes em temas relacionados a orçamento, crédito, dívidas, planejamento financeiro e consumo consciente.

---

### Relatório de Ouvidorias e Canais de Relacionamento com o Consumidor (FEBRABAN, 2024)

Publicação da Federação Brasileira de Bancos (FEBRABAN) que apresenta iniciativas, indicadores e práticas adotadas pelas instituições financeiras para aprimorar o relacionamento com consumidores. O relatório aborda temas como atuação das ouvidorias, evolução dos canais de atendimento, acessibilidade, educação financeira, segurança digital, prevenção a fraudes e tratamento de públicos vulneráveis, destacando o papel desses mecanismos na melhoria contínua da experiência do cliente.

**Importância para a pesquisa**

Esta referência foi utilizada para compreender como o setor bancário brasileiro estrutura seus canais de relacionamento e atendimento ao consumidor. O documento contribuiu para a identificação de práticas adotadas pelas instituições financeiras na gestão de demandas, resolução de conflitos e promoção da satisfação dos clientes, servindo como base para o desenho dos fluxos de atendimento, encaminhamento e suporte da BIA Resolve.

---

### Guia de Boas Práticas de Relacionamento com os Vulneráveis (FEBRABAN, 2023)

Publicação da FEBRABAN desenvolvida para compartilhar práticas adotadas pelas instituições financeiras no atendimento a consumidores em situação de vulnerabilidade. O guia apresenta conceitos, desafios e recomendações relacionados à identificação e ao atendimento de públicos que podem apresentar limitações temporárias ou permanentes em sua capacidade de compreensão, tomada de decisão ou acesso aos serviços financeiros, incluindo idosos, pessoas com deficiência, indivíduos com baixa escolaridade, baixa maturidade digital ou em situação de superendividamento.

**Importância para a pesquisa**

Esta referência contribuiu para a definição dos princípios de atendimento que orientarão o comportamento da BIA Resolve. As recomendações presentes no documento auxiliaram na concepção de uma solução mais inclusiva, acessível e centrada no usuário, capaz de adaptar a comunicação ao perfil do cliente, utilizar linguagem clara e identificar situações que demandem suporte especializado ou encaminhamento prioritário para atendimento humano.

