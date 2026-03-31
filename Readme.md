# 🎙️ Assistente de Voz Financeiro com IA (Whisper + YFinance)

Este projeto foi desenvolvido como parte do meu portfólio de **Engenharia de Dados e IA**, aplicando conceitos de Processamento de Linguagem Natural (NLP) e ingestão de dados em tempo real. O assistente é capaz de ouvir uma pergunta por voz, identificar o ativo financeiro citado, buscar a cotação atualizada na B3/Yahoo Finance e responder por áudio.

---

## 🚀 Tecnologias Utilizadas

* **Python 3.12**: Linguagem base para integração do pipeline.
* **OpenAI Whisper**: Modelo de Machine Learning para transcrição de áudio (Speech-to-Text) rodando localmente.
* **Yahoo Finance (yfinance)**: Ingestão de dados financeiros em tempo real.
* **gTTS (Google Text-to-Speech)**: Síntese de voz para resposta do assistente.
* **Google Colab**: Ambiente de desenvolvimento e execução em nuvem.

---

## 🛠️ Arquitetura do Projeto

1.  **Captura de Áudio**: Interface JavaScript para gravação via navegador.
2.  **Transcrição**: O modelo Whisper processa o `.wav` e converte em string.
3.  **Processamento de Dados**: Lógica em Python identifica o ticker do ativo (ex: PETR4, Dólar).
4.  **Consulta de API**: O `yfinance` busca o preço de fechamento mais recente.
5.  **Output de Voz**: A resposta é gerada e convertida em áudio para o usuário.

---

## 📋 Como Executar

1. **Acesse o Notebook**: Clique no botão abaixo para abrir o projeto diretamente no Google Colab:
   
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-3CwZC8hj_MsRZlUttNsP0_uFzm2O1wn)

2. **Configuração**: No menu do Colab, vá em `Ambiente de Execução` > `Executar tudo`.
3. **Interação**: 
   - Localize o bloco de **Captura de Áudio**.
   - Clique no botão de gravar e pergunte sobre um ativo (ex: "Qual o preço do dólar?").
   - O sistema processará sua voz e responderá via áudio automaticamente.

---

## 👤 Autor

**Victor Biscaia** *Data Analyst & Engineer* Salvador, Bahia - Brasil  
[LinkedIn](https://www.linkedin.com/in/victor-biscaia/) | [GitHub](https://github.com/vbiscaia-ai)

---
*Projeto educativo desenvolvido durante Bootcamp Bradesco - GenAI & Dados.*
