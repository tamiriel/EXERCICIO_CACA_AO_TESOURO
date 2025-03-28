# Caça ao Tesouro Android

Este é um aplicativo Android nativo desenvolvido com Jetpack Compose e Navigation, onde o usuário navega entre diferentes telas para encontrar um "tesouro". Em cada tela, o usuário recebe uma pista e precisa descobrir a resposta para avançar para a próxima tela até encontrar o tesouro.

## Funcionalidades

- **Tela Inicial (Home)**: Apresenta um botão "Iniciar Caça ao Tesouro", que inicia o jogo.
- **Telas de Pistas (3 telas)**: Cada tela exibe uma pista (charada ou pergunta) com um campo de resposta e dois botões:
  - **Próxima Pista**: Leva o usuário para a próxima tela, caso a resposta esteja correta.
  - **Voltar**: Retorna para a tela anterior.
- **Tela de Tesouro**: Exibe uma mensagem de sucesso, como "Parabéns! Você encontrou o tesouro!", e inclui um botão para retornar à tela inicial e recomeçar o jogo.
- **Tempo de Jogo**: O tempo total que o usuário leva para encontrar o tesouro é rastreado e exibido na tela de tesouro.
- **Respostas**: A navegação só é permitida para a próxima tela se o usuário acertar a resposta correta.

## Tecnologias Utilizadas

- **Jetpack Compose**: Para criar as interfaces de usuário.
- **Navigation Component**: Para gerenciar a navegação entre as telas.
- **Kotlin**: Linguagem de programação utilizada para o desenvolvimento.
- **Android Studio**: Ambiente de desenvolvimento utilizado.
