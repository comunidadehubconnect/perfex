<p align="center">
	<img src="https://github.com/EngajamentoFlow/perfexquepasa/blob/main/perfex-crm-logo.jpg" alt="Quepasa-logo" width="100" />	
	<p align="center">O Perfex CRM é uma plataforma completa de gestão de relacionamento com o cliente, que oferece recursos para vendas, suporte, faturamento e muito mais.</p>
</p>
<hr />
<p align="left">
</p>
<hr />
<p align="left">
	<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
	<span>Grupo WhatsaAPP Chatwoot : </span>
	<a href="https://chat.whatsapp.com/CLKge3hmHmmBcIL04mBzmT" target="_blank">Grupo</a>
<hr />
<hr />

### Manual integração CRM PERFEX

Acesse seu perfex CRM

https://seudominio/admin/leads/statuses

Clique no botão `Novo Status do Lead` preencha as informações e no campo `Ordem / Posição` deixe definido com o número.

Agora acesse a url abaixo:

https://seudominio/admin/leads/sources

Clique no botão `Nova Fonte` defina um nome e salve

### Baixe modulo API Perfex desse Github

Vá até a opção: `Definições>Módulos` faça upload do módulo baixado, instale e ative.

Acesse a url abaixo:

https://seudominio.com.br/admin/api/api_management

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

Pronto tudo Funcionando 👍✅
