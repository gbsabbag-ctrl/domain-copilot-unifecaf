# DOMAIN Copilot — Assistente Inteligente de Comunicação Interna e RH

## 📌 Descrição do Projeto
O DOMAIN Copilot é um assistente virtual multimodal integrado via n8n e IA Generativa, desenvolvido para automatizar a redação de e-mails corporativos, comunicados institucionais e atas de reunião para a empresa DOMAIN Tech & People Solutions.

## 🛠️ Tecnologias Utilizadas
* **Automação de Fluxos:** n8n
* **Processamento de IA (LLM / Visão / Áudio):** Google Gemini API
* **Gerenciamento de Contexto / Memória:** Simple Memory (Buffer In-Memory)
* **Plataforma de Atendimento & Canais:** Chatwoot (Integração via Webhook)
* **Ferramenta de Envio de E-mail:** Tool de Envio Integrada (Resend / Gmail API)

## 🚀 Como Executar e Testar
1. Importe o arquivo JSON do workflow para o seu ambiente n8n.
2. Configure as credenciais da API do Gemini e os endpoints do Chatwoot.
3. Configure o Webhook do Chatwoot apontando para o gatilho de entrada do n8n.
4. Envie uma mensagem de texto, áudio ou imagem através da caixa de entrada do Chatwoot.
5. O assistente processará o conteúdo, manterá a retenção de contexto via Simple Memory e retornará a resposta formatada diretamente no canal de atendimento.
