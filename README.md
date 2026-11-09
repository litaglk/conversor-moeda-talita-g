App Conversor de Moedas

Link Expo Snack: https://snack.expo.dev/@litag/conversor-moeda

Conversor de Moedas - React Native (MVVM)

Aplicativo mobile de conversão de moedas desenvolvido com React Native e JavaScript, consumindo a API Frankfurter e aplicando o padrão arquitetural MVVM.

Tecnologias Utilizadas
Reactive Native/Expo
JavaScript
Arquitetura MVVM
API Pública Frankfurter (`https://api.frankfurter.dev`)
@react-native-picker/picker

Estrutura da Arquitetura MVVM

`src/models/currencyModel.js`: Faz as requisições HTTP (`fetch`) para os endpoints `/currencies` e `/rate/{from}/{to}` da API Frankfurter.
`src/viewmodels/useCurrencyViewModel.js`: Custom Hook que gerencia o estado da aplicação, faz as validações de regras de negócio (entradas numéricas, moedas iguais) e calcula as conversões.
`src/views/CurrencyConverterScreen.js`: Interface visual responsiva que exibe o formulário, seletores de moeda e área de resultados.

Como Executar o Projeto

Instalar dependências:
   ```bash
   npm install @react-native-picker/picker

Bash

npx expo start

Identidade Visual - Bandeira do Líbano

Vermelho: #d81c22
Branco: #FFFFFF
Verde: #00A651
