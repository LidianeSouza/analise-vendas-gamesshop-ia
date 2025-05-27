# 📊 Análise de Vendas com IA – GamesShop

## 🏢 Sobre a empresa

A **GamesShop** é uma fabricante global de consoles de videogame. Seu foco está exclusivamente na **produção dos equipamentos**, enquanto a **distribuição e as vendas** são realizadas por empresas terceiras. Com alcance internacional, os produtos da GamesShop estão disponíveis em diversos países, o que traz desafios relacionados à **logística**, **popularidade regional dos produtos** e **consolidação de dados** de diferentes fontes.

---

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo utilizar **inteligência artificial** e **engenharia de prompts** para analisar relatórios de vendas da **GamesShop** e extrair **insights estratégicos**. A análise é baseada em planilhas consolidadas de vendas de terceiros, permitindo transformar **dados brutos** em **informações úteis para o fabricante**.

**🤖 Abordagem Utilizada:** Com o uso de ferramentas como o **ChatGPT** e o **Microsoft Copilot**, foram desenvolvidas análises orientadas por perguntas específicas (prompts), respondendo a questões relevantes para a tomada de decisão da empresa.

**⚙️ Diferenças entre as ferramentas utilizadas:**

- **ChatGPT (versão gratuita):**  
  - Possui **limite na quantidade de análises que podem ser feitas**.  
  - **Gera gráficos** com base nos próprios insights produzidos em resposta aos prompts.
  - Permite carregar **mais de uma planilha ao mesmo tempo** (ex: foi possível anexar 3 planilhas com dados brutos).
  - **Foi utilizado exclusivamente no conjunto de prompts do Item 1 ("Produtos Mais Populares por País") devido à limitação de interações da versão gratuita.**
    
- **Microsoft Copilot:**  
  - **Não possui limite na quantidade de análises que podem ser realizadas**.
  - **Gera o código ou fórmula necessária**, mas não cria gráficos automaticamente — é necessário executar o código gerado.
  - Permite carregar **apenas uma planilha por vez**, idealmente com os dados já processados.
  - **Foi utilizado em todos os demais conjuntos de prompts (Itens 2, 3 e Bônus), permitindo maior profundidade analítica.**

---

## 💡 Benefícios da abordagem

- Facilita a análise para usuários não técnicos.
- Permite gerar relatórios claros e prontos para apresentação.
- Combina o melhor das ferramentas da Microsoft com o potencial da IA da OpenAI.

---

## 🧭 Escopo da Análise

- 📦 Consolidar bases de dados de vendas de distribuidores e varejistas;
- 🌍 Identificar **os produtos mais populares em cada país**;
- 🚚 Obter **insights sobre transporte e logística**, desde a saída da fábrica até o momento da venda;
- 📈 Transformar dados de vendas em **informações relevantes para decisões de negócio**, como projeção de demanda, regionalização da produção e otimização da cadeia de suprimentos.

---

## 🤖 Ferramentas e Tecnologias Utilizadas

- 🧠 **ChatGPT (OpenAI)** – Para análise de dados via prompts estruturados  
- 🤖 **Microsoft Copilot** – Para assistência na criação de conteúdo e automação de análises  
- 📊 **Excel / Planilhas Google** – Para visualização e preparação inicial das planilhas  
- 📝 **Markdown** – Para documentação dos prompts e dos insights  
- 💾 **CSV** – Formato principal dos dados analisados  

---

## ✍️ Exemplos de Prompts Aplicados

Alguns exemplos de perguntas aplicadas à IA durante o processo:

- “Quais são os 3 produtos mais vendidos por país?”
- “Quais países têm o maior custo logístico médio?”
- “Existem gargalos logísticos (tempo ou custo acima da média)?”
- “Quais decisões estratégicas podem ser tomadas com base nesses dados?”

Todos os prompts utilizados estão documentados no arquivo [`prompts/prompts_analise.md`](prompts/prompts_analise.md).

---

## 💡 Principais Insights Obtidos

- O produto **"NEW MEGANIUM RG 40XXV"** foi destaque no Canadá e Japão.
- Os maiores valores médios por pedido ocorrem principalmente em **Shopee e AliExpress**, sugerindo que esses canais possuem produtos de ticket mais alto nesses países.
- Os meses de **junho, julho e agosto** tiveram os maiores volumes de vendas.
- Podemos destacar que os **EUA, Canáda e Reino Unido** possuem **alta demanda** e poderiam se beneficiar de produção descentralizada para reduzir custos e melhorar prazos de entrega. 

Mais detalhes no arquivo [`insights/insights_finais.md`](insights/insights_finais.md).

---

## 🧑‍💻 Contribuição

Este projeto faz parte dos meus estudos práticos sobre **análise de dados com apoio de inteligência artificial**. Se você quiser trocar ideias, sugerir melhorias ou tiver feedback, fique à vontade para me chamar!

---

## 🔗 Links Úteis

- [Portal Microsoft Azure](https://portal.azure.com)  
- [Microsoft Learn – Treinamentos Gratuitos](https://learn.microsoft.com/pt-br/training/)  
- [ChatGPT da OpenAI](https://chat.openai.com)  
- [Microsoft Copilot](https://www.microsoft.com/pt-br/microsoft-copilot)

