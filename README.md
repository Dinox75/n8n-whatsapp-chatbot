# 🤖 n8n WhatsApp Chatbot com IA

Este projeto foi criado a partir da curiosidade em explorar o poder de automação do **n8n**, conectando APIs e inteligência artificial para criar um **chatbot de WhatsApp** totalmente automatizado.

## 💡 Sobre o projeto

O fluxo recebe mensagens via **Webhook (Z-API)**, registra contatos no **Google Sheets** e usa o modelo **Groq + LangChain** para gerar respostas automáticas, cordiais e humanas.  
Em seguida, o bot envia a resposta de volta ao usuário no WhatsApp.

### 🔗 Principais integrações
- **Z-API:** conexão com o WhatsApp  
- **Google Sheets:** armazenamento de contatos e dados  
- **Groq + LangChain:** geração de respostas com IA  
- **n8n:** orquestração do fluxo completo  

## 🧩 Como importar o workflow

1. Baixe o arquivo [`Chatbot_Limpo_v2.json`](./Chatbot_Limpo_v2.json)
2. Acesse o painel do [n8n](https://n8n.io)
3. Clique em **Workflows → Import**
4. Selecione o arquivo `.json` e importe
5. Conecte suas credenciais:
   - **Z-API:** adicione seu `instance_id` e `token`
   - **Google Sheets:** conecte com sua conta Google
   - **Groq:** insira sua chave de API
6. Ative o workflow 🚀

## ⚙️ Requisitos
- Conta no [n8n](https://n8n.io)
- Conta na [Z-API](https://z-api.io)
- Conta [Groq](https://groq.com)
- Acesso ao Google Sheets

## 👨‍💻 Autor
**Vinicius Lima**  
💼 [LinkedIn](https://www.linkedin.com/in/vinicius-lima-b98100308/)  
📧 vibylima75@gmail.com

---

> ⚠️ Este repositório é público e seguro: tokens e chaves foram removidos do arquivo (`Chatbot_Limpo_v2.json`).
