# 📊 Análise de Exportações do Brasil - Dados de 2025

Este projeto tem como objetivo realizar a **análise e o tratamento dos dados de exportações brasileiras referentes ao ano de 2025**, utilizando **Python (Google Colab)** para a exploração e preparação dos dados.  
Os resultados dessa etapa servirão de base para a construção de dashboards comparativos no Power BI.

---

## 🔗 Acesse o Notebook no Google Colab
Você pode abrir e executar o notebook diretamente pelo link abaixo:

👉 [Abrir no Google Colab](https://colab.research.google.com/drive/1Y1zlnWwj_xKuY-kaL1TtuaPqxlz4khGT?usp=sharing)

---

## 🧠 Objetivo do Notebook

O notebook realiza o **tratamento e a análise inicial** dos dados de exportações do ano de 2025.  
Esta é a **primeira fase do projeto**, focada em preparar os dados para visualizações futuras no Power BI.

### Etapas desenvolvidas:
1. **Importação do dataset do ComexStat**
   - Leitura de dados públicos de exportações brasileiras.
2. **Exploração e limpeza dos dados**
   - Padronização de nomes de colunas.  
   - Conversão de tipos e tratamento de valores ausentes.  
   - Filtragem de registros inválidos ou inconsistentes.
3. **Criação de novas métricas**
   - `Valor_USD`: valor total exportado.  
   - `Peso_kg`: peso total exportado.  
   - `Preco_medio_USD_kg`: preço médio por kg exportado.
4. **Exportação dos dados tratados**
   - Base final pronta para integração e visualização no Power BI.

---

## 📈 Contexto do Projeto

Este notebook faz parte de um projeto mais amplo de análise de exportações brasileiras, que será expandido para comparar os resultados de **2024 e 2025** no Power BI.  
O foco inicial é garantir a **qualidade, consistência e estruturação dos dados** para que os dashboards futuros apresentem informações confiáveis.

---

## 📊 Exemplo de Visualização no Power BI (etapa futura)

Após o tratamento completo, os dados são integrados ao Power BI, permitindo análises como:

- 💰 **Valor total exportado (USD)**  
- ⚖️ **Peso total exportado (KG)**  
- 📉 **Preço médio por KG**  
- 🌎 **Top estados exportadores**  
- 🏭 **Principais produtos exportados**  
- 📅 **Evolução mensal das exportações**

---

## 🧱 Modelo de Dados (Power BI)

O modelo segue o formato **estrela**, com uma tabela fato central (`FATO_EXPORTACAO`) e dimensões relacionadas:

- **DIM_PRODUTO** → informações sobre os produtos exportados  
- **DIM_UF** → informações sobre os estados exportadores  
- **DIM_CALENDARIO** → informações temporais (ano, mês, feriados, etc.)

---

## 🛠️ Ferramentas Utilizadas
- **Python (Pandas, Matplotlib, Seaborn)**  
- **Google Colab**  
- **Power BI**  
- **Fonte dos dados:** [ComexStat - Ministério da Economia](https://balanca.economia.gov.br/balanca/)

---

## 🧩 Próximos Passos
- [ ] Integrar dados de 2024  
- [ ] Realizar análises comparativas (2024 × 2025)  
- [ ] Criar visualizações avançadas no Power BI  
- [ ] Publicar o dashboard interativo final

---

## ✉️ Autoria
Projeto desenvolvido por [**Raíra Marinho**](https://github.com/rairamarinho)  
💡 *Este repositório faz parte de um estudo prático de análise e visualização de dados no contexto do comércio exterior brasileiro.*


