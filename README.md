# Graph-Tutorial

Repositório contendo um tutorial sobre grafos, criado para a atividade 1 da disciplina de **Algoritmos e Estrutura de Dados II**.

## Conteúdo do Repositório

Este repositório inclui:
- Um **notebook Jupyter** contendo um tutorial no formato "Hands On" sobre o uso do **NetworkX** e a criação de grafos.
- Arquivos auxiliares utilizados no processo de geração do notebook.

## Geração do Notebook

O notebook foi criado com o auxílio da ferramenta de IA **ChatGPT**, utilizando o modelo **o3-mini** com a opção **"Refletir"** ativada, para obter a melhor resposta possível.

Três arquivos foram enviados como contexto para a IA:
1. **Um PDF contendo os capítulos 2, 3, 6 e 7 do livro _The Atlas For The Aspiring Network Scientist_**, utilizados para contextualizar o tema do notebook.
2. **Um notebook Jupyter** com um tutorial do NetworkX, que serviu como base para a criação do novo tutorial.
3. **Uma imagem** descrevendo a metodologia de aprendizado que deveria ser aplicada no tutorial.

## Estrutura do Prompt Utilizado

O prompt utilizado seguiu o formato recomendado para uso eficiente do ChatGPT, incluindo:
- **Objetivo**
- **Tipo de retorno esperado**
- **Restrições**
- **Contextualização**

### Prompt Utilizado:
```text
Eu quero criar um novo tutorial Notebook Jupyter no estilo "Hands On". O tutorial deve ter seções de explicação, seções de código para serem executados e exemplos para que o usuário possa treinar.

Para isso, retorne um notebook Jupyter.

Crie um notebook diferente do que foi enviado e tome cuidado para que os exemplos estejam corretos e funcionando.

Para contexto: Utilize o notebook (NetworkElementsI.ipynb) enviado como inspiração para o novo tutorial que será criado. Também use as informações disponíveis nos capítulos do PDF enviado (livrocut.pdf) para desenvolver o novo tutorial. Utilize também a imagem enviada como base para a metodologia de aprendizado que será usada no tutorial.
````

## Localização dos Arquivos

- **O notebook gerado encontra-se na main do repositório.**
- **Os arquivos utilizados para sua geração estão armazenados na pasta "prompt".**
