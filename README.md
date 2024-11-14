# Classificador de Nível de Herói

Este projeto faz parte de um curso da [DIO](https://github.com/digitalinnovationone), com aulas ministradas por [Felipe Aguiar](https://github.com/felipeAguiarCode).

## Objetivo

O objetivo deste desafio é criar uma aplicação que classifica heróis em diferentes níveis com base na quantidade de XP (experiência) que possuem. O programa realiza a classificação do herói em uma das seguintes categorias:

- **Ferro** (XP menor que 1.000)
- **Bronze** (XP entre 1.001 e 2.000)
- **Prata** (XP entre 2.001 e 5.000)
- **Ouro** (XP entre 5.001 e 7.000)
- **Platina** (XP entre 7.001 e 8.000)
- **Ascendente** (XP entre 8.001 e 9.000)
- **Imortal** (XP entre 9.001 e 10.000)
- **Radiante** (XP maior ou igual a 10.001)

## Descrição

A aplicação tem duas versões:
1. **Versão Node.js**: A versão inicial, em `classificador.js`, gera um herói aleatório e classifica o nível dele com base em um valor de XP também gerado aleatoriamente. Basta rodar o arquivo com o comando `node classificador.js` para visualizar o resultado no terminal.
   
2. **Versão Web (HTML + JavaScript)**: Uma versão melhorada, com uma interface gráfica, permite ao usuário selecionar um herói e informar o XP para ver a classificação do herói em tempo real. O resultado é mostrado de forma interativa em uma página web.

### Arquivos do projeto:

- **classificador.js**: Implementação em JavaScript puro para rodar no terminal.
- **index.html**: Página HTML com a interface do usuário para a versão web.
  
## Como usar

### Versão Node.js

1. Clone este repositório em seu computador.
2. Navegue até a pasta onde o repositório foi clonado.
3. Execute o comando:
   ```bash
   node classificador.js

### Versão Interativa (index.html)
1. Abra o arquivo `index.html` em um navegador da web.
2. Selecione um herói da lista suspensa e insira a quantidade de XP.
3. Clique em "Classificar Nível" para ver o resuldado da classificação.

## Tecnologias usadas:

- HTML
- CSS
- JavaScript