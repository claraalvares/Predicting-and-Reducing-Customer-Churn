## Previsão e Redução de Rotatividade em Academias

### Sobre o Projeto  
O projeto tem como objetivo analisar dados dos clientes da rede de academias **Model Fitness** para identificar perfis de usuários, prever a probabilidade de rotatividade e propor estratégias de retenção. A partir da análise exploratória e da modelagem preditiva, serão desenvolvidas recomendações para reduzir a perda de clientes e melhorar os serviços oferecidos.

---

### Dados  
**Fonte:** /datasets/gym_churn_us.csv  
**Composição:**  
- **Informações do cliente:**  
  - `gender`: gênero.  
  - `age`: idade.  
  - `Lifetime`: tempo de associação do cliente (em meses).  
  - `Near_Location`: se o cliente mora ou trabalha perto da academia.  
  - `Partner`: se o cliente é funcionário de uma empresa parceira.  
  - `Promo_friends`: se a adesão foi via promoção "traga um amigo".  
  - `Phone`: se o cliente forneceu número de telefone.  

- **Status de associação e frequência:**  
  - `Contract_period`: período do contrato (1, 3, 6 ou 12 meses).  
  - `Month_to_end_contract`: meses restantes até o fim do contrato.  
  - `Group_visits`: se participa de aulas em grupo.  
  - `Avg_class_frequency_total`: frequência média semanal durante a associação.  
  - `Avg_class_frequency_current_month`: frequência média semanal no mês atual.  
  - `Avg_additional_charges_total`: gastos totais em serviços extras (café, produtos, massagem).  

- **Variável alvo:**  
  - `Churn`: indicador de rotatividade no mês em questão.  

---

### Método  
A análise será conduzida em cinco etapas principais:  
1. **Análise Exploratória de Dados (AED):** inspeção, limpeza e visualização dos dados.  
2. **Modelagem Preditiva:** treinamento de modelos de classificação (Regressão Logística e Floresta Aleatória) para prever a rotatividade.  
3. **Segmentação de Clientes:** agrupamento com K-means para identificar padrões e perfis.  
4. **Análise de Resultados:** avaliação dos fatores mais relevantes para a rotatividade.  
5. **Recomendações:** desenvolvimento de estratégias para melhorar a retenção.  

---

### Ferramentas Utilizadas  
- **Python 3.x**  
- **Bibliotecas:**  
  - `Pandas`: manipulação e análise de dados.  
  - `Matplotlib` & `Seaborn`: visualização de dados.  
  - `Scikit-learn`: modelagem preditiva e clustering.  
  - `SciPy`: estatísticas e testes de hipóteses.  

---

### Como Executar o Projeto  
1. Clone o repositório;  
2. Navegue até o diretório do projeto;  
3. Abra o projeto no seu IDE favorito;  
4. Instale as dependências;  
5. Execute o script principal.  

---

### Licença  
Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

----------------------

## Predicting and Reducing Customer Churn in Gyms

### About the Project  
This project aims to analyze customer data from the **Model Fitness** gym network to identify user profiles, predict churn probability, and propose retention strategies. Using exploratory analysis and predictive modeling, recommendations will be developed to reduce customer churn and improve service offerings.

---

### Data  
**Source:** /datasets/gym_churn_us.csv  
**Composition:**  
- **Customer Information:**  
  - `gender`: gender.  
  - `age`: age.  
  - `Lifetime`: membership duration (in months).  
  - `Near_Location`: whether the customer lives or works near the gym.  
  - `Partner`: whether the customer is an employee of a partner company.  
  - `Promo_friends`: whether membership was through the "bring a friend" promotion.  
  - `Phone`: whether the customer provided a phone number.  

- **Membership and Attendance Status:**  
  - `Contract_period`: contract duration (1, 3, 6, or 12 months).  
  - `Month_to_end_contract`: months remaining until the contract expires.  
  - `Group_visits`: participation in group classes.  
  - `Avg_class_frequency_total`: average weekly attendance throughout the membership.  
  - `Avg_class_frequency_current_month`: average weekly attendance in the current month.  
  - `Avg_additional_charges_total`: total spending on extra services (café, products, massage).  

- **Target Variable:**  
  - `Churn`: churn indicator for the current month.  

---

### Method  
The analysis will be conducted in five main steps:  
1. **Exploratory Data Analysis (EDA):** inspection, cleaning, and visualization of the data.  
2. **Predictive Modeling:** training classification models (Logistic Regression and Random Forest) to predict churn.  
3. **Customer Segmentation:** clustering with K-means to identify patterns and profiles.  
4. **Results Analysis:** evaluating the most relevant factors for churn.  
5. **Recommendations:** developing strategies to improve retention.  

---

### Tools Used  
- **Python 3.x**  
- **Libraries:**  
  - `Pandas`: data manipulation and analysis.  
  - `Matplotlib` & `Seaborn`: data visualization.  
  - `Scikit-learn`: predictive modeling and clustering.  
  - `SciPy`: statistics and hypothesis testing.  

---

### How to Run the Project  
1. Clone the repository;  
2. Navigate to the project directory;  
3. Open the project in your favorite IDE;  
4. Install dependencies;  
5. Run the main script.  

---

### License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
