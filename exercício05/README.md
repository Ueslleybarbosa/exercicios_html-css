# Aprendendo Checkbox e Radios

Este projeto foi criado para aprender sobre a implementação de checkboxes e radio buttons em HTML. Durante o aprendizado, foram abordados conceitos básicos de formulários HTML e como utilizar esses elementos de input para criar opções interativas para o usuário.

## Descrição

O código abaixo apresenta os trechos específicos utilizados para criar radio buttons e checkboxes em um formulário simples. Através deste exemplo, foi possível entender como definir radio buttons para permitir a seleção única entre opções, e checkboxes para permitir múltiplas seleções.

```html
<!-- Trecho de Radio Buttons -->
<fieldset>
    <legend>Qual é o seu sexo:</legend>

    <input type="radio" name="sexo" id="masculino">
    <label for="masculino">Homem</label>

    <input type="radio" name="sexo" id="feminino" checked>
    <label for="feminino">Mulher</label>
</fieldset>

<!-- Trecho de Checkboxes -->
<fieldset>
    <legend>Qual é o seu esporte favorito:</legend>

    <input type="checkbox" name="basquete" id="basquete">
    <label for="basquete">Basquete</label>

    <input type="checkbox" name="futebol" id="futebol" checked>
    <label for="futebol">Futebol</label>

    <input type="checkbox" name="natacao" id="natacao">
    <label for="natacao">Natação</label>
</fieldset>
