# 📊 Análise de Vendas 

## 🌍 1. Produtos Mais Populares por País

### 🔍 Perguntas
- **Quais são os 3 produtos mais vendidos por país?**
- **Quantas unidades foram vendidas de cada um?**
- **Resultados em formato de tabela, com países ordenados alfabeticamente e produtos por volume de vendas decrescente.**

### 📋 Tabela: Top 3 Produtos Mais Vendidos por País

| País        | Produto                     | Quantidade Vendida |
|-------------|-----------------------------|---------------------|
| Australia   | NEW MEGANIUM RG CubeXX      | 13                  |
|             | NEW MEGANIUM RG28XX         | 8                   |
|             | MEGANIUM RG353M             | 5                   |
| Canada      | NEW MEGANIUM RG 40XXV       | 19                  |
|             | NEW MEGANIUM RG35XX         | 14                  |
|             | NEW MEGANIUM RG28XX         | 11                  |
| France      | NEW MEGANIUM RG35XX         | 12                  |
|             | NEW MEGANIUM RG CubeXX      | 9                   |
|             | MEGANIUM RG353M             | 6                   |
| Germany     | NEW MEGANIUM RG 40XXV       | 7                   |
|             | NEW MEGANIUM RG28XX         | 7                   |
|             | NEW MEGANIUM RG CubeXX      | 5                   |
| Japan       | NEW MEGANIUM RG 40XXV       | 11                  |
|             | MEGANIUM RG353M             | 6                   |
|             | NEW MEGANIUM RG CubeXX      | 5                   |
| UK          | NEW MEGANIUM RG35XX         | 7                   |
|             | MEGANIUM RG353M             | 5                   |
|             | NEW MEGANIUM RG CubeXX      | 1                   |
| USA         | MEGANIUM RG353M             | 4                   |
|             | NEW MEGANIUM RG CubeXX      | 1                   |

### 📈 Visualização Gráfica

Foi gerado um gráfico de barras agrupadas com os 3 produtos mais vendidos em cada país, com as seguintes características:

- **Eixo Y**: Produtos vendidos
- **Eixo X**: Quantidade vendida
- **Cores**: Cada país representado por uma cor diferente
- **Legenda**: Países
- **Ordenação**: Produtos organizados por volume de vendas decrescente dentro de cada país

### 🧠 Observações

- O produto **"NEW MEGANIUM RG 40XXV"** foi destaque no Canadá e Japão.
- O **"MEGANIUM RG353M"** aparece em quase todos os países, mesmo com volume um pouco menor.
- A presença de variações como **"CubeXX"**, **"28XX"** e **"35XX"** indica boa diversificação de vendas da marca.

---

## 🚚 2. Insights sobre Transporte e Logística

### 🌎 1. Países com Maior Custo Logístico Médio
Para calcular o custo logístico médio, consideramos o valor médio dos descontos aplicados por país. Aqui estão os países com os maiores custos logísticos médios (desconto médio por venda):

| 🌍 País       | 💰 Custo Logístico Médio (Desconto Médio) |
|--------------|-----------------------------------|
| 🇨🇦 Canadá     | 53.57                            |
| 🇬🇧 Reino Unido | 52.93                            |
| 🇦🇺 Austrália  | 51.36                            |

Esses países apresentam o maior desconto médio por venda, indicando um custo logístico possivelmente mais elevado.

### 💵 2. Receita Líquida Média por País e Plataforma

A receita líquida pode ser calculada como:

```
Receita Líquida = total_price - discount_value
```

### 📊 Dados de Receita Líquida Média

| 🌍 País       | 🛒 Plataforma  | 💵 Receita Líquida Média |
|--------------|--------------|----------------------|
| 🇺🇸 EUA      | 🧡 Etsy       | 168.97               |
| 🇨🇦 Canadá   | 🛍️ Shopee      | 204.57               |
| 🇬🇧 Reino Unido | 📦 AliExpress | 184.20               |
| 🇩🇪 Alemanha | 🛍️ Shopee      | 317.67               |
| 🇦🇺 Austrália | 🧡 Etsy       | 189.46               |

Esses valores refletem a receita líquida média após aplicar descontos. 

### 🌍 Países com Maiores Valores Médios por Pedido  
O valor médio por pedido pode ser calculado como:  

