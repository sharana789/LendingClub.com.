# LendingClub.com.
Decision Trees and Random Forest Project

**Objective**: To predict whether borrowers will fully repay their loans using Lending Club data from 2007-2010.

**Data Source**: Lending Club dataset, containing information about loan applications, including features such as credit policy, loan purpose, interest rate, and borrower’s financial details.

### **Steps Involved**

1. **Data Exploration**:
   - **Histograms**: Compared FICO score distributions by credit policy and loan repayment status.
   - **Countplot**: Visualized the count of loans by purpose and repayment status.
   - **Jointplot**: Analyzed the relationship between FICO score and interest rate.
   - **LMPlot**: Investigated the trend between interest rate and FICO score across different credit policies and repayment statuses.

2. **Data Preparation**:
   - **Feature Engineering**: Converted categorical variables into dummy variables to include in the model.
   - **Train-Test Split**: Split the data into training and testing sets to evaluate model performance.

3. **Model Training**:
   - **Decision Tree**:
     - Trained a Decision Tree Classifier on the training data.
     - Evaluated performance using classification report and confusion matrix.
   - **Random Forest**:
     - Trained a Random Forest Classifier on the training data.
     - Evaluated performance similarly and compared with the Decision Tree model.

4. **Model Evaluation**:
   - **Metrics**: Compared models using precision, recall, and F1 score.
   - **Results**: Random Forest typically performed better, showing improved accuracy and generalization over the Decision Tree.

### **Key Findings**

- **Random Forest vs. Decision Tree**: Random Forest generally outperformed the Decision Tree due to its ensemble learning approach, which reduces overfitting and improves prediction accuracy.
- **Feature Impact**: FICO score, loan purpose, and interest rate are significant predictors of loan repayment.

### **Conclusion**

The project demonstrates the process of using machine learning algorithms to predict loan repayment, highlighting the effectiveness of Random Forest in improving model performance compared to a single Decision Tree. Further feature engineering and model tuning could enhance prediction accuracy.
