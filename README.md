

Eles apareceram por causa da formatação.



\### Faça assim



No `README.md`, deixe \*\*exatamente\*\* esta parte:



```markdown

\## 🔄 Funcionamento



O usuário utiliza a interface web para informar a movimentação do estoque.



A solicitação é enviada para o n8n através de um webhook.



O n8n processa as informações, verifica o estoque e realiza a operação correspondente.



\### Entrada



Quando uma lona é recebida, a quantidade é adicionada ao estoque.



\### Saída



Quando uma lona é retirada, o sistema verifica se existe quantidade suficiente disponível antes de realizar a saída.



As movimentações também são registradas para manter um histórico das operações.



\## 📦 Tipos de lona



O sistema foi desenvolvido para trabalhar com diferentes tamanhos de lona, como:



\- 3x3

\- 4x4

\- 5x5

\- 6x6

\- 8x8

\- 10x10



\## 🔗 Integração com n8n



O workflow utilizado na automação está localizado em:



`n8n/fluxo.json`



Para utilizar o workflow:



1\. Abra o n8n.

2\. Importe o arquivo `fluxo.json`.

3\. Configure as credenciais necessárias.

4\. Configure os Webhooks utilizados pelo workflow.

5\. Verifique as conexões com o Google Sheets.

6\. Ative o workflow.



\## 🖥️ Interface



A interface do sistema está localizada no arquivo:



`index.html`



Ela pode ser aberta em um navegador ou hospedada em um servidor web.



\## 🔐 Segurança



Não devem ser armazenados no GitHub:



\- Senhas

\- Tokens

\- Chaves de API

\- Credenciais

\- Dados pessoais de usuários

\- Arquivos de banco de dados



O arquivo `.gitignore` foi configurado para evitar o envio de arquivos sensíveis e bancos SQLite.



\## 🚀 Próximas melhorias



Algumas melhorias que podem ser implementadas futuramente:



\- Dashboard com indicadores de estoque

\- Alertas de estoque mínimo

\- Relatórios de movimentações

\- Controle de usuários

\- Histórico com filtros

\- Melhorias na interface

\- Autenticação de acesso



\## 👩‍💻 Projeto



Projeto desenvolvido para estudo e prática de automação de processos utilizando n8n, APIs, Webhooks e desenvolvimento web.

