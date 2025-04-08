**Aplicativo de Cadastro de Clientes**  
Este projeto é um aplicativo desenvolvido no **Power Apps** para gerenciar o cadastro de clientes. O app permite cadastrar, visualizar, editar e excluir registros de clientes, com integração a listas do **SharePoint** e suporte a uso offline.

**🔧 Funcionalidades**  
- **Cadastro de Clientes:** Adicione novos registros com nome, e-mail e endereço.  
- **Edição e Exclusão:** Altere ou remova clientes cadastrados.  
- **Visualização em Galeria:** Navegue pela lista de clientes com interface intuitiva.  
- **Suporte Offline:** Use o app sem conexão à internet. As alterações são armazenadas localmente e sincronizadas automaticamente ao restabelecer a conexão.  
- **Pesquisa:** Localize rapidamente clientes pelo nome ou e-mail.  

**💡 Tecnologias Utilizadas**  
- **Power Apps:** Plataforma de desenvolvimento low-code.  
- **SharePoint:** Armazenamento de dados via listas.  
- **Conexões de Dados:** Integração com listas do SharePoint como fonte de dados.  

**📁 Estrutura do Projeto**  
A estrutura do aplicativo é composta por:  
- **Formulário** de cadastro e edição.  
- **Galeria** com visualização e busca.  
- **Botões** com lógica condicional para salvar localmente ou sincronizar com o SharePoint.  
- Uso de **SaveData** e **LoadData** para funcionalidade offline.
