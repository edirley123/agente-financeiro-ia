# 📊 Avaliação e Métricas do Agente

Para garantir a eficiência e a segurança do **Agente Financeiro Inteligente**, utilizamos três pilares de avaliação:

## 1. Precisão e Assertividade (Grounding)
Esta métrica avalia se a IA está extraindo os valores corretos dos arquivos CSV/JSON.
* **KPI:** Porcentagem de respostas cujos valores numéricos coincidem exatamente com a base de dados.
* **Meta:** 100% de precisão para dados históricos.

## 2. Taxa de Respostas Seguras (Anti-Alucinação)
Mede a capacidade do agente em dizer "Não sei" quando a informação não existe na base.
* **Teste:** Inserir 10 perguntas sobre temas externos (ex: cotação de moedas, notícias).
* **Meta:** 0% de alucinação (o agente não deve inventar dados em nenhuma hipótese).

## 3. Coerência com o Perfil (Personalização)
Verifica se as sugestões de investimento respeitam o `perfil_investidor.json`.
* **Cenário:** Se o perfil é 'Conservador', o agente é penalizado se sugerir 'Renda Variável'.
* **Meta:** 100% de aderência ao perfil de risco do cliente.

## 4. Métricas de Performance (Engenharia)
* **Tempo de Resposta (Latency):** O agente deve responder em menos de 3 segundos para manter a fluidez.
* **Consumo de Tokens:** Monitoramento para otimizar o custo operacional da solução.
