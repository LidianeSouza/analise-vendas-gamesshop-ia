# 📊 Análise de Vendas — Produtos Mais Vendidos por País

## 🔍 Perguntas
- **Quais são os 3 produtos mais vendidos por país?**
- **Quantas unidades foram vendidas de cada um?**
- **Resultados em formato de tabela, com países ordenados alfabeticamente e produtos por volume de vendas decrescente.**

## 📋 Tabela: Top 3 Produtos Mais Vendidos por País

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

## 📈 Visualização Gráfica

Foi gerado um gráfico de barras agrupadas com os 3 produtos mais vendidos em cada país, com as seguintes características:

- **Eixo Y**: Produtos vendidos
- **Eixo X**: Quantidade vendida
- **Cores**: Cada país representado por uma cor diferente
- **Legenda**: Países
- **Ordenação**: Produtos organizados por volume de vendas decrescente dentro de cada país

## 🧠 Observações

- O produto **"NEW MEGANIUM RG 40XXV"** foi destaque no Canadá e Japão.
- O **"MEGANIUM RG353M"** aparece em quase todos os países, mesmo com volume um pouco menor.
- A presença de variações como **"CubeXX"**, **"28XX"** e **"35XX"** indica boa diversificação de vendas da marca.

---

# 📦 Análise de Custos Logísticos e Receita Líquida Média

## 🌎 1. Países com Maior Custo Logístico Médio
Para calcular o custo logístico médio, consideramos o valor médio dos descontos aplicados por país. Aqui estão os países com os maiores custos logísticos médios (desconto médio por venda):

| 🌍 País       | 💰 Custo Logístico Médio (Desconto Médio) |
|--------------|-----------------------------------|
| 🇨🇦 Canadá     | 53.57                            |
| 🇬🇧 Reino Unido | 52.93                            |
| 🇦🇺 Austrália  | 51.36                            |

Esses países apresentam o maior desconto médio por venda, indicando um custo logístico possivelmente mais elevado.

## 💵 2. Receita Líquida Média por País e Plataforma

A receita líquida pode ser calculada como:

```
Receita Líquida = total_price - discount_value
```

## 📊 Dados de Receita Líquida Média

| 🌍 País       | 🛒 Plataforma  | 💵 Receita Líquida Média |
|--------------|--------------|----------------------|
| 🇺🇸 EUA      | 🧡 Etsy       | 168.97               |
| 🇨🇦 Canadá   | 🛍️ Shopee      | 204.57               |
| 🇬🇧 Reino Unido | 📦 AliExpress | 184.20               |
| 🇩🇪 Alemanha | 🛍️ Shopee      | 317.67               |
| 🇦🇺 Austrália | 🧡 Etsy       | 189.46               |

Esses valores refletem a receita líquida média após aplicar descontos.

# 📦 Análise de Logística e Performance de Vendas  

## 🌍 Países com Maiores Valores Médios por Pedido  
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

## 🚧 Gargalos Logísticos Identificados

Os gargalos logísticos podem envolver tempo excessivo de entrega ou custo acima da média. Aqui estão algumas observações:

- **Custo elevado:**  
  Os países com os maiores descontos aplicados (indicando possíveis altos custos logísticos) são:  
  - 🇦🇺 Austrália: 86.68  
  - 🇬🇧 Reino Unido: 86.51

- **Possíveis atrasos:**  
  Caso tenhamos dados de prazo de entrega, poderíamos verificar se esses custos refletem dificuldades operacionais, como transporte internacional demorado.

## 📉 Regiões com Baixa Performance & Ações de Melhoria

Para identificar regiões com baixo desempenho, podemos analisar fatores como menor receita líquida e alto custo logístico.

## 🔍 Regiões com Baixo Desempenho

- 🇫🇷 França e 🇯🇵 Japão apresentam pedidos menores e descontos relativamente altos.

## 🚀 Sugestões de Melhoria

- 🚚 **Revisão de rotas e fornecedores:** Otimizar transportadoras e armazenagem para reduzir custos e prazos de entrega.  
- 📈 **Promoção de canais alternativos:** Explorar Shopee em mercados com baixa performance para ampliar vendas.  
- 💳 **Estratégia de precificação:** Ajustar preços e descontos para tornar ofertas mais competitivas nos países de menor demanda.
