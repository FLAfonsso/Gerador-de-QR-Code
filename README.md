# Gerador de QR Code

Aplicação web desenvolvida com HTML, CSS e JavaScript para gerar QR Codes a partir de uma URL ou de um texto informado pelo usuário. O projeto utiliza uma API externa para criar o código e exibi-lo na interface.

## Funcionalidades

- **Geração de QR Code:** cria um QR Code com base no texto ou endereço informado.
- **Geração por botão ou teclado:** permite gerar o código clicando no botão ou pressionando `Enter`.
- **Feedback visual:** altera o texto do botão durante a geração e após o carregamento do QR Code.
- **Interface simples:** apresenta um campo de entrada e uma área para exibir o resultado.
- **Exibição dinâmica:** mostra a área do QR Code após a geração e a oculta quando o campo é esvaziado.

## Tecnologias utilizadas

- **HTML5:** estrutura da aplicação.
- **CSS3:** estilização da interface, posicionamento e transições visuais.
- **JavaScript:** captura de eventos e atualização dinâmica da página.
- **QR Server API:** serviço externo utilizado para gerar os QR Codes.
- **Google Fonts — Roboto:** tipografia da interface.

## Estrutura do projeto

```text
Gerador-de-QR-Code/
├── css/
│   └── styles.css
├── img/
│   └── QRcode.png
├── js/
│   └── scripts.js
├── index.html
└── README.md
```

## Como executar o projeto

Não é necessário instalar dependências para executar a aplicação localmente.

1. Clone o repositório:

   ```bash
   git clone https://github.com/FLAfonsso/Gerador-de-QR-Code.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd Gerador-de-QR-Code
   ```

3. Abra o arquivo `index.html` no navegador.

## Como utilizar

1. Digite uma URL ou um texto no campo de entrada.
2. Clique em **Gerar QR Code** ou pressione `Enter`.
3. Aguarde o carregamento do QR Code na tela.
4. Escaneie o código com a câmera do celular ou com um leitor de QR Code.

## Observações

- A geração do QR Code depende de conexão com a internet, pois os dados são enviados à API externa do QR Server.
- O conteúdo informado é incorporado ao endereço da requisição da API para gerar o código.
- O projeto foi desenvolvido como prática de HTML, CSS e JavaScript, com foco na manipulação do DOM, eventos e integração com uma API.

## Autor

Desenvolvido por Pedro Afonso.
