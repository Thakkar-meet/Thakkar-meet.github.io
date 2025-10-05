# Fuel Efficiency Analysis using the MPG Dataset

This project performs basic exploratory data analysis (EDA) on the **MPG (Miles per Gallon)** dataset using **Matplotlib** in Google Colab.  
The dataset provides details about various car models from different origins (USA, Europe, Japan) and includes attributes such as engine size, horsepower, weight, and fuel efficiency.

---

## Data Source

- **Dataset Name:** MPG Dataset  
- **Source:** Seaborn built-in dataset (originally from the UCI Machine Learning Repository)  
- **Citation:**  
  *Jeffrey C. Schlimmer (1987). Concept Acquisition: Analytic and Experimental Studies of Knowledge Acquisition. Machine Learning, 2, 287–294.*  
- **Access Method in Colab:**
  ```python
  import seaborn as sns
  df = sns.load_dataset("mpg").dropna()

## Weight vs MPG 
<img width="686" height="547" alt="image" src="https://github.com/user-attachments/assets/6ca1a7e1-1960-407a-914b-ffa8f3b6d0eb" /> 


The first observation to be made is that heavier cars have lower miles per gallon. Also as cylinder increases, cars shift toward heavier weights and lower miles per gallon.

## MPG vs number of cylinder 
<img width="578" height="445" alt="image" src="https://github.com/user-attachments/assets/b5a53ea1-ea07-4afe-aff0-8db14cce7323" />


Car with fewer cylinders will generally have higher MPG, showing better fuel efficiency and higher-cylinder engines consume more fuel. Therefore, engine size directly affects efficiency. 

## Average MPG over the years
<img width="700" height="547" alt="image" src="https://github.com/user-attachments/assets/a2519a29-4df8-4b82-8d6a-8dd7d7626e01" />


Here we expect to see an upward trend as cars became more fuel-efficient over time due to regulations and better technology. 

## Average MPG by origin
<img width="609" height="470" alt="image" src="https://github.com/user-attachments/assets/84007c67-bdc5-4eed-a0e7-3a207784672b" />


Japanese > Europe > USA. Japanese cars are generally more fuel efficient.


