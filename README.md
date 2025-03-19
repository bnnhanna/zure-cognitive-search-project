# Azure Cognitive Search - Indexação de Dados do Blob Storage

## Descrição do Projeto
Este projeto demonstra como configurar o Azure Cognitive Search para indexar dados do Armazenamento de Blob do Azure.

## Pré-requisitos
- Conta no Azure.
- Armazenamento de Blob do Azure com arquivos para indexar.
- Serviço de Azure Cognitive Search.

## Passo a Passo
1. Configurar o Armazenamento de Blob do Azure.
2. Criar uma fonte de dados no Azure Cognitive Search.
3. Configurar o índice e importar os dados.
4. Testar o índice usando o Gerenciador de Pesquisa.

## Exemplos de Consultas
- Pesquisa simples: `search=tecnologia`.
- Filtros: `$filter=metadata_storage_name eq 'documento.pdf'`.

## Referências
- [Documentação do Azure Cognitive Search](https://learn.microsoft.com/en-us/azure/search/).
- [Documentação do Armazenamento de Blob do Azure](https://learn.microsoft.com/en-us/azure/storage/blobs/).
