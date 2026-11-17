# Bot Supervisor de TI — IA901

**Autor:** Kaiky Yoshio Ono Marins  
**Portfólio:** [kaikysec.vercel.app](https://kaikysec.vercel.app/)  
**Categoria:** Python · Streamlit · Help Desk · IA  
**Status:** Projeto de estudo

## Visão geral

Aplicação Streamlit que apresenta um assistente para triagem de problemas de TI. A pessoa descreve a dificuldade e o fluxo usa um modelo de IA para organizar a solicitação e apoiar a abertura de chamados com prioridade e departamento.

## Problema e proposta

Solicitações de suporte chegam com descrições diferentes e, muitas vezes, sem informações organizadas. O protótipo explora como uma interface conversacional pode estruturar o relato para facilitar a triagem.

## Recursos identificados

- Interface de chat para relatar problemas.
- Fluxo de abertura de chamados.
- Classificação de prioridade e departamento.
- Histórico de conversa na interface.
- Painel com informações de uso do modelo.

## Tecnologias

- Python
- Streamlit
- Pandas
- SDK compatível com OpenAI / Azure AI Foundry, conforme configuração do deployment

## Como executar

1. Crie um ambiente virtual Python.
2. Instale as dependências de `requirements.txt`.
3. Configure localmente o endpoint, o deployment e as credenciais exigidas pelo ambiente de IA.
4. Execute `streamlit run Bots_IA901.py`.

## Segurança e limitações

As credenciais do provedor devem ser configuradas por variáveis de ambiente ou Secrets. Não publique chaves no código ou no Git. Como o resultado depende de um modelo de IA, a prioridade e o departamento sugeridos devem ser revisados por uma pessoa responsável pelo atendimento.

## O que este projeto demonstra

- Criação de uma interface conversacional para um fluxo de suporte.
- Estruturação de informações de chamados.
- Integração de uma aplicação Python com um serviço de IA.

© 2026 Kaiky Yoshio Ono Marins.
