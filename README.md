# Repositório do Índice de Pesquisa do Azure AI

Este repositório demonstra como criar um índice de pesquisa do Azure AI para extrair insights de avaliações de clientes. Ele abrange os seguintes passos:

## Cenário

Imagine que você trabalha para a Fourth Coffee, uma cadeia nacional de cafés. Você foi solicitado a ajudar a construir uma solução de mineração de conhecimento que facilite a busca por insights sobre as experiências do cliente. Você decide criar um índice de Pesquisa de IA do Azure usando dados extraídos de avaliações de clientes.

## Recursos do Azure Necessários
- **Azure AI Search:** Gerencia indexação e consulta.
- **Serviços de IA do Azure:** Fornece serviços de IA para enriquecimento de dados.
- **Conta de Armazenamento do Azure:** Armazena documentos brutos e outras coleções.

## Criando Recurso de Pesquisa do Azure AI
1. Faça login no portal Azure.
2. Crie um recurso de Pesquisa do Azure AI com preço básico.
3. Configure as configurações necessárias e revise a implantação.

## Criando Recurso de Serviços de IA do Azure
1. Crie um recurso de Serviços de IA do Azure na mesma região do Azure AI Search.
2. Configure as configurações e revise a implantação.

## Criando Conta de Armazenamento do Azure
1. Crie uma conta de Armazenamento do Azure com contêineres de blob para armazenar documentos.
2. Configure as configurações de acesso para permitir acesso anônimo ao blob.

## Carregando Documentos no Armazenamento do Azure
1. Baixe e extraia as avaliações de café fornecidas.
2. Faça upload dos documentos extraídos para um contêiner de blob no Armazenamento do Azure.

## Indexação de Documentos
1. Use o portal Azure AI Search para importar dados do Armazenamento de Blob do Azure.
2. Configure o indexador para extrair metadados e conteúdo dos documentos.
3. Habilite habilidades cognitivas para enriquecer os dados.
4. Salve os enriquecimentos em uma loja de conhecimento.

## Consultando o Índice
1. Use o Search Explorer para escrever e testar consultas.
2. Consulte todos os documentos e filtre por localização e sentimento.

## Revisando a Loja de Conhecimento
1. Explore a loja de conhecimento para visualizar dados enriquecidos persistidos como projeções e tabelas.
2. Analise as palavras-chave capturadas e metadados de imagem extraídos das avaliações.

Este repositório fornece um guia abrangente para configurar um índice de pesquisa do Azure AI para extrair insights de avaliações de clientes. Siga as instruções detalhadas para implementar a solução de forma eficaz.
