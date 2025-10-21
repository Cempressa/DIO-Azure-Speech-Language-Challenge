# DIO-Azure-Speech-Language-Challenge
Entrega final do Desafio DIO, utilizando Azure Speech Studio e Language Studio para análise de fala e linguagem natural.

# Desafio DIO: Análise de Fala e Linguagem Natural com Azure AI Services

## 🎯 Objetivo do Laboratório

Este projeto visa demonstrar o uso prático e aprofundado das ferramentas **Azure Speech Studio** e **Language Studio**, conforme proposto pela Digital Innovation One (DIO). O foco principal é a criação de soluções em Inteligência Artificial para análise de voz e linguagem natural.

Ao concluir, foram alcançados os seguintes objetivos de aprendizado:
* Aplicação de conceitos em um ambiente prático (Azure).
* Documentação de processos técnicos de forma clara e estruturada.
* Uso do GitHub como ferramenta para compartilhamento de documentação técnica.

## ⚙️ Configuração do Ambiente no Azure

Para garantir que o laboratório fosse realizado sem custos, foi utilizado o benefício da Assinatura Gratuita do Azure.

### 1. Criação do Recurso de Serviços de IA

Foi criado um recurso de **Serviços de Fala** (Speech Services), que oferece o acesso tanto ao Speech Studio quanto ao Language Studio.

* **Assinatura:** `Azure subscription 1`
* **Grupo de Recursos:** `RG-DIO-IA`
* **Nome do Recurso:** `DIO-Speech-2025`
* **Região:** `East US`
* **Faixa de Preços:** **`Free F0`** (Gratuito) - Crucial para evitar custos.

**Evidência da Criação do Recurso:**
![Detalhes do recurso DIO-Speech-2025 no plano Free F0](images/image_a50e94.png)

---

## 🎙️ Prática 1: Conversão de Fala em Texto (Speech Studio)

A primeira etapa prática consistiu na **Conversão de Fala em Texto** (Speech-to-Text), utilizando a funcionalidade de **Transcrição em Lote** (Batch Transcription), que simula o carregamento de arquivos de áudio para processamento.

### Ações Executadas:
1.  Acesso ao Speech Studio (`https://speech.microsoft.com/portal/`).
2.  Navegação até **"Transcrição em lote"** no menu **"Conversão de fala em texto"**.
3.  Carregamento de um arquivo de áudio para transcrição, com o idioma configurado para **Português (Brasil)**.
4.  O resultado exibiu a transcrição do áudio, que foi copiado para a próxima etapa de análise de linguagem.

**Captura de Tela da Transcrição:**
* *Insira aqui o link para a captura de tela do resultado da Transcrição em Lote (ex: `![Resultado da Transcrição](images/transcricao_lote.png)`).*

---

## 📝 Prática 2: Análise de Sentimento (Language Studio)

A segunda etapa utilizou o texto obtido na transcrição para realizar a **Análise de Sentimento**, focando em habilidades de linguagem natural.

### Ações Executadas:
1.  Acesso ao Language Studio (`https://language.cognitive.azure.com/`).
2.  Navegação até **"Análise de sentimento e mineração de opiniões"** na seção **"Classificar texto"**.
3.  O texto transcrito (ou um texto de exemplo) foi inserido no playground, e a análise foi executada.
4.  O sistema retornou a classificação do sentimento no
