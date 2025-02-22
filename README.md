# **Video Game Sales Prediction Project**

## **1. Project Goal**
The objective of this project is to predict **global video game sales** based on various factors, including regional sales and game-related attributes. By applying machine learning techniques, the project aims to build a model that accurately estimates total sales.

## **2. Input and Output Features**
### **Input Features (Independent Variables)**
- **Platform**: The gaming platform (e.g., PS4, Xbox, PC)  
- **Genre**: The category of the game (e.g., Action, Sports, RPG)  
- **Publisher**: The company responsible for releasing the game  
- **Year_of_Release**: The year the game was released  
- **NA_Sales**: Sales in North America  
- **EU_Sales**: Sales in Europe  
- **JP_Sales**: Sales in Japan  
- **Other_Sales**: Sales in other regions  

### **Output Feature (Dependent Variable)**
- **Global_Sales**: The total worldwide sales of a game  

## **3. Steps in Making the Project**
### **A. Data Preprocessing & Cleaning**
- Load the dataset using **Pandas**  
- Check for missing values and handle them appropriately  
- Convert categorical data into numerical form if needed  
- Normalize or scale numerical features if required  
- Drop unnecessary columns that do not contribute to predictions  

### **B. Data Visualization**
- **Count Plot**: Displays the number of video games in different categories.  
- **Scatter Plot - Global Sales Over the Years by Platform**: Shows the distribution of global sales over different years across various platforms.  
- **Bar Plot - Regional Sales by Genre**: Analyzes how sales vary across different regions based on game genres.  
- **correlation heatmap**
  
### **C. Model Selection and Training**
- Apply **Linear Regression** to predict global sales  
- Train the model using the available dataset  
- Evaluate performance using:  
  - **R-squared (R²)**: Measures how well the model fits the data  
  - **Mean Squared Error (MSE)**: Measures prediction error  

## **4. Results and Conclusion**
- The **R-squared value is 0.99999**, indicating an almost perfect fit.  
- The **Mean Squared Error (MSE) is 2.69e-05**, suggesting extremely low error.  
- These results confirm that the model can **accurately predict global video game sales** using the provided features.  
