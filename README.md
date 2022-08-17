The goal of this analysis  to answer the following question: Which factors play the most influential role in setting a car’s price? 

Dataset 

car_price.csv
A car dataset with 17 columns is explored and analyzed in this application. 

Columns:
- id            
- region        
- price         
- year          
- manufacturer  
- model         
- condition     
- cylinders     
- fuel          
- odometer      
- title_status  
- transmission  
- VIN           
- drive         
- size          
- type          
- paint_color   
- state         

Models used:
- Linear Regression
- Polynomial Regression
- Lasso Regression
- Ridge Regression

Most of these models seem to yield similar results. Using a degree 2 model yield worse results than just using a degree 1 model.

Technologies
- Python
- Pandas, Jupyter

Author: Katherine Lopez

Link: https://github.com/kalopez/practical_application_car_pricing

Summary of Findings:

Factors that influence car price in order of importance:¶
1.	Year 
2.	Odometer
3.	Cylinders
4.	S
