# Desafio - Sistema de Entrega
Desafio criado para outro desafio da DevChallenge - https://www.devchallenge.com.br/

<br />
<p align="center">
  <a href="http://www.freepik.com">
    <img src="https://image.freepik.com/free-photo/delivery-uniform-boy-work-courier_1368-6381.jpg" >
  </a>
</p>

## Índice

* [Devchallenge](#devchallenge) 
* [Desafio](#desafio)
* [Techs](#techs)
* [Requisitos](#requisitos)
* [Bônus](#bônus)
* [Compartilhe](#compartilhe)

# Devchallenge
<a href="https://devchallenge.now.sh/"> DevChallenge</a> permite que você evolua suas skills como programador!

# Desafio
O seu desafio é criar um sistema de entrega. Onde há três pontos fixos de entrega e três entregadores.
Você terá que fazer o controle das entregas, porque cada local tem o seu tempo de entrega.

# Techs: 
Você pode utilizar qualquer tecnologia para fazer o desafio.

# Requisitos: 
São três locais de entrega, que tem o nome e a distância medida em minutos. A distância em minutos é a soma de ida e volta do entregador.
1. Há três locais fixos de entrega com as seguintes características: <br/>
  . nome: Ponto A <br/>
  . distância: 4 <br/>
  . nome: Ponto B <br/>
  . distância: 5 <br/>
  . nome: Ponto C <br/>
  . distância: 6 <br/>
  
2. São três funcionários (entregadores), que tem nome, status, início e fim. <br/>
Os status dos funcionários são esperando ou entregando. <br/>
    1. status esperando (o funcionário está esperando um pedido para entregar) esse é o status inicial dos três funcionários quando inicia o sistema. <br/>
    2. status entregando (o funcionário pegou um pedido e está em rota de entrega). <br/>
    
Início e fim são os horários. Exemplo de horário: 17:26:00 <br/>
    1. início é o horário que o funcinário pega o pedido para a entrega. <br/>
    2. fim é o horário de início mais a distância do local. <br/>
    Exemplo: 17:26:00 + 4 minutos que é a distância do Ponto A, ou seja, às 17:30:00 o funcionário deve está de volta para pegar outra entrega.<br/>
  
3. Cada um minuto o sistema deve gerar um pedido aleatório entre os locais fixos. <br/>
4. Quando todos os funcionários estiverem ocupados nas entregas, a mensagem: "Todos os funcionários estão fazendo entregas.", deve ser apresentada. <br/>
5. Se todos os funcionários estão ocupados, os pedidos gerados devem ser armazenados em uma lista de espera, para quando um funcionário voltar da entrega ele pegue o pedido mais antigo. <br/>
6. O sistema deve mostrar as informações das entregas e funcionários na tela. <br/>
Uma amostra de saída está no arquivo saida_exemplo.txt.<br/>

# Bônus

Aqui está uma funcionalidade adicional ao sistema. Tente implementá-la. <br/>

1. Quando todos os funcionários estiverem em entrega e a lista de espera for maior que 3 pedidos, adicione um funcionário temporário para fazer as entregas.<br/>
2. Quando não tiver mais nenhuma entrega na lista de espera, esse funcionário temporário deve ser removido.
3. Esse processo também deve ser apresentado na tela








