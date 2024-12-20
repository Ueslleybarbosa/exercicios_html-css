# Formulário de Soma de Números

Este é um simples formulário HTML que permite ao usuário inserir dois números e ver a soma desses números em tempo real.

## Estrutura do Código

O código é composto pelas seguintes seções:

1. **Cabeçalho HTML**: Define o tipo de documento, a linguagem da página (`pt-br`), o conjunto de caracteres (`UTF-8`) e o título da página.

2. **Corpo HTML**:
   - `form`: Um formulário que envia dados para `formulario.php` usando o método `get`.
   - **Campos de Entrada**:
     - `Número 01`: Um campo de entrada para o primeiro número (`n1`) com um valor máximo de 100.
     - `Número 02`: Um campo de entrada para o segundo número (`n2`) com um valor máximo de 100.
   - **Saída**:
     - `Soma`: Um campo de saída que exibe a soma dos dois números inseridos.
   - **Botões**:
     - `Enviar`: Um botão para enviar o formulário.
     - `Limpar`: Um botão para resetar os campos do formulário.

## Funcionalidade

- O atributo `oninput` nos campos de entrada é usado para atualizar o valor da soma em tempo real.
- A soma é calculada usando `Number(n1.value) + Number(n2.value)` e exibida no elemento `output` com o id `isoma`.

## Uso

1. Abra o arquivo HTML em um navegador.
2. Insira dois números nos campos "Número 01" e "Número 02".
3. Veja a soma ser atualizada automaticamente no campo "Soma".
4. Use o botão "Enviar" para enviar os dados ou "Limpar" para resetar o formulário.

---

Este formulário é útil para demonstrações simples de manipulação de formulário e cálculos em tempo real utilizando HTML e JavaScript.
