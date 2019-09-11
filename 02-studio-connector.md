Mudanças ao longo do projeto não afeta meu desenvolvimento.

Tópicos:
- Salesforce -> File
- FTP
- Origem: Database, destino: Salesforce

Passo a passo:

- **Abrir o arquivo `fast-dev-demo.xml`:** apresentar o fluxo
    que inicia com o Salesforce exportando dados para arquivo.

- **Arrastar o FTP:** por requisito de negócio, é necessário obter
    os arquivos por FTP.

- **Remover o Salesforce:** podemos substituir a fonte de dados 
    por outro repositório.

- **Arrastar o Database:** criar uma query SELECT para obter os
    dados a partir de uma tabela.

- **Buscar por Salesforce Create:** inverter a lógica para obter
    dados do BD e inserir no Salesforce.