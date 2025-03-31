# Jogo JokenPo

Este é um aplicativo simples de **JokenPo** (Pedra, Papel, Tesoura) desenvolvido utilizando o framework Flutter. O aplicativo permite que o usuário jogue contra o computador, que escolhe uma opção aleatória. O resultado do jogo é exibido diretamente na interface.

## Funcionalidades

- O usuário pode escolher entre **Pedra**, **Papel** ou **Tesoura**.
- O aplicativo gera uma escolha aleatória para o computador.
- O resultado é exibido em uma mensagem (você venceu, você perdeu, ou empate).
- Imagens representando as escolhas do usuário e do aplicativo são exibidas.

## Como Jogar

1. Ao abrir o aplicativo, o usuário verá a opção "Escolha uma opção abaixo".
2. O usuário pode escolher entre **Pedra**, **Papel** ou **Tesoura**, clicando nas respectivas imagens.
3. O aplicativo exibirá a escolha do computador e a mensagem sobre o resultado do jogo (se venceu, perdeu ou empatou).

## Tecnologias Utilizadas

- **Flutter**: Framework de desenvolvimento para apps móveis.
- **Dart**: Linguagem de programação utilizada no Flutter.
- **Random**: Para gerar a escolha aleatória do computador.

## Estrutura do Código

O código consiste na criação de um **StatefulWidget** chamado `Jogo`, onde o estado da escolha do usuário e do aplicativo é mantido e atualizado com base nas interações do usuário.

### Funções principais:

- **_jogar(String escolhaUsuario)**: Recebe a escolha do usuário, gera uma escolha aleatória para o computador, compara as escolhas e atualiza o resultado.
- **build()**: Método de construção da interface gráfica, contendo a visualização das imagens de escolha e a exibição do resultado.

## Imagens Utilizadas

As imagens dos itens **Pedra**, **Papel**, e **Tesoura** são utilizadas para representar as escolhas do usuário e do aplicativo. Essas imagens devem estar na pasta `images` dentro do diretório do projeto.

### Estrutura de Pastas:

images/

  - pedra.png

  - papel.png

  - tesoura.png

  - padrao.png

lib/

  - main.dart (onde o código do aplicativo está implementado)

## Como Executar

1. **Instalar o Flutter**:
   Siga o guia oficial para instalar o Flutter em seu ambiente: [Flutter Installation](https://flutter.dev/docs/get-started/install).

2. **Clonar o Repositório**:
   Clone o repositório para o seu computador:
     git clone https://github.com/FelipeBattarra/app-jokenpo.git
   
3. **Instalar Dependências**: Navegue até o diretório do projeto e instale as dependências:
    cd app-jokenpo
    flutter pub get

4. **Executar o Aplicativo**: Conecte um dispositivo físico ou use um emulador e execute o aplicativo:
    flutter run

