# Projeto de Navegação em React Native

Projeto desenvolvido para a disciplina de **Dispositivos Móveis**, com o objetivo de praticar diferentes formas de navegação entre telas utilizando **React Native**, **Expo** e **React Navigation**.

## Identificação

- **Aluno:** Thiago Vilela
- **Professor:** William Firmino
- **Instituição:** Faculdade de Tecnologia do Senac
- **Curso:** Análise e Desenvolvimento de Sistemas (ADS)
- **Turma:** 4º período — manhã

## Funcionalidades

O aplicativo implementa três tipos de navegação:

- **Stack Navigator:** permite avançar para outra tela e retornar à anterior.
- **Bottom Tabs:** apresenta abas inferiores para acessar Início, Produtos e Perfil.
- **Drawer Navigator:** oferece um menu lateral com Início, Produtos, Perfil e Configurações.

Os navegadores são testados individualmente, alternando uma configuração no projeto.

## Tecnologias utilizadas

- React Native
- Expo (SDK 54)
- React Navigation 7
- JavaScript e JSX
- Material Icons (`@expo/vector-icons`)

## Estrutura do projeto

O projeto está organizado nas seguintes pastas:

- `src/components/` — componentes reutilizáveis: ButtonIcon, Header e Title.
- `src/screens/` — telas Home, Product, Profile e Settings.
- `src/routes/` — arquivos StackRoutes, BottomRoutes, DrawerRoutes e index.
- `src/assets/` — imagens e recursos do aplicativo.

O arquivo `src/App.jsx` contém o componente principal, enquanto o `index.js` inicializa a aplicação.

## Como executar

1. Abra o terminal na pasta `my-app`.
2. Instale as dependências com `npm install`.
3. Inicie o projeto com `npm start`.
4. Abra o aplicativo pelo Expo ou execute `npm run web` para testá-lo no navegador.

## Como alternar entre os navegadores

No arquivo `src/routes/index.jsx`, altere o valor da constante `TIPO_DE_NAVEGACAO`.

Os valores disponíveis são:

- `"stack"` — navegação em pilha;
- `"bottom"` — abas inferiores;
- `"drawer"` — menu lateral.

Salve o arquivo para testar o modo escolhido. O projeto foi organizado para usar **um navegador por vez**, conforme a atividade.

## Referência

Material de apoio da disciplina: **Navegação em React Native — Passo a passo completo com React Navigation: Stack, Bottom Tabs e Drawer**.