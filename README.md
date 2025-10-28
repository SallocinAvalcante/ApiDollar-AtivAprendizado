# ApiDollar-AtivAprendizado
Teste de API de dolar 
# 💵 Cotação do Dólar (USD/BRL)

Este projeto é uma página web simples e responsiva que consome a AwesomeAPI(https://docs.awesomeapi.com.br/api-de-moedas) para exibir informações atualizadas sobre a cotação do dólar em relação ao real brasileiro (USD/BRL).

---

## 📌 Objetivo

Utilizar `fetch()` em JavaScript para consumir uma API pública de moedas e exibir:

- Valor atual do dólar
- Maior valor do dia
- Menor valor do dia

---

## ⚙️ Tecnologias Utilizadas

- **HTML5**: estrutura da página
- **JavaScript (ES6+)**: consumo da API e manipulação do DOM
- **Bootstrap 5.3**: estilização e layout responsivo via CDN

---

## 🎨 Layout e Estilo

A interface é construída com componentes do Bootstrap, sem CSS personalizado. Os valores são destacados com cores diferentes para facilitar a leitura:

| Tipo de valor       | Cor usada     | Classe Bootstrap |
|---------------------|---------------|------------------|
| Valor atual         | Amarelo       | `text-warning`   |
| Maior valor do dia  | Verde         | `text-success`   |
| Menor valor do dia  | Vermelho      | `text-danger`    |

---

## 🔗 API Utilizada

- **Endpoint**: `https://economia.awesomeapi.com.br/json/last/USD-BRL`
- **Formato de resposta**: JSON
- **Campos utilizados**:
  - `bid`: valor atual
  - `high`: maior valor do dia
  - `low`: menor valor do dia

