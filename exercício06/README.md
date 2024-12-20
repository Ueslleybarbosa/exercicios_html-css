# Formulário de Envio de Fotos e Escolha de Cores

Este projeto foi desenvolvido para praticar o uso de elementos de input em HTML, especificamente para adicionar fotos, escolher cores e enviar dados via POST.

## Descrição

Neste projeto, foi criado um formulário HTML que permite aos usuários:

- Selecionar uma cor através de um seletor de cores.
- Medir a satisfação do usuário com um controle deslizante.
- Enviar uma foto utilizando um seletor de arquivos.

Os dados do formulário são enviados para um arquivo PHP (`formulario.php`) utilizando o método POST.

## Aprendizados

Durante a implementação deste código, foi possível aprender:
- Como utilizar o `input` de tipo `file` para permitir o upload de fotos.
- Como utilizar o `input` de tipo `color` para permitir a escolha de cores.
- Como utilizar o `input` de tipo `range` para criar um medidor de satisfação.
- Como enviar os dados do formulário via método POST.
- A importância de verificar o tamanho dos arquivos enviados, garantindo que o arquivo de fotos possui mais de 3 mil bytes.
