# API de Produtos - React Native

![React Native](https://img.shields.io/badge/React%20Native-0.76.7-blue.svg)
![Expo](https://img.shields.io/badge/Expo-~52.0.37-black.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Um aplicativo móvel desenvolvido em React Native utilizando Expo, que consome uma API de produtos para exibir uma lista de itens com navegação para detalhes. Este projeto demonstra habilidades em desenvolvimento mobile, consumo de APIs, navegação e design de interfaces.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Pré-requisitos](#pré-requisitos)
- [Instalação e Execução](#instalação-e-execução)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [API Utilizada](#api-utilizada)
- [Como Contribuir](#como-contribuir)
- [Licença](#licença)
- [Contato](#contato)

## 🎯 Sobre o Projeto

Este é um projeto de estudo e portfólio que implementa um aplicativo mobile para visualização de produtos. O app consome dados de uma API externa e apresenta uma interface intuitiva com navegação entre telas. Foi desenvolvido com foco em boas práticas de desenvolvimento, organização de código e experiência do usuário.

O projeto serve como demonstração de competências em:

- Desenvolvimento mobile com React Native
- Gerenciamento de estado
- Consumo de APIs REST
- Navegação entre telas
- Design responsivo
- Boas práticas de código

## ✨ Funcionalidades

- **📱 Lista de Produtos**: Exibição de produtos em formato de grid responsivo
- **🔍 Detalhes do Produto**: Visualização completa das informações do produto selecionado
- **🖼️ Imagens**: Exibição de thumbnails dos produtos
- **💰 Preços**: Formatação e exibição de preços
- **📂 Categorias**: Organização por categorias
- **🔄 Loading States**: Indicadores de carregamento durante fetch de dados
- **📱 Navegação Intuitiva**: Transições suaves entre telas

## 🛠️ Tecnologias Utilizadas

### Core

- **React Native**: Framework principal para desenvolvimento mobile
- **Expo**: Plataforma para desenvolvimento e build de apps React Native
- **JavaScript**: Linguagem de programação

### Navegação

- **React Navigation**: Biblioteca para navegação entre telas
  - `@react-navigation/native`: Core da navegação
  - `@react-navigation/stack`: Navegação em pilha
  - `react-native-screens`: Otimização de performance
  - `react-native-safe-area-context`: Suporte a safe areas

### UI/UX

- **React Native Vector Icons**: Ícones para interface
- **React Native Reanimated**: Animações fluidas
- **React Native Gesture Handler**: Manipulação de gestos

### Desenvolvimento

- **Expo CLI**: Ferramentas de desenvolvimento
- **Metro Bundler**: Empacotador do React Native

## 📋 Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:

- **Node.js** (versão 18 ou superior)
- **npm** ou **yarn**
- **Expo CLI** (`npm install -g @expo/cli`)
- **Git**

### Para desenvolvimento mobile:

- **Android Studio** (para emulador Android)
- **Xcode** (para emulador iOS, apenas macOS)
- Ou dispositivo físico com app Expo Go instalado

## 🚀 Instalação e Execução

### 1. Clone o repositório

```bash
git clone https://github.com/VictorAnizauBarros/api-produtos-react-native.git
cd api-produtos-react-native
```

### 2. Instale as dependências

```bash
npm install
# ou
yarn install
```

### 3. Inicie o servidor de desenvolvimento

```bash
npm start
# ou
expo start
```

### 4. Execute no dispositivo/emulador

#### Android

```bash
npm run android
# ou
expo start --android
```

#### iOS

```bash
npm run ios
# ou
expo start --ios
```

#### Web

```bash
npm run web
# ou
expo start --web
```

### 5. Teste no dispositivo físico

- Instale o app **Expo Go** na App Store ou Google Play
- Escaneie o QR code exibido no terminal ou navegador

## 📁 Estrutura do Projeto

```
api-produtos-react-native/
├── assets/                    # Recursos estáticos (imagens, ícones)
├── src/
│   ├── components/           # Componentes reutilizáveis
│   │   └── ProductCard.js    # Card de produto
│   └── screens/              # Telas do aplicativo
│       ├── HomeScreen.js     # Tela principal com lista de produtos
│       └── DetailsScreen.js  # Tela de detalhes do produto
├── App.js                    # Ponto de entrada do app
├── app.json                  # Configurações do Expo
├── index.js                  # Arquivo de inicialização
├── package.json              # Dependências e scripts
└── README.md                 # Documentação do projeto
```

### Descrição dos Arquivos Principais

- **App.js**: Configuração da navegação e estrutura principal do app
- **HomeScreen.js**: Tela inicial que busca e exibe a lista de produtos
- **DetailsScreen.js**: Tela que mostra os detalhes completos de um produto
- **ProductCard.js**: Componente que representa um produto na lista

## 🌐 API Utilizada

O aplicativo consome a API pública [DummyJSON](https://dummyjson.com/), especificamente o endpoint `/products`.

### Estrutura da resposta da API:

```json
{
  "products": [
    {
      "id": 1,
      "title": "Produto Exemplo",
      "description": "Descrição do produto",
      "price": 99.99,
      "thumbnail": "url_da_imagem",
      "category": "categoria"
    }
  ]
}
```

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Siga estes passos:

1. **Fork** o projeto
2. Crie uma **branch** para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. Abra um **Pull Request**

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

**Victor Anizau Barros**

- LinkedIn: [Victor Hugo Anizau Barros](https://linkedin.com/in/victor-hugo-anizau-barros-65a775322/)
- GitHub: [VictorAnizauBarros](https://github.com/VictorAnizauBarros)

---

⭐ **Se este projeto te ajudou ou inspirou, dê uma estrela no repositório!**

---
