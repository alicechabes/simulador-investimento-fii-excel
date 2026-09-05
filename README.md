# 📈 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Projeto desenvolvido como desafio prático na **Digital Innovation One (DIO)**. O objetivo é criar uma ferramenta automatizada em Excel para simular o crescimento patrimonial e o recebimento de dividendos em Fundos Imobiliários ao longo do tempo.

---

## 🎯 Objetivos do Projeto

- Automatizar o cálculo de projeção de renda passiva com FIIs.
- Aplicar conceitos de juros compostos e reinvestimento de dividendos no Excel.
- Documentar e compartilhar projetos técnicos no GitHub.

---

## 🧮 Estrutura e Fórmulas da Planilha

A planilha foi dividida em duas áreas: **Premissas do Investimento** e **Projeção Mês a Mês**.

### 1. Parâmetros de Entrada
- **Aporte Inicial ($A_0$):** Valor inicial investido.
- **Aporte Mensal ($A_m$):** Valor adicionado todos os meses.
- **Dividend Yield Mensal ($DY$):** Taxa média de rendimento mensal do fundo.
- **Prazo ($t$):** Período da simulação em meses.

### 2. Lógica dos Cálculos
Para cada mês $n$, os cálculos seguem a seguinte ordem:

- **Saldo Inicial:** Igual ao Patrimônio Total do mês anterior ($n-1$).
- **Dividendos do Mês:** 
  $$\text{Dividendos} = (\text{Saldo Inicial} + \text{Aporte}) \times \text{DY}$$
- **Patrimônio Total:** 
  $$\text{Patrimônio} = \text{Saldo Inicial} + \text{Aporte} + \text{Dividendos}$$

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel / Google Sheets:** Construção do modelo financeiro e fórmulas.
- **Git & GitHub:** Versionamento e publicação do repositório.
- **Markdown:** Documentação técnica.

---

## 🚀 Como Utilizar a Planilha

1. Baixe o arquivo `.xlsx` disponível neste repositório.
2. Abra o arquivo no Excel ou Google Sheets.
3. Altere apenas as células de **Premissas** (Aporte Inicial, Aporte Mensal e DY %).
4. Visualize os resultados consolidados na tabela e nos gráficos automáticos.

---

## 👤 Autor

Desenvolvido por **Seu Nome** durante a formação na [DIO](https://www.dio.me/).
- **GitHub:** [@seu-usuario](https://github.com/seu-usuario)
- **LinkedIn:** [Seu Perfil](https://linkedin.com/in/seu-perfil)
- 
