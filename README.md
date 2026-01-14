# 🎙️ Assistente de Voz com Gemini e Whisper

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini-orange)](https://ai.google.dev/)
[![Whisper](https://img.shields.io/badge/SpeechToText-Whisper-green)](https://github.com/openai/whisper)

Este projeto é um assistente de voz completo desenvolvido para rodar no **Google Colab**. Ele utiliza o modelo **Whisper** da OpenAI para transcrição e o **Google Gemini** para processamento de linguagem natural e geração de respostas.



## 🚀 Funcionalidades

* **Captação de Áudio:** Gravação direta via navegador usando JavaScript.
* **Speech-to-Text:** Transcrição precisa com o modelo Whisper (OpenAI).
* **Inteligência Artificial:** Processamento de contexto e resposta via Gemini (Google).
* **Text-to-Speech:** Conversão da resposta em áudio utilizando gTTS.

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Função |
| :--- | :--- |
| **Python** | Linguagem principal |
| **Whisper** | Transcrição de áudio para texto |
| **Google Gemini** | Modelo de linguagem (LLM) |
| **gTTS** | Google Text-to-Speech para a voz de saída |
| **Google Colab** | Ambiente de execução |

---

## 📋 Como Configurar

### 1. Obter Chave da API
Para utilizar este projeto, você precisará de uma chave de API do Google AI Studio:
1.  Acesse o [Google AI Studio](https://aistudio.google.com/).
2.  Crie uma nova **API Key**.
3.  No Google Colab, adicione a chave nos "Secrets" (ícone de chave na lateral esquerda) com o nome `GOOGLE_API_KEY`.

### 2. Instalação de Dependências
O projeto requer as seguintes bibliotecas que serão instaladas automaticamente ao executar o notebook:
```bash
pip install git+[https://github.com/openai/whisper.git](https://github.com/openai/whisper.git)
pip install -q -U google-genai
pip install gTTS
