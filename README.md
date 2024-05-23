<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2024/04/logo_github.png" width="240" />
<p align="center">Seja bem-vindo ao Guia Perfex CRM 🚀</p>
</p>
  
<p align="center"> 
<a href="https://hubconnect.top" target="_blank">👉 Participe da Comunidade HubConnect 👈</a>
</p>

<hr />
<hr />


### Manual integração CRM PERFEX SASS

Acesse seu perfex CRM

https://seudominioperfexcrm/admin/leads/statuses

Clique no botão `Novo Status do Lead` preencha as informações e no campo `Ordem / Posição` deixe definido com o número.

Agora acesse a url abaixo:

https://seudominioperfexcrm/admin/leads/sources

Clique no botão `Nova Fonte` defina um nome e salve

### Baixe modulo API Perfex desse Github

Vá até a opção: `Definições>Módulos` faça upload do módulo baixado, instale e ative.

Acesse a url abaixo:

https://seudominioperfexcrm.com.br/admin/api/api_management

Crie nova chave de API clicando no botão `New User`, preencha as informações e salve!

### Acesse seu N8N e importe os seguintes workflows:

- PerfexCRM
- CadastroPerfexcrm
- QuepasaAutomatic
- AjustaContato

### Configure as credenciais do Google Sheets e Postgres!

Crie uma planilha no Google Sheets com as seguintes colunas:
- Conta
- Url Perfex
- Token

### Acesse seu Chatwoot, vá até contatos e procure pelo BOT, envie uma nova mensagem da seguinte forma:

```bash
/perfexcrm

Url: https://seudominioperfexcrm.com.br
Token: Sua Chave de de API Perfexcrm
```
