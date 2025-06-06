# Sprint 2: Modelagem de Dados e Projeções Financeiras

Nesta Sprint, o foco foi aprofundar a análise de dados, transformando a pesquisa inicial em um modelo de negócios quantitativo. Guiados por 25 questões estratégicas, desenvolvemos a base de dados detalhada que servirá como alicerce para o futuro dashboard em Power BI.

O relatório completo desta etapa pode ser acessado no link abaixo:
- **[📄 Relatório Completo da Sprint 2 (PDF)](https://github.com/user-attachments/files/20628128/SPRINT.2.1.1.pdf)**

---

## 🏗️ O Novo Modelo de Dados

A principal entrega desta fase foi a evolução da nossa planilha, que agora conta com 5 novas abas totalmente integradas. Construímos um sistema dinâmico onde 99% dos dados estão vinculados, ou seja, qualquer alteração em um parâmetro ajusta o modelo como um todo, garantindo consistência e agilidade na análise de cenários.

Em nosso novo cenário, o market share foi atualizado para 20%

<details>
<summary>Visualizar a estrutura das novas abas</summary>

![Estrutura das novas abas da planilha](https://github.com/user-attachments/assets/fad07706-09ef-48cd-870b-60c02b4979ad)

</details>

O documento técnico detalhando a nova base de dados está disponível aqui:
- **[📄 Base de Dados Técnica (PDF)](https://github.com/user-attachments/files/20627602/Planilha.Base.de.Dados.-.Informacoes.Mercado.-.PI.I.GPI.-.2025.1.pdf)**

---

## 📊 Detalhamento das Análises

A seguir, apresentamos os principais componentes do nosso modelo financeiro e operacional.

### 📈 1. Previsão de Vendas

Para cada uma das 5 regiões do país, projetamos as vendas mensais dos 4 modelos de smartphone (Nacional/Importado, mais caro/mais barato). Esta projeção detalhada, baseada em um cenário ideal, nos permitiu calcular indicadores operacionais essenciais:

- **Cálculo de lotes de compra** para otimização de estoque.
- **Estimativa de EBR** (Estação Base de Rádio) necessárias.
- **Dimensionamento dos PAs** (Postos de Atendimento).
- **Número de equipes** de campo e de vendas necessárias.

<details>
<summary>Visualizar Planilha de Previsão de Vendas</summary>

![image](https://github.com/user-attachments/assets/a6a6086d-e495-421d-b3de-d4bf661bbc91)

</details>

### 💸 2. Estratégia de Custos e Precificação

Para definir o preço final ao consumidor e garantir a lucratividade, detalhamos a estrutura de custos e analisamos diferentes cenários de markup.

**Estrutura de Custos:**
- Aplicamos uma carga tributária de **30% sobre o custo dos celulares nacionais**.
- Aplicamos uma carga tributária de **40% sobre o custo dos celulares importados**.

**Análise de Markup:**
- Com base nos custos, calculamos e analisamos diferentes percentuais de markup para encontrar o ponto de equilíbrio ideal entre competitividade de preço e margem de lucro sustentável.

<details>
<summary>Visualizar Planilha de Custos e Markup</summary>

![image](https://github.com/user-attachments/assets/3e413de0-6005-4131-9118-b284e4aa77dc)
![image](https://github.com/user-attachments/assets/461a87d9-9e7a-4909-9be8-1008f0fd8fe9)

</details>

### 📦 3. Logística e Gestão de Estoque (Armazém)

A estratégia de compra foi definida em **lotes de 25 unidades** por modelo. Esta abordagem foi escolhida para otimizar os custos logísticos, reduzir o capital de giro imobilizado em estoque e obter melhores condições com os fornecedores.

<details>
<summary>Visualizar Planilha do Armazém</summary>

![image](https://github.com/user-attachments/assets/de2cb0a9-942b-488e-93d8-d38c49149929)

</details>

---

## ❗ Status e Impedimentos

- **Ponto de Atenção:** A aba **"Custos Estruturais e Retorno"** foi corrompida e seus dados foram perdidos durante o desenvolvimento. A equipe está ciente e avaliará o esforço necessário para a reconstrução em uma próxima etapa, caso seja definida como prioridade.
