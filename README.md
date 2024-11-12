# Specker Smash

Specker Smash é um aplicativo de edição de imagem que permite aos usuários recortar, inverter e adicionar emojis às suas fotos, além de salvar as edições diretamente na galeria.

## Desenvolvido por

**Jhan Houzer**

## Funcionalidades

- **Recorte de Imagens**: Selecione e recorte partes específicas de suas fotos.
- **Inversão Horizontal e Vertical**: Inverta suas imagens para criar efeitos únicos.
- **Adição de Emojis**: Personalize suas imagens com uma variedade de emojis.
- **Abertura e Salvamento**: Abra imagens da galeria e salve as edições de volta na galeria.
- **Interface Intuitiva**: Navegação fácil e acessível para todos os usuários.

## Tecnologias Usadas

- **React Native**: Para desenvolvimento de aplicativos móveis.
- **Expo**: Para funcionalidades como seleção de imagens e acesso à biblioteca de mídia.
- **Bibliotecas Utilizadas**:
  - `react-native`: Componentes básicos para o aplicativo.
  - `expo-image-picker`: Para selecionar imagens da galeria.
  - `react-native-gesture-handler`: Para manipulação de gestos.
  - `expo-media-library`: Para gerenciar a biblioteca de mídia.
  - `react-native-view-shot`: Para capturar imagens da tela.
  - `expo-image`: Para manipulação de imagens.
  - `dom-to-image`: Para converter elementos DOM em imagens.
  
- **Componentes Personalizados**:
  - `Button`: Componente de botão reutilizável.
  - `ImageViewer`: Componente para visualizar imagens.
  - `IconButton`: Botão com ícone.
  - `CircleButton`: Botão circular.
  - `EmojiList`: Lista de emojis disponíveis.
  - `EmojiPicker`: Componente para selecionar emojis.
  - `EmojiSticker`: Componente para adicionar emojis como adesivos.

## Instalação

Siga os passos abaixo para instalar e executar o Specker Smash localmente:

1. Clone o repositório:

   ```bash
   git clone https://github.com/jandesson-moraes/stickersmash-jhanhouzer.git

## Get started

1. Instale as dependências:

   ```bash
   npm install
   ```

2. Inicie o aplicativo:

   ```bash
    npx expo start
   ```

No terminal, você encontrará opções para abrir o aplicativo em um:

- [Desenvolvimento Build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Emulador Android](https://docs.expo.dev/workflow/android-studio-emulator/)
- [Simulador iOS](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo
