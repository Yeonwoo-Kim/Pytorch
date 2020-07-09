## Data description

* ### breast cancer diagnosis

  - 어찌고 저찌고~~~~~~~~~~~~~~~
  
  - [source code]()
   

* ### Boston Housing Price

  - gg

* ### cabbage_price

  - gg

* ### diabetes diagnosis

  - gg

* ### Animal Classification

  - gg

* ### Danyang Water quality of sewage
  - Estimate the number of E. coli in water quality using discharge water data at Danyang Sewage Treatment Plant.<br>
  
  - <b>Data summary</b><br>
    outflow (방류량), temp 수온(℃), 방류수질(pH(-)), 방류수질(BOD(㎎/L)), 방류수질(COD(㎎/L)), 방류수질(SS(㎎/L)), 방류수질(T-N(㎎/L)), 방류수질(T-P(㎎/L)), Escherichia coli(개/㎖)
  
  - [data source](https://www.data.go.kr/data/15053866/fileData.do)
  
  - [source code](https://github.com/Yeonwoo-Kim/Pytorch/blob/master/script/water_quality.ipynb)

* ### peak wave height
  - This is the maximum significance crest prediction problem using the observations of the Ocean Data Buoy report.<br>
    The Ocean Data Buoy observes marine weather phenomena with various weather equipment at sea level.
    Depending on the shape, there are two types, ship type and disk type, and Pagoe and Paegui measure and analyze the moving acceleration of the buoyant body at sea level.
    For the Train data, it consists of daily data from 2014 to 2018, so you can study it to predict test data.
    The marine weatherman used the data from Ulleungdo Island.
   
  - <b>Data summary</b><br>
    point, date, average wind speed (m/s), average air pressure (hPa), average relative humidity (%), average temperature (°C), average water temperature (°C), average maximum       wave height(m), average significant wave height (m), maximum wave height (m), average wave period (sec), max wave period (sec), max significant wave height(m)
    
    
  - significant wave height: The average of the crests observed during the arbitrary observation time, corresponding to one-third of the total, in the order in which the wave       heights are high.
    Maximum wave height: The largest wave height observed during the arbitrary observation time.<br>
    Mean wave height: Mean crest of the observed wave height during the arbitrary observation time.<br>
    
  - [data source](https://data.kma.go.kr/data/sea/selectBuoyRltmList.do?pgmNo=52&tabNo=1)
  
  - [source code](https://github.com/Yeonwoo-Kim/Pytorch/blob/master/script/peak_wave_height.ipynb)

* ### sea ice extent

  - data source
    - [car_reg](http://www.index.go.kr/potal/main/EachDtlPageDetail.do?idx_cd=1257)
    - [cow](http://www.fao.org/faostat/en/#data/QL)
    - [gdp](https://data.oecd.org/gdp/gross-domestic-product-gdp.htm)
    - [Carbon](https://www.kaggle.com/ucsandiego/carbon-dioxide?select=archive.csv)
    - [seaice_extent](https://www.kaggle.com/nsidcorg/daily-sea-ice-extent-data)
