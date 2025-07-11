# Análise de fala e Linguagem Natural

Para a resolução deste projeto segui o tutorial do laboratório 03 [Explore Speech in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html) e [Analyze text in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html), seguindo os passos abaixo:

# 1. Criar um projeto no portal Azure AI Foundry

1. Abrir no browser `https://ai.azure.com/managementCenter/allResources` e selecionar a opção `Criar novo`

![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem1.png)

2. Na criação do projeto, no primeiro passo escolher a opção `Recurso do Azure AI Foundry`
   
   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem2.png)

3. No segundo passo, seguir com as seguintes configurações:

  - **Subscrição:** A tua subscrição Azure
  - **Grupo de recursos:** Criar ou selecionar um resource group
  - **Recurso do Azure AI Foundry:** Manter o pré-definido
  - **Região:** East US
    
    ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem3.png)

4. Depois do projeto estar criado, deve ser redirecionado para a página `Descrição geral`

# 2. Speech - Explorar a conversão de fala para texto
   
1. No menu lateral da esquerda, selecionar `Catálogo de modelos`. Procurar pelo modelo `Azure-AI-Speech` e selecioná-lo

   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem4.png)


2. Na página `Azure-AI-Speech` seleciona a opção `Transcrição em tempo real`
   
   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem5.png)

3. Fazer upload do [ficheiro de voz](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/input/WhatAICanDo.m4a)

4. Verificar que a transcrição em tempo real é exatamente igual ao que se ouve no audio.

   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem6.png)


# 3. Analisar texto
   
1. No menu lateral da esquerda, selecionar `Catálogo de modelos`. Procurar pelo modelo `Azure-AI-Language` e selecioná-lo

   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem7.png)

2. Na página `Azure AI Language` seleciona a opção `Extrair informação identificativa do texto`
   
   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem8.png)

3. Verificar a secção `Detalhes` como a informação identificativa vem com informações adicionais, como `Categoria`, `Desfasamento`, `Duração` e `Confiança`. Note que a percentagem de confiança representa a probabilidade do tipo identificado pertencer a essa categoria.

   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem9.png)

4. Alterar para a opção `Extrair expressões-chave`

    ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem10.png)

5. Verificar na secção `Detalhes` as diferentes expressões-chave extraídas

   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem11.png)

6. Alterar para a opção `Resumir conversas`

    ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem12.png)

7. Verificar na secção `Detalhes` o resumo extraído da [amostra](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/input/resumir-texto-input.json)

   ![](https://github.com/CarlaAlves887/analise-fala-linguagem-natural/blob/main/images/Imagem13.png)




