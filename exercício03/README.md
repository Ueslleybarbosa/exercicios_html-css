# 📋 Projeto de Formulários HTML

## Descrição
Este projeto demonstra a criação e envio de formulários HTML, com foco em segurança e boas práticas. Abaixo estão os detalhes sobre cada parte do formulário e os atributos usados nos campos `<input>`.

## Explicação das Partes do Formulário

### Tag `<form>`
- **`action`**: Define a URL do servidor que processará os dados do formulário.
- **`method`**: Especifica o método HTTP (GET ou POST) para enviar os dados. POST é mais seguro para dados sensíveis. 🔒
- **`autocomplete`**: Permite que o navegador sugira preenchimentos automáticos. 📝

### Campos de Entrada (`<input>`)
- **Nome**:
  - **`type="text"`**: Campo para entrada de texto. 🖊️
  - **`name`**: Nome do campo usado na submissão dos dados. 🏷️
  - **`id`**: ID único para o campo. 📛
  - **`required`**: Torna o campo obrigatório. 🚨
  - **`autocomplete`**: Sugere preenchimentos automáticos. 🔄
  - **`size`**: Define a largura visível do campo. 📏

- **Sobrenome**:
  - **`type="text"`**: Campo para entrada de texto. 🖊️
  - **`name`**: Nome do campo usado na submissão dos dados. 🏷️
  - **`id`**: ID único para o campo. 📛
  - **`required`**: Campo obrigatório. 🚨
  - **`minlength`**: Número mínimo de caracteres exigidos. 4️⃣
  - **`size`**: Define a largura visível do campo. 📏

- **Senha**:
  - **`type="password"`**: Campo para entrada de senha. 🔐
  - **`name`**: Nome do campo usado na submissão dos dados. 🏷️
  - **`id`**: ID único para o campo. 📛
  - **`required`**: Campo obrigatório. 🚨
  - **`minlength`**: Número mínimo de caracteres exigidos. 8️⃣
  - **`autocomplete`**: Sugere preenchimento automático seguro. 🔄
  - **`size`**: Define a largura visível do campo. 📏

### Botões de Ação
- **`<input type="submit"`**: Botão que submete o formulário. 📤
- **`<input type="reset"`**: Botão que reseta todos os campos do formulário. 🔄

### Considerações de Segurança
- O método POST é preferível para dados sensíveis. 🔒
- Sempre utilize HTTPS para garantir que os dados sejam transmitidos de forma segura.