```
Valor Médio por Pedido = total_price / quantity
```

| 🌍 País       | 💰 Valor Médio por Pedido | 🛒 Canal Predominante |
|--------------|--------------------------|----------------------|
| 🇩🇪 Alemanha  | 110.00                   | Shopee               |
| 🇬🇧 Reino Unido| 100.00                  | AliExpress           |
| 🇨🇦 Canadá    | 100.00                   | Shopee               |

Os maiores valores médios por pedido ocorrem principalmente em Shopee e AliExpress, sugerindo que esses canais possuem produtos de ticket mais alto nesses países.

### 🚧 Gargalos Logísticos Identificados

Os gargalos logísticos podem envolver tempo excessivo de entrega ou custo acima da média. Aqui estão algumas observações:

- **Custo elevado:**  
  Os países com os maiores descontos aplicados (indicando possíveis altos custos logísticos) são:  
  - 🇦🇺 Austrália: 86.68  
  - 🇬🇧 Reino Unido: 86.51

- **Possíveis atrasos:**  
  Caso tenhamos dados de prazo de entrega, poderíamos verificar se esses custos refletem dificuldades operacionais, como transporte internacional demorado.

### 📉 Regiões com Baixa Performance & Ações de Melhoria

Para identificar regiões com baixo desempenho, podemos analisar fatores como menor receita líquida e alto custo logístico.

### 🔍 Regiões com Baixo Desempenho

- 🇫🇷 França e 🇯🇵 Japão apresentam pedidos menores e descontos relativamente altos.

### 🚀 Sugestões de Melhoria

- 🚚 **Revisão de rotas e fornecedores:** Otimizar transportadoras e armazenagem para reduzir custos e prazos de entrega.  
- 📈 **Promoção de canais alternativos:** Explorar Shopee em mercados com baixa performance para ampliar vendas.  
- 💳 **Estratégia de precificação:** Ajustar preços e descontos para tornar ofertas mais competitivas nos países de menor demanda.

---

## 📈 3. Estratégias de Crescimento e Otimização 

### 📆 Tendências e Sazonalidades  
A seguir, o volume total de vendas por mês para cada produto:  

| 📅 Mês        | 🛍️ Produto              | 🔢 Quantidade Vendida |
|--------------|----------------------|------------------|
| Maio 2024    | MEGANIUM RG353M       | 3                |
| Maio 2024    | NEW MEGANIUM RG CubeXX | 2                |
| Maio 2024    | NEW MEGANIUM RG28XX    | 5                |
| Junho 2024   | NEW MEGANIUM RG 40XXV  | 11               |
| Junho 2024   | NEW MEGANIUM RG35XX    | 6                |
| Junho 2024   | NEW MEGANIUM RG28XX    | 1                |
| Julho 2024   | MEGANIUM RG353M       | 6                |
| Julho 2024   | NEW MEGANIUM RG35XX    | 18               |
| Julho 2024   | NEW MEGANIUM RG CubeXX | 3                |
| Agosto 2024  | MEGANIUM RG353M       | 11               |
| Agosto 2024  | NEW MEGANIUM RG 40XXV  | 8                |
| Agosto 2024  | NEW MEGANIUM RG28XX    | 6                |
| Setembro 2024| MEGANIUM RG353M       | 8                |
| Setembro 2024| NEW MEGANIUM RG 40XXV  | 5                |
| Setembro 2024| NEW MEGANIUM RG28XX    | 3                |
| Outubro 2024 | MEGANIUM RG353M       | 12               |
| Outubro 2024 | NEW MEGANIUM RG 40XXV  | 8                |
| Outubro 2024 | NEW MEGANIUM RG28XX    | 4                |
| Novembro 2024| MEGANIUM RG353M       | 2                |
| Novembro 2024| NEW MEGANIUM RG 40XXV  | 6                |

### 🔍 Insights sobre sazonalidade  
- Os meses de **junho, julho e agosto** tiveram os maiores volumes de vendas.  
- **MEGANIUM RG353M** manteve um nível de vendas consistente, mas teve picos nos meses de julho e outubro.  
- **NEW MEGANIUM RG 40XXV** teve um volume alto em junho e agosto, mas uma queda em setembro e outubro.  

