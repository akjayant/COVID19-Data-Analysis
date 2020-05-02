# COVID19 Data Analysis

## 1) Forecasting:
     Used ARIMA To predict/forecast numbers of COVID19 cases in INDIA, ITALY, USA, BELGIUM :
     #### Highlight -  (Trained till 29rd April and forecasting for next 7 days)
     example plot - 
   ### India
   Training - 
   
   ![India](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/INDIA_training.png)
   
   
   Forecasting - 
   
   ![India](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/india_forecasting.png)
   
   Forecasted Values -
   
*CI - (95% Confidence interval)

|Date|Confirmed|Confirmed CI|Recovered	|Recovered CI|Deaths|Deaths CI|
|---|---|---|---|---|----|---|
|2020-04-30|34876|[34561, 35192]|9080|[8983, 9178]|1144|[1132, 1157]
|2020-05-01|36620|[36140, 37101]|9776|[9613, 9939]|1218|[1196, 1239]
|2020-05-02|38439|[37773, 39104]|10467|[10197, 10736]|1287|[1255, 1319]
|2020-05-03|40321|[39465, 41176]|11158|[10764, 11551]|1359|[1312, 1406]
|2020-05-04|42163|[41081, 43245]|11879|[11354, 12403]|1433|[1372, 1493]
|2020-05-05|44051|[42692, 45410]|12583|[11901, 13265]|1504|[1428, 1581]
|2020-05-06|45933|[44309, 47557]|13314|[12470, 14158]|1580|[1486, 1673]
|2020-05-07|47867|[45956, 49778]|14044|[13020, 15067]|1654|[1543, 1765]






  ### Italy
   Training - 
   
   ![Italy](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/italy_training.png)
   
   
   Forecasting - 
   
   ![Italy](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/italy_forecasting.png)
   
  Forecasted Values -
Date|Confirmed|Confirmed CI|Recovered|Recovered CI|Deaths|Deaths CI|
|---|---|---|---|---|----|---|
|2020-04-30|205258|[204221, 206295]|73475|[72701, 74249]|28055|[27916, 28193]
|2020-05-01|206931|[205345, 208518]|75644|[74179, 77109]|28456|[28218, 28695]
|2020-05-02|208569|[206257, 210880]|77751|[75442, 80060]|28815|[28427, 29204]
|2020-05-03|210322|[207262, 213382]|79801|[76566, 83037]|29157|[28574, 29740]
|2020-05-04|212105|[208079, 216132]|81798|[77559, 86037]|29522|[28740, 30305]
|2020-05-05|213845|[208595, 219096]|83743|[78442, 89044]|29892|[28906, 30877]
|2020-05-06|215446|[208685, 222207]|85639|[79227, 92051]|30243|[29034, 31451]
|2020-05-07|216910|[208442, 225377]|87489|[79924, 95053]|30589|[29139, 32039]



## 2) Cluster Analysis - 
Download covid_19_*.html in ./interactive graph/
### Data source - Incredible team of covid19india.org
     1) To check for patterns in sub-graphs if present in high number and longer/denser chain 
     may imply community transmission.
 #### Highlight - 1 (Till 23rd April available details of ~1500 patients)
 
  ![pattern](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/full.png)
  
     2) State-wise analysis : to check whether there was transfer of infection from one state 
        to another due to travel or any other reasons
        
 #### Highlight - 2 (Till 23rd April available details of ~1500 patients)
 ![State-wise analysis India](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/top_8.png)
  
  *Paired Analysis : Delhi-UP,Rajasthan-Gujarat,Maharashtra-MP, Kerala-Tamil Nadu results in ./images/ & ./interactive_graphs/




     

