# 📘 Projeto: Calculadora de Equação do Segundo Grau

Este projeto é uma ferramenta educacional completa para o estudo e
resolução de **equações do segundo grau** (ax² + bx + c = 0). A
aplicação conta com validações inteligentes, gráficos, histórico de
cálculos, modo escuro, entrada por voz e uma interface responsiva.

## 📌 Funcionalidades

### ✅ Cálculo Completo

-   Entrada dos coeficientes **a**, **b**, **c**.
-   Cálculo automático do **delta (Δ)**.
-   Determinação das **raízes reais ou complexas**.
-   Explicação detalhada quando **Δ \< 0**.

### ⚠️ Validações Inteligentes

-   O coeficiente **a ≠ 0**.
-   Impede valores inválidos ou não numéricos.
-   Exibe alertas amigáveis para erros do usuário.

### 📊 Gráfico da Parábola (Chart.js)

-   Desenho automático da parábola correspondente.
-   Marcação visual das raízes reais no eixo X.
-   Escala ajustável.

### 🧾 Histórico de Cálculos

-   Armazena automaticamente (opcional) cada equação resolvida.
-   Mostra coeficientes usados e raízes encontradas.
-   Usa `localStorage` para manter os dados entre sessões.

### 🎨 Modo Claro / Escuro

-   Alternador de tema.
-   Layout adaptado para leitura confortável.

### 🎤 Entrada por Voz (Opcional)

-   Usa Web Speech API.
-   Permite dizer valores como: "a igual a 2, b igual a -3, c igual a
    5".

### 📱 Totalmente Responsivo

-   Interface adaptada para celular, tablet e PC.
-   Layout reorganizado com media queries.

## 🛠️ Tecnologias Utilizadas

-   **HTML5**
-   **CSS3**
-   **JavaScript ES6**
-   **Chart.js**
-   **Web Speech API**
-   **localStorage**

## 📥 Como Usar

1.  Abra o arquivo `index.html` no navegador.
2.  Insira os coeficientes **a**, **b**, **c**.
3.  Clique em **Calcular**.
4.  Veja resultados, análise do delta e gráfico.
5.  Salve no histórico se desejar.
6.  Use o botão de tema.
7.  Teste a entrada por voz.

## 📂 Estrutura Recomendada

    📁 equacao-2-grau
     ├── index.html
     ├── style.css
     ├── script.js
     ├── README.md
     └── /assets
          └── chart.min.js

## 👨‍💻 Desenvolvedor

**Egmar Afonso**\
"Perseverança e simplicidade me guiam em cada projeto."
