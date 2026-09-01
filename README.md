# Radar Acadêmico com n8n e OpenAlex

Fluxo automatizado para recuperação, organização e envio periódico
de publicações científicas obtidas por meio da API do OpenAlex.

## Funcionalidades

- execução semanal;
- 16 categorias temáticas;
- consultas em português e inglês;
- janela móvel de dez dias;
- recuperação de metadados do OpenAlex;
- controle de registros processados;
- geração de relatório em HTML;
- envio por e-mail.

## Requisitos

- Docker;
- Docker Compose;
- chave da API do OpenAlex;
- credencial de serviço de e-mail compatível com o n8n.

## Instalação

1. Clone este repositório.
2. Execute `docker compose up -d`.
3. Acesse `http://localhost:5678`.
4. Importe o arquivo `workflow/radar-academico-openalex.json`.
5. Configure as credenciais do OpenAlex e do serviço de e-mail.
6. Revise o destinatário antes de ativar o fluxo.

## Segurança

As credenciais e os endereços pessoais não estão incluídos no repositório.

## Artigo

Artefato desenvolvido para o SIRC 2026.