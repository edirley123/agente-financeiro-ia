🤖 Agente Financeiro Inteligente com IA Generativa
📌 Visão Geral
Este projeto apresenta a IA financeira, um agente inteligente desenvolvido para o setor financeiro. Diferente de chatbots tradicionais, este agente utiliza IA Generativa e a técnica de RAG (Retrieval-Augmented Generation) para fornecer consultoria personalizada, proativa e segura, baseada em dados reais de transações e perfis de investimento.

🎯 Problema e Solução
Problema: A maioria dos assistentes financeiros é limitada a respostas genéricas e reativas, falhando em oferecer uma visão estratégica do patrimônio do cliente.

Solução: O agente analisa padrões de consumo e objetivos de longo prazo para atuar como um mentor financeiro, garantindo que cada sugestão seja fundamentada na base de conhecimento (CSV/JSON) e protegida contra alucinações.

📂 Estrutura do Projeto
O repositório está organizado seguindo as melhores práticas de Engenharia de Software:

data/: Base de conhecimento contendo o histórico de transações, perfis de usuários e catálogo de produtos financeiros.

docs/: Documentação detalhada incluindo arquitetura, engenharia de prompts, métricas de avaliação e o roteiro do pitch.

src/: Código-fonte do protótipo desenvolvido em Python.

assets/: Recursos visuais e mídias do projeto.

🛠️ Tecnologias Utilizadas
Linguagem: Python 3.x

Bibliotecas de Dados: Pandas e JSON

IA Generativa: Integração com LLMs via API (Prompt Engineering Avançado)

Ambiente: Google Colab / Visual Studio Code

Controle de Versão: Git & GitHub

⚙️ Arquitetura e Segurança
O agente opera através de um fluxo de dados rigoroso para garantir a confiabilidade:

Ingestão de Dados: Leitura de arquivos estruturados (CSV/JSON).

Contextualização: Injeção de dados reais no Prompt de Sistema.

Filtro Anti-Alucinação: Regras estritas que impedem a IA de gerar informações fora da base de dados fornecida.

📊 Avaliação de Resultados
O sucesso do agente é medido através de:

Acurácia de Dados: Comparação entre as respostas da IA e os valores reais das planilhas.

Aderência ao Perfil: Garantia de que sugestões de investimento respeitam o perfil de risco do cliente.

Conformidade de Segurança: Verificação de que o agente não responde sobre temas externos ao domínio financeiro.

👨‍💻 Desenvolvedor
Edirley Ferreira da Costa Estudante DIO Especialista em Gestão de Varejo com foco em inovação tecnológica e Inteligência Artificial.
