# IA_Azure_CopilotAndOpenAI

# Explorando os Recursos de IA Generativa com Copilot e OpenAI

Este repositório contém um guia básico para iniciar um projeto utilizando **IA Generativa com GitHub Copilot e OpenAI**, incluindo a configuração, exemplos práticos e testes.

##  Pré-requisitos

Antes de começar, certifique-se de ter:
- Uma conta no [GitHub](https://github.com/)
- Acesso ao **GitHub Copilot** (assinatura ativa ou período de teste)
- Uma conta na [OpenAI](https://openai.com/)
- Criado uma chave de API no [OpenAI API](https://platform.openai.com/signup/)
- Python ou outra linguagem compatível instalada

## 🚀 Configurando o GitHub Copilot

1. Acesse o [GitHub Copilot](https://github.com/features/copilot)
2. Ative a assinatura ou inicie um teste gratuito
3. Instale a extensão do Copilot no seu editor de código (VS Code, JetBrains ou Neovim)
4. Faça login no GitHub e habilite o Copilot nas configurações do editor

### Testando o Copilot
Abra um arquivo `.py` no VS Code e comece a digitar um comentário, por exemplo:
```python
# Função para calcular a soma de dois números
```
O Copilot sugerirá automaticamente o código correspondente.

##  Usando OpenAI API

### 1️⃣ Instalando a Biblioteca OpenAI
```bash
pip install openai
```

### 2️⃣ Criando um Script para Gerar Texto
```python
import openai

openai.api_key = "SUA_CHAVE_API"

response = openai.ChatCompletion.create(
    model="gpt-4",
    messages=[{"role": "user", "content": "Explique a teoria da relatividade de forma simples."}]
)

print(response["choices"][0]["message"]["content"])
```

### 3️⃣ Executando o Script
```bash
python meu_script.py
```

##  Explorando Outras Funcionalidades
- **Gerar código automaticamente** com Copilot
- **Usar OpenAI para análise de textos** (tradução, resumo, sentimentos)
- **Criar chatbots inteligentes** com OpenAI
- **Gerar imagens com DALL·E**
- ![Print do Azure AI Language Studio](images/img_1.png)
- ![Print do Azure AI Language Studio](images/img_2.png)
- ![Print do Azure AI Language Studio](images/img_3.png)


## 📚 Referências
- [Documentação do GitHub Copilot](https://docs.github.com/en/copilot/)
- [Documentação da OpenAI](https://platform.openai.com/docs/)

---
