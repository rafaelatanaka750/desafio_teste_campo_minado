**Rafaela Tanaka Cardoso 24062611-2**

**Vitor Hugo da Costa 23234248-2**


# Campo Minado – Casos de Teste

## Concepção do Desafio

O desafio consiste na criação de casos de teste para o jogo Campo Minado, utilizando JavaScript e o framework Jest.
O jogo possui um tabuleiro de 18 linhas por 14 colunas, totalizando 252 células, com 40 bombas espalhadas pelo tabuleiro.

O objetivo é testar as principais funcionalidades do jogo e verificar se elas estão funcionando corretamente, considerando situações que podem acontecer durante uma partida.

## Funcionamento dos Casos de Teste

Os casos de teste foram criados para simular diferentes situações do jogo. Cada teste realiza uma ação e verifica se o resultado obtido corresponde ao resultado esperado.

Foram considerados testes para:

- Criação do tabuleiro e verificação do seu tamanho.
- Quantidade de bombas e células sem bombas.
- Contagem de bombas nas células vizinhas.
- Revelação de células seguras.
- Revelação de células que possuem bombas.
- Marcação e desmarcação de células.
- Verificação de vitória do jogador.
- Tentativas de acessar posições inválidas do tabuleiro.

Os testes são executados utilizando o Jest, que verifica automaticamente se cada funcionalidade apresenta o resultado esperado. Caso o resultado seja diferente, o teste indica que houve uma falha.

## Como executar os testes

Para executar os testes, é necessário ter o Node.js instalado.

Instale o Jest utilizando o comando:

```bash
npm install --save-dev jest
```

Depois, execute:

```bash
npx jest
```

## Resultado Esperado

Ao finalizar a execução, esperamos que todos os casos de teste sejam aprovados, mostrando que as funcionalidades verificadas estão apresentando os resultados esperados.
