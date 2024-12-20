# 📋 Formulários HTML: `select`, `option` e `datalist`

## `select`
A tag `<select>` é usada para criar um menu suspenso em um formulário HTML. Ela permite que o usuário selecione uma das opções definidas.

- **Uso:** Ideal para permitir a escolha entre várias opções predefinidas.
- **Estrutura:** Contém múltiplas tags `<option>` que representam as opções disponíveis.

## `option`
A tag `<option>` define uma opção que pode ser selecionada dentro de um menu `<select>`. Ela é usada para listar cada item dentro do menu suspenso.

- **Uso:** Cada `<option>` dentro de um `<select>` representa uma escolha que o usuário pode fazer.
- **Atributos importantes:** `value` (o valor enviado ao servidor) e `selected` (marca a opção como pré-selecionada).

## `datalist`
A tag `<datalist>` é usada para fornecer uma lista de opções predefinidas para um campo de entrada (`input`). Quando o usuário começa a digitar no campo, as opções definidas no `<datalist>` aparecem como sugestões de autocompletar.

- **Uso:** Facilita a entrada de dados ao sugerir opções conforme o usuário digita.
- **Estrutura:** Contém múltiplas tags `<option>`, mas neste caso, as `<option>` servem como sugestões em vez de serem enviadas diretamente ao servidor.

Essas funcionalidades melhoram a interatividade e a usabilidade dos formulários HTML, oferecendo diversas maneiras de coletar informações dos usuários de forma estruturada e intuitiva.
