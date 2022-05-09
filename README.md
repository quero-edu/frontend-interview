# Frontend Interview

## Requirements

- `Node >= 14`
- `NPM >= 7`

## Start

- `npm install`
- `npm start`

## Client

the client runs on port [`1234`](http://localhost:1234/)

## API

the API runs on port [`3000`](http://localhost:3000/)

### Endpoint

`http://localhost:3000/offers`

#### Response

```json
[
  {
    "price": 706.08,
    "course": {
      "name": "Engenharia Mecânica"
    },
    "university": {
      "name": "UNIP",
      "logoUrl": "https://www.tryimg.com/u/2019/04/16/unip.png"
    }
  }
]
```

## Template

### Layout

```html
<div id="app">
  <div class="container">
    <h1>Lista de ofertas</h1>
    <main class="wrapper">
      <!-- offer cards -->
      <!-- offer cards -->
      <!-- offer cards -->
    <main>
  </div>
</div>
```

### Offer Card

```html
<div class="offer-card">
  <img src="https://www.tryimg.com/u/2019/04/16/unip.png" alt="UNIP">
  <h2>Engenharia Mecânica</h2>
  <p>
    <strong>R$ 706,08</strong>
    <span>/mês</span>
  </p>
</div>
```