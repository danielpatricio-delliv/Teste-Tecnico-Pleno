# Desafio Técnico: Sistema de Confirmação de Chegada e Atribuição de Pedidos

## Objetivo:
Desenvolver uma aplicação web utilizando React para o frontend, React Native para o aplicativo de entregadores, e Node.js para o backend. O sistema deve permitir a notificação do estabelecimento da chegada do entregador, a confirmação da chegada pelo estabelecimento, o cadastro de pedidos pelo estabelecimento após a confirmação, e a visualização da lista de pedidos pelo entregador.

## Requisitos Técnicos:
### Notificação de Chegada:
O entregador, ao chegar ao estabelecimento, deve poder notificar a sua chegada por meio do aplicativo React Native.
O estabelecimento deve receber uma notificação em tempo real (WebSocket ou tecnologia similar) informando a chegada do entregador.
Confirmação da Chegada:
O estabelecimento, ao receber a notificação, deve poder confirmar a chegada do entregador por meio do sistema web React.
A confirmação deve ser registrada no backend.
Cadastro de Pedidos pelo Estabelecimento:
Após a confirmação da chegada, o estabelecimento deve ser redirecionado para uma tela onde possa cadastrar até 3 pedidos destinados ao entregador.
Cada pedido deve conter informações como nome do cliente, endereço de entrega, e itens do pedido.
Acesso à Lista de Pedidos pelo Entregador:
Após a confirmação da chegada, o entregador deve poder acessar a lista de pedidos cadastrados para ele por meio do aplicativo React Native.
A lista deve ser atualizada em tempo real conforme novos pedidos são cadastrados.
Segurança:
Implementar autenticação e autorização para garantir que apenas usuários autenticados possam notificar a chegada, confirmar chegadas, cadastrar pedidos e visualizar a lista de pedidos.
Persistência de Dados:
Utilizar um banco de dados para persistir as informações, garantindo a integridade dos dados e a possibilidade de consulta histórica.
Testes:
Implementar testes automatizados para garantir a robustez e confiabilidade do sistema.
Entrega:
O código-fonte deve ser entregue em um repositório Git público ou compartilhado com acesso ao avaliador.
Incluir instruções claras sobre como executar a aplicação localmente.
Observações:
Levar em consideração boas práticas de desenvolvimento, arquitetura do código, e design responsivo.
Documentar qualquer decisão técnica significativa e assumida durante o desenvolvimento.
Atenção à usabilidade e experiência do usuário.
