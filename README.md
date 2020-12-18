### :rocket: Desafio 07: Frontend aplicação de GoFinances - GoStack 11.0
Neste desafio foi desenvolvido o frontend da aplicação de gestão financeira, a
GoFinances.

### Tecnologias utilizadas

- [React.js](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://www.npmjs.com/package/jest)

Também foram utilizadas tecnologias para padronização de código, são elas:
prettier, eslint e editorconfig.

### Backend da aplicação

O backend, que uma API em NODEJS, está disponível no seguinte link: [https://github.com/adrianoluisalmeida/desafio-06-gostack11](https://github.com/adrianoluisalmeida/desafio-06-gostack11)


### Executando a aplicação

```js
yarn
yarn start
```

**Para executar os testes:**

```js
yarn test
```

### :muscle: Rotas e Funcionalidades

**Listagem de transações**

O dashboard, disponível na rota padrão da aplicação ('/') apresenta uma listagem
de lançamentos de entradas (incomes) e saídas (outcomes). Também são
apresentadas informações adicionais como: Valor, Categoria e Data. No topo, são
apresentados widgets com os somatórios: Entradas, Saídas e Total.

<img src="https://raw.githubusercontent.com/adrianoluisalmeida/desafio-07-gostack11/master/assets/dashboard.png" alt="print dashboard">

**Importação de transações**

A importação, disponível na rota ('/import') apresenta um campo drag and drop
para envio de arquivos no formato CSV para importação de lançamentos. O arquivo
deve seguir um padrão, disponível [AQUI](https://github.com/adrianoluisalmeida/desafio-07-gostack11/blob/master/assets/file.csv).

<img src="https://raw.githubusercontent.com/adrianoluisalmeida/desafio-07-gostack11/master/assets/import.png" alt="print import">


### :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

<p align="center">Feito  por <strong>Renato Cunha</p>
