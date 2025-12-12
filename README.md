## 📊 Santander Dev Week - ETL com IA
Projeto de pipeline ETL (Extract, Transform, Load) desenvolvido para a Santander Dev Week 2023 (DIO).

# 📝 O Projeto
O script extrai dados de clientes via API, utiliza a IA do GPT-4o-mini para gerar mensagens de investimento personalizadas e salva o resultado final em um arquivo JSON.

# 🛠️ Tecnologias
- Python 3

- OpenAI API (Processamento de Linguagem Natural)

- Requests (Consumo de API REST)

- Google Colab (Ambiente de execução)

# 🚀 Fluxo de Execução
1. Extract: Consome a API de clientes.

2. Transform: Gera mensagens de marketing com IA (com sistema de fallback para erros).

3. Load: Exporta os dados enriquecidos para o Google Drive.

# 🔑 Configuração Rápida
1. No Colab, vá em Secrets (ícone de chave).

2. Adicione a chave OPENAI_API_KEY.

3. Ative o Notebook access.

4. Execute as células em ordem.
