Caça ao Tesouro com Navegação entre Telas
Este é um aplicativo Android nativo desenvolvido utilizando Jetpack Compose, com o objetivo de criar uma experiência de navegação entre várias telas. O usuário deve navegar por diferentes telas para encontrar um "tesouro" escondido, resolvendo pistas em cada uma delas.

Funcionalidades
O aplicativo é composto por várias telas e recursos, conforme descrito abaixo:

1. Tela Inicial (Home)
Exibe um botão "Iniciar Caça ao Tesouro".

Ao clicar no botão, o usuário é redirecionado para a primeira tela de pista.

2. Telas de Pistas (3 telas)
Exibe uma pista para o usuário, como uma charada ou uma pergunta simples.

O usuário deve responder corretamente para continuar.

Cada tela apresenta dois botões:

Próxima Pista: Leva o usuário para a próxima tela de pista.

Voltar: Retorna o usuário para a tela anterior.

3. Tela de Tesouro
Exibe uma mensagem de sucesso: "Parabéns! Você encontrou o tesouro!".

Inclui um botão para voltar à tela inicial e recomeçar a caça ao tesouro.

Funcionalidades Extras
Animações de Transição: Animações de transição entre as telas para melhorar a experiência do usuário.

Rastreamento de Tempo: O tempo total gasto pelo usuário para encontrar o tesouro é rastreado e exibido na tela de tesouro.

Validação de Respostas: Em cada tela de pista, há um campo de texto para que o usuário insira sua resposta. O botão "Próxima Pista" só é habilitado se a resposta estiver correta.

Tecnologias Utilizadas
Jetpack Compose: Framework moderno para criação de interfaces nativas em Android.

Navigation Component: Para gerenciar a navegação entre as telas do aplicativo.

Kotlin: Linguagem de programação usada para desenvolver o aplicativo.
