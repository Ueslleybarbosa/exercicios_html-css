# 📋 Formulário de Registro

Este é um exemplo de formulário HTML que desenvolvi para aprender e praticar a validação de campos de email e telefone, além de explorar a funcionalidade do atributo `pattern`.

## 🎓 Aprendizado

### 📧 Email
- **Campo de Email:** Usei o campo `input` com o tipo `email` para garantir que os usuários insiram um endereço de email válido.
- **Atributo `required`:** Tornei o campo obrigatório para garantir que nenhuma submissão seja feita sem um email válido.

### 📞 Telefone
- **Campo de Telefone:** Criei um campo `input` com o tipo `tel` para números de telefone.
- **Formato Brasileiro:** Adaptei o formato para seguir o padrão brasileiro, incluindo o DDD e o dígito 9 adicional.
- **Uso do `pattern`:** Utilizei a expressão regular para validar o formato do número de telefone, garantindo que siga o padrão estabelecido.

### 🔍 Atributo `pattern`
- **Expressão Regular (Regex):** Aprendi a usar expressões regulares para validar padrões específicos de entrada de dados. No caso, para números de telefone no formato brasileiro.
