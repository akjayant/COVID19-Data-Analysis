# COVID19 Data Analysis

## 1) Forecasting:
     Used ARIMA To predict/forecast numbers of COVID19 cases in INDIA, ITALY, USA, SPAIN :
     #### Highlight -  (Trained till 29rd April and forecasting for next 7 days)
     example plot - 
   ### India
   training - 
   ![India](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/INDIA_training.png)
   
   forecasting - 
   ![India](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/india_forecasting.png)
   
   Values -
   
|Date| Confirmed|Recovered|Deaths|
|-----|-----|------|-----|
2020-04-30|34876.921219|9080.866314|1144.559756
2020-05-01|36620.997641|9776.454077|1218.424487
2020-05-02|38439.044994|10467.364391|1287.275389
2020-05-03|40321.03655|11158.053847|1359.420128
2020-05-04|42163.363068|11879.389996|1433.014994
2020-05-05|44051.643545|12583.516854|1504.704122
2020-05-06|45933.409976|13314.415654|1580.314252
2020-05-07|47867.515026|14044.127166|1654.341421

  ### Italy
   training - 
   ![Italy](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/italy_training.png)
   
   forecasting - 
   ![Italy](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/italy_forecasting.png)
   
   Values -
|Date| Confirmed|Recovered|Deaths|
|-----|-----|------|-----|
|2020-04-30|205258.280455|73475.740964|28055.244312
|2020-05-01|206931.928058|75644.475967|28456.572283
|2020-05-02|208569.169255|77751.112023|28815.640814
|2020-05-03|210322.195962|79801.934184|29157.389528
|2020-05-04|212105.918978|81798.432166|29522.746073
|2020-05-05|213845.926064|83743.576215|29892.290301
|2020-05-06|215446.326560|85639.661019|30243.061754
|2020-05-07|216910.344679|87489.057069|30589.422327



## 2) Cluster Analysis - 
Download covid_19_*.html in ./interactive graph/
### Data source - Incredible team of covid19india.org
     1) To check for patterns in sub-graphs if present in high number and longer/denser chain 
     may imply community transmission.
 #### Highlight - 1 (Till 23rd April available details of ~1500 patients)
 
  [pattern](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/full.png)
  
     2) State-wise analysis : to check whether there was transfer of infection from one state 
        to another due to travel or any other reasons
        
 #### Highlight - 2 (Till 23rd April available details of ~1500 patients)
 ![State-wise analysis India](https://github.com/akjayant/COVID19-Data-Analysis/blob/master/images/top_8.png)
  
  *Paired Analysis : Delhi-UP,Rajasthan-Gujarat,Maharashtra-MP, Kerala-Tamil Nadu results in ./images/ & ./interactive_graphs/




     

