# 📋 Formulários HTML

## Métodos de Envio de Formulários

### Método GET
🔍 O método GET envia os parâmetros do formulário na URL, o que pode ser arriscado para dados sensíveis porque essas informações ficam visíveis na barra de endereços do navegador e podem ser facilmente armazenadas nos logs do servidor ou no histórico do navegador.

### Método POST
🔒 O método POST envia os dados no corpo da requisição HTTP, e eles não aparecem na URL. Isso oferece uma camada extra de segurança para dados sensíveis. No entanto, as informações ainda podem ser interceptadas se a conexão não for segura (por exemplo, sem HTTPS).

## 🛡️ Considerações de Segurança
🔐 Mesmo usando POST, as informações podem ser vistas nos headers da requisição HTTP. Portanto, é essencial garantir que a conexão seja segura usando HTTPS para criptografar os dados durante a transmissão. Isso protege as informações contra interceptações maliciosas.

### Resumo
- **GET**: Parâmetros visíveis na URL. 🚫 Não recomendado para dados sensíveis.
- **POST**: Dados enviados no corpo da requisição, ✅ mais seguro para dados sensíveis, mas deve ser usado com HTTPS para criptografia.

### 🚀 Limite do Método GET
O método GET aceita até 3.000 bytes.
