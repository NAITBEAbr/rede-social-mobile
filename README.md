# Rede social mobile

Esqueleto de um aplicativo de rede social em React Native, com a navegação já montada:
menu lateral, abas e as três telas principais.

## O que já existe

- **Navegação por menu lateral** (drawer), com Início e Perfil
- **Navegação por abas** dentro do Início, entre Feed e Criação de Postagem
- **Telas** de Feed, Criação de Postagem e Perfil, ainda como marcadores de lugar

## O que falta

- Conteúdo real das telas: lista de postagens no feed, formulário de nova postagem e
  dados do usuário no perfil
- Banco de dados para guardar as postagens
- Autenticação de usuário

## Tecnologias

- React Native com Expo
- React Navigation (drawer e bottom tabs)

## Como executar

```bash
npm install
npx expo start
```

## Estrutura

```
App.js                      ponto de entrada
navigation/
  DrawerNavigator.js        menu lateral: Início e Perfil
  TabNavigator.js           abas: Feed e Criação de Postagem
screens/
  Feed.js                   feed de postagens
  CreatePost.js             criação de postagem
  Profile.js                perfil do usuário
```
