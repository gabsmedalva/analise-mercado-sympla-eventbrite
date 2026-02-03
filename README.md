# Análise de Mercado: Sympla vs Eventbrite com GenAI

Este projeto utiliza Engenharia de Dados e IA Generativa (Google Vertex AI) para analisar 10.000 reviews reais da Google Play Store e identificar vantagens competitivas estruturais.

## O que tem no Notebook?
O arquivo [`analise_sentimento_sympla_vertexai.ipynb`](./analise_sentimento_sympla_vertexai.ipynb) contém o pipeline completo:

1.  **Engenharia de Prompt:** Configuração do modelo Gemini 2.5 Flash para classificação zero-shot.
2.  **Tratamento de Erros:** Lógica de *retry* e *backoff* para lidar com cotas da API.
3.  **Analytics:** Consultas SQL via BigQuery Client para gerar métricas de NPS e clusters de reclamação.
4.  **Autópsia de Release:** Análise automatizada que identificou bugs críticos na versão v12.6 do app.

## Tech Stack
* **Cloud:** Google Cloud Platform (BigQuery, Vertex AI)
* **Language:** Python (Pandas, Google Cloud SDK)
* **AI:** Gemini 1.5 Pro & 2.5 Flash

---
*Este notebook foi exportado diretamente do ambiente Google Cloud BigQuery Studio.*
