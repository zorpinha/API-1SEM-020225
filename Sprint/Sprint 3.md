# Sprint 3: Reconstrução do Modelo de Dados e Dashboard Interativo

> Apesar de imprevistos que adiaram a data de entrega, a Sprint 3 marcou a reconstrução completa do nosso modelo financeiro, resultando em uma base de dados mais robusta e detalhada, e a entrega do dashboard em Power BI para análise visual.

As entregas principais foram:
1.  **Planejamento Estratégico em Excel:** Um modelo financeiro e operacional totalmente reestruturado.
2.  **Dashboard em Power BI:** Uma ferramenta interativa para análise dos indicadores de negócio.
3.  **Relatório Final (esta página):** A documentação de todo o processo e resultados.

---

## ⚙️ Reconstrução e Evolução do Modelo em Excel

Após a corrupção de dados na Sprint anterior, optamos por reconstruir a planilha do zero. O resultado foi um modelo muito mais granular, com o dobro de abas, permitindo uma análise mais profunda e precisa.

<details>
<summary>Visualizar a nova estrutura geral da planilha</summary>

![Nova estrutura com mais abas](https://github.com/user-attachments/assets/bd99b875-77a8-4a4b-854d-eb0853ec975f)

</details>

### As principais alterações foram agrupadas nas seguintes categorias:

<br>

<details>
<summary><b>Clique para ver as alterações em Projeções, Vendas e Receita</b></summary>

- **1. Otimização da Pesquisa de Mercado:** Os dados dos modelos de celulares foram reformatados para simplificar o uso em fórmulas complexas.  
  ![image](https://github.com/user-attachments/assets/a3610e65-631f-4ddd-a533-2ee2251a6df4)

- **2. Reestruturação da Previsão de Vendas:** A aba foi remodelada com orientação vertical (meses nas linhas), alinhada à demografia e sazonalidade. Novos critérios, como lotes mínimos para arredondamento, foram adicionados para evitar compras excessivas.
  ![image](https://github.com/user-attachments/assets/f0b7775f-350c-4338-9df3-a72a6a5cf6f0)

- **3. Validação dos Lotes de Celulares:** Para maior clareza, a gestão de lotes foi movida para uma aba dedicada. Incluímos uma fórmula de validação que compara o total de lotes com a previsão de vendas, garantindo que os números estejam sempre corretos.
  ![image](https://github.com/user-attachments/assets/666afae6-5a80-426b-93f1-734cdc8a6e33)

- **4. Correção na Compra e Venda de Celulares:** Identificamos e corrigimos um erro no cálculo do preço de compra e venda. A nova estrutura, baseada na tabela de referência, garante valores precisos e uma organização mais clara.
  ![image](https://github.com/user-attachments/assets/46819d6b-0af1-45e1-98c6-88292115839d)
  ![image](https://github.com/user-attachments/assets/1978ece9-7e6c-4370-a154-2aa2334a5307)


- **5. Criação da Aba de Pacotes de Serviço:** Adicionamos a receita proveniente de pacotes de serviços, um item que havia sido omitido por desatenção na sprint anterior, completando nossa visão de faturamento.
  ![image](https://github.com/user-attachments/assets/0c6d4834-4b2c-44c2-a15f-6d0bed4a847e)

</details>

<details>
<summary><b>Clique para ver as alterações em Custos, Operações e Infraestrutura</b></summary>

- **1. Gestão de Estoque (Armazém):** A aba foi reorganizada com uma visão mensal para cálculos mais precisos, considerando a demanda variável. Implementamos a regra de negócio de que o galpão (400 lotes) é alugado em frações de 25 lotes, otimizando o custo de armazenagem.
  ![image](https://github.com/user-attachments/assets/97f9b14f-15e1-4033-b32d-afc9ed321f94)

- **2. Otimização da Equipe e Infraestrutura:** A gestão de equipes foi separada em uma aba própria, com novos parâmetros de contratação. Implementamos uma lógica de contratação flexível (efetivos vs. temporários) para otimizar custos com pessoal, evitando demissões desnecessárias.  
  ![image](https://github.com/user-attachments/assets/360e04da-b829-43a8-aaf4-c222fe51a9d9)
   ![image](https://github.com/user-attachments/assets/0a746650-c799-4d43-873d-1e70b13fe077)


- **3. Custo de Infraestrutura Detalhado:** A qualidade da infraestrutura (ERBs e PAs) agora é um parâmetro selecionável, e os custos são calculados em abas separadas por região para melhor visualização.  
![image](https://github.com/user-attachments/assets/7b529622-7148-48e1-a44a-2e4d50146c0d)

- **4. Abas Dedicadas para Custos:** Criamos abas específicas para "Custo de Equipe" (incluindo contratações/demissões) e "Custo de Infraestrutura", facilitando a análise detalhada.
  ![image](https://github.com/user-attachments/assets/d3292af0-aa41-45b3-978b-5da7af928214)
  ![image](https://github.com/user-attachments/assets/625e1287-b3f8-4502-ab01-2a83e426eb26)

</details>

<details>
<summary><b>Clique para ver as alterações em Consolidação e Preparação para o Power BI</b></summary>

- **1. Consolidação de Custos Mensais:** Com a nova formatação, a junção de todos os custos em uma única aba de visão mensal se tornou muito mais prática e confiável.
  ![image](https://github.com/user-attachments/assets/ab30aa0c-e970-4f41-9ec9-b4172b81c9a2)

- **2. Análise de Retorno Mensal:** De forma similar, a aba de retorno mensal consolida todo o faturamento e subtrai os custos, oferecendo uma visão clara do resultado financeiro da empresa a cada mês.
  ![image](https://github.com/user-attachments/assets/c37341fd-3e54-40b6-b8e7-9f95b66cee0a)

- **3. Criação da "DataBase" para Power BI:** Todos os dados relevantes foram unificados em uma única tabela (aba "DataBase"), formatada como um fluxo de dados para ser facilmente importada e trabalhada no Power BI na criação dos indicadores.
  ![image](https://github.com/user-attachments/assets/3a666a30-d8ac-49b4-9168-740e3e60c9de)

</details>

<br>

### Conclusão da Reconstrução
Apesar do desafio inicial, a criação de uma nova planilha do zero permitiu corrigir inconsistências e erros de cálculo anteriores, resultando em um modelo financeiro significativamente mais preciso, detalhado e confiável.

---

## 📊 Dashboard em Power BI: Análise Visual dos Dados

Com a base de dados finalizada, criamos um dashboard interativo no Power BI. A ferramenta permite explorar os dados de forma visual, aplicar filtros e extrair insights rapidamente.

**Tela Principal de Navegação:**
![image](https://github.com/user-attachments/assets/afcaf95a-dd68-40ad-945f-bc3b8276c3d4)

Abaixo estão algumas das telas de análise criadas:

---

- **Análise de Vendas:** Acompanhamento de vendas de celulares e planos de internet, com filtros por mês e região.
<details>
<summary>Visualizar Dashboards de Vendas</summary>

![image](https://github.com/user-attachments/assets/59da23b0-6335-4324-b660-f4d850209e69)
![image](https://github.com/user-attachments/assets/b32680d3-7685-488b-b4ac-6bec651fedc3)

</details>

---

- **Análise de Operações:** Acompanhamento de compra de lotes e custos de armazenagem.
<details>
<summary>Visualizar Dashboards de Operações</summary>

![image](https://github.com/user-attachments/assets/8956fe14-cb6f-427e-85de-0580eaa7db11)
![image](https://github.com/user-attachments/assets/b4e8d83d-9573-467f-a73e-50f07e0def15)
</details>

---

- **Análise de RH:** Variação de contratações, custos com salários e necessidade de treinamento ao longo do ano.
<details>
<summary>Visualizar Dashboards de RH</summary>

![image](https://github.com/user-attachments/assets/110f0a59-3260-4063-8390-709fe18b485f)
![image](https://github.com/user-attachments/assets/83601e18-80e3-4fd1-b241-562d905811d2)
![image](https://github.com/user-attachments/assets/9833662c-8ead-41fb-8658-c3ffd250abbe)


</details>

---

- **Análise de Infraestrutura:** Acompanhamento dos custos de construção de ERBs e PAs por mês e região.
<details>
<summary>Visualizar Dashboard de Infraestrutura</summary>

![image](https://github.com/user-attachments/assets/6b32a667-0d7d-4117-b9a0-2687a401f5ea)
</details>
