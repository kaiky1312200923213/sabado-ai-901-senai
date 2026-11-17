# Bot Supervisor de TI — IA901

**Autor:** Kaiky Yoshio Ono Marins  
**Categoria:** Python · Streamlit · Help Desk · IA  
**Status:** Projeto de estudo

## Visão geral

Aplicação Streamlit que apresenta um assistente para triagem de problemas de TI. O usuário descreve a dificuldade, e o fluxo usa um modelo de IA para avaliar a solicitação e, quando apropriado, abrir um chamado com descrição, prioridade e departamento.

## Recursos identificados

- Interface de chat para relatar problemas.
- Função de abertura de chamados de TI.
- Registro de prioridade e departamento.
- Painel de controle com informações de uso do modelo.
- Histórico de conversa na interface.

## Tecnologias

- Python
- Streamlit
- Pandas
- SDK OpenAI-compatível / Azure AI Foundry (configuração do deployment)

## Como executar

1. Crie um ambiente virtual Python.
2. Instale as dependências de `requirements.txt`.
3. Configure localmente o endpoint, deployment e credenciais exigidos pelo ambiente de IA.
4. Execute `streamlit run Bots_IA901.py`.

Não coloque chaves de acesso no código ou no Git. Use variáveis de ambiente ou os Secrets do serviço de hospedagem.

© 2026 Kaiky Yoshio Ono Marins.