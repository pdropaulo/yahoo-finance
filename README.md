# 📊 Dashboard Financeiro – Análise de Ativo (Yahoo Finance)

Este projeto apresenta um **painel interativo construído no Tableau** a partir de dados históricos do Yahoo Finance.  
O objetivo é analisar **preço, volume, volatilidade e tendências** de um ativo do mercado financeiro, simulando uma aplicação real em **monitoramento de investimentos**.  

---

## 🔍 1. Contexto
Investidores e analistas financeiros precisam acompanhar a evolução dos preços de ativos para tomar decisões estratégicas.  
Com base em dados de **abertura, máxima, mínima, fechamento e volume de negociação**, este projeto traz uma visão consolidada para:  
- Identificar **tendências de alta ou baixa**;  
- Avaliar **volatilidade** em diferentes períodos;  
- Relacionar **volume de negociação e movimentos de preço**;  
- Destacar **sinais técnicos simples** como médias móveis.  

---

## 🗂 2. Fonte dos Dados
- **Origem**: Yahoo Finance  
- **Período**: 2018 até 2023
- **Atributos disponíveis**:  
  - `Date` → Data da negociação  
  - `Open` → Preço de abertura  
  - `High` → Maior preço do dia  
  - `Low` → Menor preço do dia  
  - `Close` → Preço de fechamento  
  - `Adj Close` → Fechamento ajustado  
  - `Volume` → Quantidade de ações negociadas  

---

## ⚙️ 3. Elementos do Dashboard

🕰 **Candlestick Chart**  
Mostra a variação intradiária de preços (`Open`, `High`, `Low`, `Close`), permitindo visualizar tendências e volatilidade.  
📌 <img width="792" height="452" alt="image" src="https://github.com/user-attachments/assets/2703e889-bfc7-4fe7-813c-45ae9a9bee2c" />
 

📉 **Retorno Diário**  
Cálculo: `(Close - Open) / Open`. Permite identificar dias positivos e negativos.  
📌 <img width="808" height="445" alt="image" src="https://github.com/user-attachments/assets/a260b9d5-d254-4d5a-9083-9ec7a203f665" />
  

📊 **Volatilidade Diária**  
Cálculo: `(High - Low)`. Mede a instabilidade do ativo em cada sessão.  
📌 <img width="811" height="443" alt="image" src="https://github.com/user-attachments/assets/8f084c78-632b-4aa1-a945-56a179788910" />
 

📦 **Volume de Negociação**  
Barras + linha de preço médio anual → mostra períodos de maior movimentação de mercado.  
📌 <img width="396" height="455" alt="image" src="https://github.com/user-attachments/assets/c9f82d55-6ff0-47c5-b934-4cd826ee6109" />
 

📈 **Médias Móveis (MA7 e MA30)**  
Linhas de tendência para análise de curto e longo prazo.  
📌 <img width="805" height="431" alt="image" src="https://github.com/user-attachments/assets/3d58d5f8-39e0-495f-ac90-56ddc0bafeeb" />
 
📌 <img width="802" height="444" alt="image" src="https://github.com/user-attachments/assets/25dc601d-be21-4486-bdce-af65be9d00ab" />

---

## 📈 4. Principais Resultados
- O ativo apresentou **alta consistente em março de 2023**, com fechamento próximo a 33K.  
- Houve **picos de volatilidade** entre 7 e 10 de março, indicando maior risco nesse período.  
- **Aumento de volume** em 2020 e 2022, possivelmente ligado a eventos de mercado.  
- O **cruzamento da MA7 acima da MA30 no fim de março** sinalizou uma tendência de alta.  

---

## 💻 5. Tecnologias Utilizadas
- **Tableau Desktop / Tableau Public**  
- Dataset do **Yahoo Finance** (exportado em CSV) 

---

## 🚀 6. Como Acessar
O painel completo pode ser acessado aqui:  
👉 [Link para o Tableau Public](https://public.tableau.com/profile/api/publish/YahooFinances/Painel1)

---

