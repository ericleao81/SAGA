\# AGENTS.md — Projeto SAGA



\## Nome do projeto

SAGA - Sistema de Análise e Gestão Administrativa



\## Objetivo

Construir uma solução SaaS corporativa de gestão processual, com foco em:

\- autenticação e autorização

\- usuários, perfis e unidades

\- processos e histórico

\- dashboard gerencial

\- relatórios gerenciais, analíticos e executivos

\- auditoria e rastreabilidade

\- integrações por API

\- observabilidade, segurança e operação sustentada



\## Stack obrigatória

\- Front-end: React + TypeScript + Vite

\- Back-end: Java + Spring Boot

\- Banco de dados: PostgreSQL

\- Autenticação/autorização: Keycloak

\- APIs: REST em JSON com OpenAPI

\- Observabilidade: OpenTelemetry, Prometheus e Grafana

\- Empacotamento: Docker



\## Regras obrigatórias

\- Não criar microserviços sem justificativa formal.

\- Não criar código fora da arquitetura modular.

\- Não validar permissão apenas na interface; toda autorização deve ser aplicada no backend.

\- Toda ação sensível deve gerar trilha de auditoria.

\- Toda exportação deve respeitar filtro, permissão e rastreabilidade.

\- Dashboard gerencial e relatórios são módulos distintos, mas integrados.

\- Não usar segredos hardcoded.

\- Não expor stack trace, token ou dado sensível em mensagens de erro.

\- Não alterar schema, API ou regra de negócio sem registrar claramente a decisão.



\## Forma de trabalho

Antes de implementar qualquer tarefa:

1\. explique o que entendeu;

2\. diga quais arquivos serão alterados;

3\. diga os riscos técnicos;

4\. diga quais testes vai criar ou executar;

5\. diga qual será o critério de pronto.



Ao concluir qualquer tarefa, sempre entregue:

\- resumo do que foi feito

\- arquivos alterados

\- testes executados

\- pendências

\- riscos remanescentes

\- próximo passo recomendado



\## Definition of Done

Uma tarefa só está pronta quando:

\- compila ou executa corretamente;

\- possui testes mínimos adequados;

\- respeita autorização e auditoria;

\- não quebra build, lint ou quality gate;

\- atualiza a documentação essencial.

