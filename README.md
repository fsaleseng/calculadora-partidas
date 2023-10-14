# Calculadora de Partidas Ranqueadas


## Descrição

A Calculadora de Partidas Ranqueadas é um projeto JavaScript que permite aos jogadores calcular seu nível em um jogo ranqueado com base na quantidade de vitórias e derrotas. A função `calcularNivel` aceita as vitórias e derrotas como entrada e fornece o nível do jogador de acordo com as regras definidas.

## O Que Deve Ser Utilizado

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões
- Funções

## Funcionalidades

A Calculadora de Partidas Ranqueadas oferece as seguintes funcionalidades:

- Cálculo do saldo de vitórias.
- Determinação do nível com base no saldo de vitórias e nas regras definidas.

## Como Usar

1. Clone este repositório para o seu computador:

   ```bash
   git clone https://github.com/fsaleseng/calculadora-partidas.git
Navegue até a pasta do projeto:

Abra o arquivo script.js em um ambiente JavaScript ou edite-o em seu editor de código preferido.

No arquivo script.js, você pode chamar a função calcularNivel com a quantidade de vitórias e derrotas do jogador para calcular o nível.

javascript
Copy code
const vitorias = 75;
const derrotas = 25;
const resultado = calcularNivel(vitorias, derrotas);
console.log(resultado);
Altere os valores de vitorias e derrotas conforme necessário.

Execute o arquivo script.js em um ambiente JavaScript, como um navegador ou Node.js.

## Regras de Nível
O nível do jogador é determinado de acordo com as seguintes regras:

Se vitórias for menor do que 10, o nível é "Ferro".
Se vitórias estiver entre 11 e 20, o nível é "Bronze".
Se vitórias estiver entre 21 e 50, o nível é "Prata".
Se vitórias estiver entre 51 e 80, o nível é "Ouro".
Se vitórias estiver entre 81 e 90, o nível é "Diamante".
Se vitórias estiver entre 91 e 100, o nível é "Lendário".
Se vitórias for maior ou igual a 101, o nível é "Imortal".

## Contribuições
Contribuições são bem-vindas! Se você deseja aprimorar este projeto, sinta-se à vontade para criar um fork do repositório, fazer as alterações desejadas e enviar um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para mais detalhes.





