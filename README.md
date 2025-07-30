# 🏎️ React Native Lamborghini App

Aplicativo mobile desenvolvido em React Native com Expo, que exibe uma garagem virtual de carros Lamborghini. O app consome uma API fake para listar modelos, mostrar detalhes e simular a compra de veículos.

## 🚗 Funcionalidades

- Visualize diferentes modelos de Lamborghini com imagem, nome, ano e preço.
- Navegue entre os carros usando botões de próximo/anterior.
- Simule a compra de um carro com o botão "Buy This".
- Interface estilizada e responsiva.

## 🛠️ Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://axios-http.com/)

## 🚀 Como rodar o projeto

1. **Clone o repositório**
   ```bash
   git clone https://github.com/evelynnnie/react-native-lamborghini-app.git
   cd react-native-lamborghini-app
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Execute o app**
   ```bash
   npm start
   ```
   Ou use:
   - `npm run android` para rodar no Android
   - `npm run ios` para rodar no iOS
   - `npm run web` para rodar no navegador

4. **Abra no seu dispositivo**
   - Use o app [Expo Go](https://expo.dev/client) para escanear o QR Code exibido no terminal.

## 📂 Estrutura de Pastas

```
assets/
  logo.png
src/
  apis/
    getCars.ts
  components/
    BuyButton/
    CardView/
    Divider/
  constants/
    car.ts
  screens/
    GarageScreen/
  index.d.ts
App.tsx
```

## 🌐 API Fake

Os dados dos carros são obtidos da [Fake Data API Lamborghini](https://digitalinnovationone.github.io/fake-data-api-lamborghini/api/lamborghini.json).

## 👩‍💻 Autora

- Daiane Araújo

## 📄 Licença

MIT © Daiane Araújo

---

Projeto desenvolvido para fins de estudo e portfólio 🚀