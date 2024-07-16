# Chatbot de Perguntas e Respostas com Histórico Consciente

Este projeto implementa um sistema de chatbot para responder perguntas com base em um histórico de conversas. Utiliza a biblioteca Langchain para integrar modelos de linguagem e processamento de texto.

## Funcionalidades Principais

- **Carregamento de Documentos:** Carrega documentos PDF para análise.
- **Indexação de Documentos:** Usa FAISS para indexar documentos divididos em pedaços menores.
- **Modelo de Linguagem:** Utiliza Langchain para criar modelos de perguntas e respostas baseados em um histórico de conversas.
- **Histórico de Conversas:** Armazena o histórico de mensagens para contextos futuros.
- **Integração com HuggingFace:** Usa embeddings do HuggingFace para representação de texto.

## Requisitos

- Python 3.10 ou superior
- Pacotes listados em `requirements.txt`
- Credenciais para acesso ao serviço de modelo de linguagem

## Instalação e Uso

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```
2. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```
3. Configure suas variáveis de ambiente:
   Crie um arquivo `.env` na raiz do projeto e adicione suas credenciais:
   ```makefile
   GROQ_API_KEY=sua-chave-de-api-aqui
   ```

## Mais Informações

Para mais informações sobre este projeto, confira meu artigo publicado no Linkedin.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para discutir novas funcionalidades
