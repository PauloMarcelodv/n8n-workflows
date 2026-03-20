n8n Workflows — Automação de Processos
Repositório com workflows desenvolvidos no n8n para automação de processos e integração entre sistemas externos.

Workflows disponíveis
Automação de Processo Seletivo
Workflow completo para automação de um processo seletivo, desde o recebimento de candidaturas até o agendamento de entrevistas.
Fluxo:
Formulário de candidatura
       ↓
Validação de cargo e pretensão salarial
       ↓
Registro do candidato no Google Sheets
       ↓
Envio automático de e-mail (aprovado/reprovado)
       ↓
Agendamento de entrevista via Google Calendar
Funcionalidades:

Recebimento de dados via formulário
Validação de cargo e filtro por pretensão salarial
Registro automático de candidatos em planilha (Google Sheets)
Envio automático de e-mails personalizados via Gmail
Agendamento de entrevistas via Google Calendar

Integrações:
ServiçoUson8nOrquestração do workflowGmailEnvio de e-mails automáticosGoogle SheetsRegistro e controle de candidatosGoogle CalendarAgendamento de entrevistas

Como importar no n8n

Acesse sua instância do n8n
Clique em Workflows > Import from file
Selecione o arquivo .json do workflow desejado
Configure as credenciais dos serviços Google (Gmail, Sheets, Calendar)
Ative o workflow


As credenciais Google precisam ser configuradas individualmente em Settings > Credentials no n8n.


Pré-requisitos

n8n instalado (local, Docker ou cloud)
Conta Google com APIs habilitadas (Gmail, Sheets, Calendar)
Credenciais OAuth2 configuradas no n8n


Aprendizados

Automação de processos com n8n
Integração com APIs do Google via OAuth2
Modelagem de regras de negócio em workflows visuais
Manipulação de dados estruturados entre sistemas

