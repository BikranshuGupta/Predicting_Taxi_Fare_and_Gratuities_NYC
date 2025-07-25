<h1 align="center"> Predicting_Taxi_Fare_and_Gratuities_NYC-example.txt </h1>
<section>
  <h2>Overview</h2> <p> The goal of this project was to create a multiple lineae regression and random forest model to predict higher rider gratuity or not. This project utilized yellow taxi trips taken in New York City during 2017. The final random forest model performed with 86% accuracy and 72% precision determining what features were most important in separating low tippers from high tippers. Based on the model, the duration, distance, and cost of the trip were most influential in determining a generous tippere (>20%) vs a non generous one (<20%)</p>
</section>

<section>
  <h2>Business Understanding </h2> <p> According to salary.com the average salary for a New York Taxi Driver is around  $45,000. This salary is significantly low compared to a median rent value of $65,000 per month. It is important to understand what facctor encourages riders to leave tips in order to help drivers obtain a livable wage.</p>
</section>

<h2> Data Understading</h2> <p> The NYC Taxi and Limousine Commission data from  NYC.gov. The data consisted of approximately 408k unique trip and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set.
<img src="https://github.com/BikranshuGupta/Predicting_Taxi_Fare_and_Gratuities_NYC/blob/main/Image/tippers.jpg"> In connection to this, a feaor notture was engineered to represent if a ride was taken during rush hour or not. Multiple redundant columns were dropped and reformatted into the proper data type </p>

<h2> Modeling and Evaluation </h2><p> A random forest model comprising 100 decision trees was used to determine feature importance in who would tip generously or not. The below plot shows that trip duration, distance, and the cost of a fare were the Top 3 most important factors in determining a generous tipper from a non-generous one. The overall model performed with 86% accuracy and 72% precision. 
<img src="https://github.com/BikranshuGupta/Predicting_Taxi_Fare_and_Gratuities_NYC/blob/main/Image/Fig2.git.jpg"> </p>


