# Aplicativo de Cadastro de Clientes

*Este projeto é um aplicativo desenvolvido no Power Apps para gerenciar o cadastro de clientes. Ele permite registrar, visualizar e editar informações de forma integrada com o SharePoint, incluindo suporte ao uso offline.*

---

**Funcionalidades**

- *Cadastro de Clientes:* Adicione novos registros com informações como nome, e-mail e endereço.
- *Edição e Exclusão:* Atualize ou remova dados de clientes existentes.
- *Visualização em Galeria:* Exiba todos os cadastros em uma galeria de fácil navegação.
- *Suporte Offline:* O aplicativo funciona sem conexão. Os dados são sincronizados assim que a internet estiver disponível.
- *Pesquisa:* Busque rapidamente por nome ou e-mail.

---

**Tecnologias Utilizadas**

- *Power Apps:* Criação da interface e lógica do aplicativo.
- *SharePoint:* Armazenamento e sincronização dos dados.
- *Data Sources:* Conectores utilizados para leitura e escrita nas listas do SharePoint.

---

**Estrutura do Projeto**

- Tela Inicial: exibe a galeria com os registros.
- Tela de Cadastro: formulário para inclusão e edição de dados.
- Lógica de Sincronização: uso de `SaveData`, `LoadData` e `Connection.Connected` para controle offline/online.
