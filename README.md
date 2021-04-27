# PlantManager
PlantManager é um aplicativo mobile desenvolvido em React Native para gerenciar suas plantas de forma fácil 🌱

## Layout do projeto
Layout do projeto no [Figma](https://www.figma.com/file/ay33IWgNuQMA9HG4b3U636/PlantManager?node-id=0%3A1)

## Bibliotecas
- [React Native](https://reactnative.dev/)
- [Expo](https://docs.expo.io/)
- [Typescript](https://www.typescriptlang.org/)
- [Expo Icons](https://docs.expo.io/guides/icons/)
- [Expo Fonts](https://docs.expo.io/guides/using-custom-fonts/)
- [AppLoading](https://docs.expo.io/versions/latest/sdk/app-loading/)
- [React Navigation](https://reactnavigation.org/)
- [Axios](https://github.com/axios/axios)
- [JSON Server](https://github.com/typicode/json-server)
- [Lottie](https://docs.expo.io/versions/latest/sdk/lottie/)
- [GestureHandler](https://docs.expo.io/versions/latest/sdk/gesture-handler/)
- [React Native iPhone X Helper](https://github.com/ptelad/react-native-iphone-x-helper)
- [Svg](https://docs.expo.io/versions/latest/sdk/svg/)
- [AsyncStorage](https://docs.expo.io/versions/latest/sdk/async-storage/)
- [DateTimePicker](https://docs.expo.io/versions/latest/sdk/date-time-picker/)
- [Date-fns](https://date-fns.org/)
- [Notifications](https://docs.expo.io/versions/latest/sdk/notifications/)

## Como rodar a aplicação
1. Instalar as dependências
```
yarn install
```

2. Editar o arquivo **api.ts** em `./src/services/api.ts`, colocando seu endereço IP no local indicado.

3. Iniciar a aplicação
```
yarn start
```

4. Executar o JSON Server para obter os dados das plantas
```
json-server ./src/services/server.json --host <SEU_ENDEREÇO_IP> --port 3333
```

## Conteúdos relevantes
- [As 10 heurísticas de Nielsen](https://brasil.uxdesign.cc/10-heur%C3%ADsticas-de-nielsen-para-o-design-de-interface-58d782821840)
