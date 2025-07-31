# ROTA Business Intelligence (BI) - Airbnb
Projeto corresponde a segunda rota proposta pelo bootcamp Jornada de Dados da Laboratória Brasil.

# **✔Ficha Técnica**: Airbnb

---

## **📰 Título do Projeto**: **BI Airbnb**

---

- **🎯 Objetivo:**
    
    Este projeto tem como objetivo a exploração e análise de dados relacionados à disponibilidade de quartos no Airbnb e compreender os fatores que influenciam a ocupação do alojamento.
    

---

- **👩🏽‍🦱 Equipe:**
    
    O projeto individual feito por **Socorro Moura.**
    

---

- **⚙ Ferramentas e Tecnologias**:
    - Big Query - SQL
    - Power BI
    - Google Sheets

---

- **💻 Processamento e análises:**
    - **PROCESSAMENTO:**
        1. **Criação de projeto e importação** do *dataset* disponibilizado no BigQuery:
            1. **Projeto**: rota-airbnb-465302
            2. **Conjunto de dados**: dataset_airbnb
            3. **Tabelas:**
                1. *hosts*
                2. *reviews*
                3. *rooms*
        2. O passo seguinte foi o **tratamento** de dados:
            1. *Identificar e tratar valores nulos ✔*
            2. *Identificar e tratar valores duplicados ✔*
            3. *Identificar e tratar dados fora do escopo de análise ✔*
            4. *Identificar e tratar dados discrepantes em variáveis categóricas ✔*
            5. *Identificar e tratar dados discrepantes em variáveis numéricas ✔*
        3. Relacionei as tabelas:
        
        ![Relacionamentos.png](attachment:f4682007-081e-4840-b62b-37ebe1b13d49:Relacionamentos.png)
        
        1. Utilizei fórmulas DAX:
        
        ![dax.png](attachment:85d5eddb-f877-4df5-a4a2-d717720dc02a:dax.png)
        
    - **ANÁLISE:**
        1. **Etapas a serem realizadas no Power BI:**
            1. *Agrupar dados de acordo com variáveis categóricas ✔️*
            2. *Visualizar as variáveis categóricas ✔️*
            3. *Aplicar medidas de tendência central ✔️*
            4. *Visualizar distribuição ✔️*
            5. *Aplicar medidas de dispersão* ✔️
            6. Ver o comportamento dos dados ao longo do tempo ✔️
        2. Ao final, resumo no **Dasboard:**
        
        ![dashboard.png](attachment:798e696c-f792-403e-a37c-75d27a7b95fb:dashboard.png)
        

---

- ⚠ **Resultados e Conclusões:**
    
    **1. Ajustar precificação em Brooklyn**
    
    - Com base na comparação com Manhattan: revisar a política de preços e explorar imóveis de maior valor agregado em Brooklyn pode aumentar significativamente o faturamento.
    
    **2. Explorar o potencial de Queens**
    
    - Por ter mais hóspedes que Bronx e Staten Island, e ainda baixa receita: Investir em experiências diferenciadas, anúncios otimizados e propriedades com melhor infraestrutura pode impulsionar o faturamento em Queens.
    
    **3. Diagnosticar a baixa demanda nas regiões periféricas**
    
    A baixa atratividade do Bronx e de Staten Island pode ser investigada com foco em logística, segurança ou falta de anúncios competitivos.
    
    **4. Segmentar o marketing com base no perfil regional**
    
    - Os dados sugerem perfis de hóspedes distintos por região. Estratégias de marketing personalizadas podem aumentar conversão e rentabilidade.
    
    **5. Diversificação para reduzir dependência de Manhattan e Brooklyn**
    
    - Concentrar 82% dos hóspedes em apenas duas regiões representa risco. A diversificação pode ser chave para estabilidade a longo prazo.

---

- **🔐Limitações/Próximos Passos**: limitações ou desafios encontrados durante o projeto.
    1. **Previsão de faturamento estimada:**
        1. Os cálculos de faturamento são baseados em estimativas (diária × disponibilidade × hóspedes) e podem não refletir a receita real recebida por anfitriões.
    2. **Sem diferenciação de localização dentro das regiões:**
        1. Regiões como Manhattan ou Brooklyn são amplas e heterogêneas. A análise agrupada pode esconder padrões locais relevantes (ex: bairros badalados x residenciais).

---

- **🔗Links de interesse:**
    - Pré-processamentos - BigQuery - [**LINK**](https://drive.google.com/file/d/1NE4sqrWFstlve0cVUF442j61mokidvkW/view?usp=sharing)
    - Apresentação - Slides -[**LINK**](https://docs.google.com/presentation/d/1vcOKqpKnO4iZLSkWpGsvnuqkaqYBAvcfnKafaMZHUFQ/edit?usp=sharing)
    - Apresentação **Vídeo** - Loom - [**LINK**](https://www.loom.com/share/ef71735c2e8045929feafad9faba7dfb?sid=98b35e3c-f6cc-48ed-8de2-d301e85aa22b)
    - Documentação - [**LINK**](https://docs.google.com/document/d/163ottuS67zYSO3Gbvqvb0AMVF8OUe6v5aIt3sbdeILg/edit?usp=sharing)
    - Arquivo - Power BI - [**LINK**](https://drive.google.com/file/d/1TGPD086f7mVI8NBM7rrCYBeIWb6TuhNJ/view?usp=sharing)
