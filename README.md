# Projeto de Formulário de Pagamento

Este projeto consiste em uma interface simples de pagamento que permite ao usuário escolher entre as opções de pagamento via PIX ou cartão de crédito. Ele também inclui a funcionalidade de cálculo automático do valor total com base no número de parcelas escolhidas e exibe uma mensagem de sucesso após a realização do pagamento.

### Funcionalidades

- Seleção do tipo de pagamento: O usuário pode selecionar entre PIX ou cartão de crédito.
- Cálculo de parcelas: Caso o usuário selecione a opção de pagamento com cartão de crédito, o sistema calcula automaticamente o valor total, aplicando uma taxa de 5% para 4 parcelas ou 10% para 5 parcelas.
- Validação do número do cartão: Exibe a bandeira do cartão com base nos primeiros dígitos (Mastercard, Elo ou uma mensagem de erro caso o cartão seja inválido).
- Exibição de mensagem de sucesso: Após o clique no botão de pagamento, uma mensagem de confirmação é exibida por 5 segundos.

### Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- index.html: Estrutura HTML do formulário de pagamento.
- styles.css: Arquivo CSS que contém o estilo da página, garantindo uma interface amigável e responsiva.
- script.js: Arquivo JavaScript responsável por toda a lógica do sistema, como exibição de parcelas, cálculo do valor total e validação do número do cartão.
- Imagens: As imagens das bandeiras dos cartões (Mastercard, Elo) estão no diretório image/ e são exibidas dinamicamente com base no número inserido.

### Tecnologias Utilizadas

- HTML5: Para a estrutura do conteúdo.
- CSS3: Para estilização e design da interface do usuário.
- JavaScript: Para manipulação do DOM, cálculos e validações.

### Como Executar o Projeto

1. Clone o repositório para sua máquina local:

```bash Copiar código
git clone https://github.com/seu-usuario/projeto-pagamento.git
```

2. Abra o arquivo `index.html` em seu navegador.
