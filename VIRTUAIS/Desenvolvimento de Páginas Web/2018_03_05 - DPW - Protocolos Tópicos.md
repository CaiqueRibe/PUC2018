---
tags:
  - DPW
  - Protocolos Topicos
---
O que eh um protocolo?
- Regras e padroes a seguir para que um objetivo possa ser objetido 

Camada de Rede --> IP
Camada de Transporte --> TCP
Camada de Aplicacao --> HTTP

IP --> Identificacao Logica (Enderecos IP)
- Camada responsavel pelo roteamento (como um pacote viaja via a rede)
- Comutacao por pacotes
- Nao pussi garantia de entrega

TCP --> 
- Possui entrega de garantia
- Reetransmissao de dados
- Multiplexazao de portas (Street Number + Apartament Number)
  - 1 Ip, com varias portas para varias aplicacoes
- Controle de Fluxo e congestionamento
  - Fluxo --> Diminuicao de transmissao de pacotes
  - Congestionamento --> ao Enviar um pacote, ao nao receber uma confirmacao de recebimento
    - Vai diminuindo dados auto. para que o congestionamento seja mais facil de ser diminuido

HTTP --> Cliente e Servidor
- Faz a ommunicacao entre um navegador e um servidor na rede
- Um navegador pode solicitar tipos de tarefas differentes, denominadas:
  - METODOS (GET,HEAD,POST)
# Respostas
- 2XY
- 4XY


- Porta 80 --> Referente ao Protocolo HTTP