### 📈 Projeção de Demanda para os Próximos 3 Meses  
Com base nas tendências observadas, aqui está a estimativa de demanda para os próximos três meses:  

| 📅 Mês        | 🛍️ Produto              | 📊 Demanda Projetada |
|--------------|----------------------|------------------|
| Dezembro 2024| MEGANIUM RG353M       | 6                |
| Dezembro 2024| NEW MEGANIUM RG 40XXV  | 5                |
| Dezembro 2024| NEW MEGANIUM RG28XX    | 3                |
| Janeiro 2025 | MEGANIUM RG353M       | 7                |
| Janeiro 2025 | NEW MEGANIUM RG 40XXV  | 6                |
| Janeiro 2025 | NEW MEGANIUM RG CubeXX | 3                |
| Fevereiro 2025| MEGANIUM RG353M       | 5                |
| Fevereiro 2025| NEW MEGANIUM RG 40XXV  | 5                |
| Fevereiro 2025| NEW MEGANIUM RG28XX    | 2                |

### 📌 Estratégia para os próximos meses  
- **Reforçar estoques** para os meses de dezembro e janeiro, já que tendem a ter picos de vendas.  
- **Promoções e campanhas** no início do ano para manter o ritmo de vendas pós-festas.  
- **Ajuste de canais de vendas**, focando nos países que tiveram maior demanda nos últimos meses.  

## 🌎 Regiões com Alta Demanda para Descentralização da Produção  
Com base no volume de vendas, podemos destacar países que possuem **alta demanda** e poderiam se beneficiar de produção descentralizada para reduzir custos e melhorar prazos de entrega.  

| 🌍 País       | 🛒 Volume de Vendas | 🏭 Oportunidade de Produção Local |
|--------------|------------------|--------------------------------|
| 🇺🇸 EUA      | Alto              | Possível descentralização em hubs locais nos EUA. |
| 🇨🇦 Canadá   | Alto              | Expansão para centros de produção na América do Norte. |
| 🇬🇧 Reino Unido | Alto              | Fortalecimento da cadeia logística interna no Reino Unido. |

### 🔍 Estratégia:
- **Redução de prazos**: Produção mais próxima do consumidor diminui tempo de entrega.  
- **Otimização de custos**: Menos dependência de logística internacional reduz despesas operacionais.  
- **Sustentabilidade**: Menos transporte global pode resultar em menor impacto ambiental.  

### 💰 Países com Tíquete Médio Alto, Mas Vendas Baixas  
Ao identificar mercados onde os produtos possuem **preço elevado** mas **baixo volume de vendas**, podemos traçar estratégias para impulsionar as compras nesses países.  

| 🌍 País       | 💵 Tíquete Médio | 🔢 Volume de Vendas | 🚀 Estratégia de Expansão |
|--------------|--------------|----------------|---------------------------|
| 🇦🇺 Austrália | 110.0        | Baixo          | Revisão de precificação e incentivos para compradores. |
| 🇯🇵 Japão     | 100.0        | Baixo          | Campanhas de marketing local e fortalecimento de canais de distribuição. |
| 🇫🇷 França    | 100.0        | Baixo          | Exploração de marketplaces regionais para ampliar alcance. |

### 📌 Estratégias para aumentar as vendas:
- 📣 **Marketing direcionado**: Campanhas regionais adaptadas ao comportamento do consumidor.  
- 🎁 **Promoções e descontos**: Ofertas especiais para atrair novos compradores.  
- 🔗 **Expansão de canais**: Uso de marketplaces locais para melhorar a distribuição.  

### 🏆 Decisões Estratégicas Baseadas nos Dados  
Aqui estão algumas **ações recomendadas** com base na análise de demanda e tíquete médio:  

1️⃣ **Descentralizar Produção** para regiões de maior demanda, reduzindo custos logísticos.  
2️⃣ **Reforçar Estoques** nos países onde há tendência de crescimento.  
3️⃣ **Revisar Estratégia de Preço** para países de tíquete alto e vendas baixas.  
4️⃣ **Fortalecer Canais de Venda** com marketplaces estratégicos nos países de baixa performance.  
5️⃣ **Aprimorar Logística** para mitigar gargalos e otimizar prazos de entrega.  
