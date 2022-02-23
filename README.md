# Flight-Fare-Prediction
In this project prediction of fare of flight is done based on number of attributes such as Airline, Date of Journey, Departure time, Arrival time. Duration of Journey and Total Halts etc...

### Data Source
Kaggle

### Data shape
(10683,11)

### Data columns
<b> 1)</b> Airline<br>
<b> 2)</b> Date of Journey<br>
<b> 3)</b> Arrival Time<br>
<b> 4)</b> Departue Time<br>
<b> 5)</b> Total number of halts<br>
<b> 6)</b> Source<br>
<b> 7)</b> Destination<br>
<b> 8)</b> Route<br>
<b> 9)</b> Journey Duration<br>
<b> 10)</b> Additinal Info<br>
<b> 11)</b> Fare <br>

 
### Steps Followed
<b>1)</b> Data Import<br>
<b>2)</b> Column Renaming<br>
<b>3)</b> Data cleaning or null value imputation<br>
<b>4)</b> Creating Visualization<br>
<b>5)</b> Train Test spilt<br>
<b>b6)</b> Apply feature selection<br>
   SelectKBest with mutual info regressor<br>
<b>7)</b> Model building<br>
      a) <b>Random Forest Regressor</b><br>
      b) <b>Random Forest Regressor with Feature selection</b><br>
      c) <b>Randome Forest Regressor with hyper parameter tuning</b><br>
   
### Results or Accuracy                                                                     
1) Random Forest Regressor 
     1) r2 score                                  <b>0.8031867447760775</b><br>
     2) Root Mean square error                    <b>2003.789602144077</b><br>   
     3) Mean absolute percentage error            <b>0.13045697267067724</b><br>
  
2) Random Forest Regressor with feature selection
     1) r2 score                                  <b>0.7842554982841852</b><br>
     2) Root Mean squared error                   <b>2097.9484596616935</b><br>    
     3) Mean absolute percentage error            <b>0.12984649250330227</b><br> 
     
3) Random Forest Regressor with hyper parameter tuning
     1) r2 score                                  <b>0.8259036484310706</b><br>
     2) Root Mean squared error                   <b>1884.602580409371</b><br> 
     3) Mean absolute percentage error            <b>0.14444768813815576</b><br>
       
### Model Selection on basis of r2score, MAE and MAPE
   Random Forest Regressor(RF) with hyper parameter tuning becoz, it has high r2score and lower MAE and MAPE amoungs all the three models. 

