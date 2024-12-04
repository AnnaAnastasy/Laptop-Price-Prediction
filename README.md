# Laptop Price Prediction  

## Project Overview  
This project aims to predict laptop prices based on various features such as brand, processor type, RAM, storage capacity, and other specifications. Using regression techniques, the notebook provides insights into how different laptop attributes influence pricing, making it an excellent starting point for beginners in data science.  

## Target Audience  
This project is designed for beginners in data science looking to learn how to preprocess data, build regression models, and evaluate their performance.  

## Technologies Used  
The project leverages the following Python libraries:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scipy`  
- `scikit-learn`  

## Dataset Details  
The dataset contains information about laptops, including:  
- **Features**: Brand, processor type, RAM, storage capacity, graphics card, weight, operating system, warranty, and more.  
- **Target**: Price of laptops.  
- **Other Details**: Includes additional metadata such as ratings and reviews.  

## Instructions  
### Installation  
Before running the notebook, ensure you have Python installed along with the necessary libraries. You can install the required libraries using the following command:  

```bash  
pip install pandas numpy matplotlib seaborn scikit-learn scipy  
```  

## Results  
- **Model Performance**:  
  - R² on training data: **0.8448**  
  - R² on testing data: **0.8169**  
- Residual analysis confirms that the residuals are normally distributed, indicating a well-fitted model.  

## Acknowledgments  
This project uses data sourced from [Kaggle](https://www.kaggle.com/code/annastasy/laptop-price-predictions-beginner-friendly).  
