## 🔄 Funcionamento

1. O usuário informa a movimentação de estoque pela interface web.
2. A solicitação é enviada ao n8n por meio de um webhook.
3. O n8n processa os dados, verifica o estoque e executa a operação.

### Entrada
Quando uma lona é recebida, a quantidade é somada ao estoque.

### Saída
Quando uma lona é retirada, o sistema verifica se há quantidade suficiente antes de realizar a saída.

Todas as movimentações são registradas, mantendo um histórico das operações.

## 📦 Tipos de lona

O sistema trabalha com diferentes tamanhos de lona:

- 3x3
- 4x4
- 5x5
- 6x6
- 8x8
- 10x10

## 🔗 Integração com n8n

O workflow da automação está em `n8n/fluxo.json`.

Para utilizá-lo:

1. Abra o n8n.
2. Importe o arquivo `fluxo.json`.
3. Configure as credenciais necessárias.
4. Configure os webhooks utilizados pelo workflow.
5. Verifique as conexões com o Google Sheets.
6. Ative o workflow.

## 🖥️ Interface

A interface está no arquivo `index.html`. Ela pode ser aberta diretamente no navegador ou hospedada em um servidor web.

## 🔐 Segurança

Não armazene no GitHub:

- Senhas
- Tokens
- Chaves de API
- Credenciais
- Dados pessoais de usuários
- Arquivos de banco de dados

O `.gitignore` está configurado para evitar o envio de arquivos sensíveis e bancos SQLite.

## 🚀 Próximas melhorias

- Dashboard com indicadores de estoque
- Alertas de estoque mínimo
- Relatórios de movimentações
- Controle de usuários
- Histórico com filtros
- Melhorias na interface
- Autenticação de acesso

## 👩‍💻 Projeto

Projeto desenvolvido para estudo e prática de automação de processos com n8n, APIs, webhooks e desenvolvimento web.
