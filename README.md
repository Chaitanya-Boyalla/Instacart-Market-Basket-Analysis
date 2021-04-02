# Instacart-Market-Basket-Analysis

**Kaggle competiton(Data Source):** https://www.kaggle.com/c/instacart-market-basket-analysis
 
### **Introduction:**
	Instacart, a grocery ordering and delivery app that allows customers to select products on their app or website and a personal shopper handpicks those products by in-store shopping and delivers the order. In this Kaggle Competition, Instacart made their anonymized data available for Machine Learning practitioners with an aim for best Machine Learning models to analyse customer reorder patterns and predict which products can a customer reorder based on their previous shopping data.
  
### **Business problem:**
	Groceries involve daily essentials, food products, skin care products and many more which are more likely to be reordered. This reordering behaviour will be common among everyone concerned with some products like daily essentials, food products and can be different with other products. Even if everyone needs some common type of products the choice differs in brands and other factors. For example everyone needs a shampoo but which shampoo they use depends on customer interest. The products that customers choose will depend on their taste, cultural diversity, lifestyle and other factors. But this ordering pattern can be analysed with a number of orders that were made by customers over time.
  The business requirement here is to predict which previously purchased products will be in customer’s next order. This model should be developed using anonymized data which contain millions of records open sourced by Instacart. This improves the user experience as well as business of Instacart. This is different from regular recommendation system problems. There is no cold start problem involved in this task i.e., our aim is to predict will an user reorder previously purchased products. This task does not expect to suggest new products to the customer.
  
### **Performance metric:** 
	Mean F1-score is the performance metric as per Kaggle competition but considering real world scenario f1-score on ‘1=will reorder’ is the performance metric on which models should be evaluated in particular. Further, recall of ‘will reorder’ can be observed.
  
***Go through 'Abstract.pdf' for detailed explanation of problem formulation, references and solving approach.***  
    

