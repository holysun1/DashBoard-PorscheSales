# Porsche | Inteligência de Vendas - Dashboard Analítico 🏎️📊

Um dashboard interativo e sofisticado de análise de vendas focado no mercado de veículos de luxo. Este projeto foi desenvolvido em uma interface *Single Page Application* (SPA) puramente baseada em tecnologias front-end, processando dados brutos em insights de negócios acionáveis.

A interface gráfica foi desenhada sob rigorosos padrões de UI/UX, utilizando o **Minimalismo Editorial** e a identidade visual global da [Porsche.com](https://www.porsche.com/brazil/pt/), caracterizada por alto contraste, tipografia geométrica, espaços negativos e detalhes precisos no icônico "Porsche Red".

---

## 🎯 Objetivos do Projeto

O objetivo principal desta aplicação é responder de forma dinâmica e instantânea às seguintes perguntas de negócio:
* Quais os principais modelos de carro vendidos segmentados por cidade?
* Qual o ano de modelo de carro de maior saída em um determinado período/recorte?
* Quais os insights de popularidade de vendas cruzando dados de modelos e regiões geográficas?

---

## ✨ Funcionalidades

* **Filtros Dinâmicos Multi-nível:** Capacidade de fatiar (slice-and-dice) os dados por *Modelo da Porsche*, *Ano do Modelo*, *Cidade* e *Método de Pagamento*.
* **Métricas de Performance (KPIs):** Indicadores calculados em tempo real que exibem:
  * Faturamento Total (US$).
  * Volume de Veículos Entregues.
  * Ano de Modelo em Destaque.
  * *Top Seller* (Modelo mais vendido no recorte).
* **Visualização de Dados Elegante:**
  * Gráfico de Barras: Analisa a performance quantitativa por modelo.
  * Gráfico de Rosca (Doughnut): Representa o *market share* interno dos anos de modelo.
* **Motor de Insights Automatizados:** Um painel inteligente que lê os dados em exibição e escreve análises textuais automaticamente, apontando tendências geográficas e financeiras.
* **Processador de CSV Integrado:** A aplicação conta com um leitor (parser) nativo em JavaScript capaz de converter blocos de texto CSV (Comma-Separated Values) em estruturas de dados JSON dinâmicas.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído para ser leve, rápido e não depender de arquiteturas de backend complexas.

* **HTML5:** Estruturação semântica da página.
* **CSS3 (Customizado):** Estilização responsiva sem dependência de frameworks externos, utilizando variáveis (`:root`) para padronização da paleta de cores da marca.
* **Vanilla JavaScript (ES6+):** Lógica de negócios, manipulação do DOM, cálculos de KPIs, filtros de array e parser do dataset CSV.
* **Chart.js:** Biblioteca externa utilizada para a renderização limpa e performática dos gráficos em elementos `<canvas>`.
* **Google Fonts (Inter):** Tipografia escolhida por sua semelhança com a fonte oficial *Porsche Next*.

---

## 🚀 Como Executar o Projeto

Como o projeto é *Client-Side* puro e os dados estão embutidos (ou podem ser injetados no código), a execução é extremamente simples.

1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/seu-usuario/porsche-sales-dashboard.git](https://github.com/seu-usuario/porsche-sales-dashboard.git)
