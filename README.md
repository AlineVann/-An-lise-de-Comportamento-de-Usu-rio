# Analise de Comportamento de Usuario
Dashboard de Análise de Comportamento de Usuário (Looker Studio)
# 🚀 Dashboard de Análise de Comportamento de Usuário (Looker Studio)

**[https://lookerstudio.google.com/s/sacc5s3AJRk]** 

(https://lookerstudio.google.com/s/hwkfMZ9JGOk) [PDF]

---

## 1. O Problema

Este projeto foi desenvolvido como um portfólio para analisar a jornada de usuários em um site/aplicação fictícia. O objetivo é identificar gargalos, entender por que os usuários saem e qual a performance da interface para diferentes segmentos de público.

## 2. Processo e Ferramentas

O dashboard foi construído 100% no **Looker Studio**, consumindo dados de uma planilha **Google Sheets** (ou BigQuery, etc.).

O processo envolveu:
* **Limpeza e ETL:** Tratamento dos dados de `Motivo da Saída` para categorizar abandonos.
* **Criação de Métricas (Campos Calculados):** Criação de métricas-chave que não existiam na base original, como:
    * `Taxa de Abandono (%)`
    * `Taxa de Conversão por Idade (%)`
    * `Tempo Médio na Aplicação`
* **Visualização e Design:** Criação de um layout interativo para permitir o filtro por dispositivo, data e faixa etária.

## 3. Análise e Métricas

O dashboard responde a perguntas-chave usando os seguintes dados:

* **Dimensões:**
    * `Página Visitada`, `Dispositivo`, `Faixa Etária`, `Categoria`, `Motivo da Saída`, `Data`
* **Métricas:**
    * `Conversão`, `Tempo na Página (s)`, `Avaliação da Interface` (média), `Taxa de abandono`

## 4. Insights Chave (O que o Dashboard Responde)

Com este painel, um gestor pode descobrir:
* Qual `Faixa Etária` possui a maior `Taxa de Conversão`?
* O `Tempo na Página` é maior no Desktop ou no Mobile?
* Quais páginas geram a pior `Avaliação da Interface`?
* Qual o principal `Motivo da Saída` nas páginas de checkout?

## 5. Como Usar

1.  Acesse o **[https://lookerstudio.google.com/s/sacc5s3AJRk]**.
2.  Use os filtros no topo para selecionar o período ou dispositivo.
3.  Clique nos gráficos para filtrar o restante do painel (ex: clique na "Faixa Etária: 25-34" para ver o comportamento apenas desse grupo).
