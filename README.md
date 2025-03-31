Jogo JokenPo
Este é um aplicativo simples de Pedra, Papel e Tesoura (JokenPo) desenvolvido com o framework Flutter. O app permite que o usuário jogue contra o computador, que faz uma escolha aleatória. O resultado da partida é exibido diretamente na interface.

Funcionalidades
O jogador pode selecionar entre Pedra, Papel ou Tesoura.

O aplicativo gera automaticamente uma escolha aleatória para o computador.

O resultado da partida (vitória, derrota ou empate) é mostrado na tela.

As escolhas do usuário e do aplicativo são representadas por imagens.

Como Jogar
Ao abrir o aplicativo, será exibida a mensagem "Escolha uma opção abaixo".

O usuário pode selecionar Pedra, Papel ou Tesoura clicando nas imagens correspondentes.

O aplicativo exibirá a escolha do computador e mostrará o resultado (se venceu, perdeu ou empatou).

Tecnologias Utilizadas
Flutter: Framework para desenvolvimento de aplicativos móveis.

Dart: Linguagem de programação usada no Flutter.

Random: Utilizado para gerar a escolha aleatória do computador.

Estrutura do Código
O código é baseado na criação de um StatefulWidget chamado Jogo, onde o estado do jogo é armazenado e atualizado conforme as interações do usuário.

Principais funções:
_jogar(String escolhaUsuario): Recebe a opção escolhida pelo jogador, gera uma escolha aleatória para o computador, compara os resultados e atualiza o estado do jogo.

build(): Responsável por construir a interface gráfica, exibindo as imagens das opções disponíveis e o resultado da rodada.



## Como Executar

1. **Instalar o Flutter**:
   Siga o guia oficial para instalar o Flutter em seu ambiente: [Flutter Installation](https://flutter.dev/docs/get-started/install).

2. **Clonar o Repositório**:
   Clone o repositório para o seu computador:
     git clone https://github.com/IgorTakagui/Jokenpo
   
3. **Instalar Dependências**: Navegue até o diretório do projeto e instale as dependências:
    cd app-jokenpo
    flutter pub get

4. **Executar o Aplicativo**: Conecte um dispositivo físico ou use um emulador e execute o aplicativo:
    flutter run

![image](https://github.com/user-attachments/assets/d4f43380-ce20-4c20-863e-da50853709fa)
