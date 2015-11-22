# R在開放數據的加值應用
- 這場演講講述開放數據在三種數據分析類型的加值應用
- 投影片：[(繁體)](http://johnsonhsieh.github.io/OpenDataWithR/index_zh_tw.html)、[(簡體)](http://johnsonhsieh.github.io/OpenDataWithR/index.html)


## 掌握現況
- 社區醫療群地圖 (李昕迪 醫師)
  - R包：`ggmap` + `rCharts` + `shiny`
  - 參考: [slide](http://mcdlee.github.io/gisVisualization), [shinypp](https://mcdlee.shinyapps.io/communitymedcare), [github repo](https://github.com/mcdlee/communitymedcare)
  
- NPO城鄉多樣性比較 (謝宗震 博士)
  - R包：`rvest` + `dplyr` + `ggplot2` + `iNEXT`
  - 參考：[data1](https://github.com/JohnsonHsieh/OpenDataWithR/blob/master/data/NGO%20lists%20-%20%E8%81%AF%E5%90%88%E5%8B%B8%E5%8B%9F.csv), [data2](https://github.com/JohnsonHsieh/OpenDataWithR/blob/gh-pages/npo-type.csv), [github repo](https://github.com/JohnsonHsieh/OpenDataWithR/)

## 洞悉因素案例
- 找出火災風險熱區 (New Orleans Analytics)
  - R包：`reshape` + `plyr` + `dplyr` + `ROCR` + `maps` + `maptools` + `sp` + `rgdal`
  - 參考：[github repo](https://github.com/cno-opa/smoke-alarm-outreach), [report](http://nola.gov/performance-and-accountability/nolalytics/files/full-report-on-analytics-informed-smoke-alarm-outr/)

## 預測未知案例
- 豪宅房價預測 (謝宗震 博士)
  - R包：`mgcv`
  - 參考：[data](https://github.com/JohnsonHsieh/OpenDataWithR/blob/master/data/dat1.rds), [github repo](https://github.com/JohnsonHsieh/study-area-statR)
  
- NPO總數估計 (謝宗震 博士)
  - R包：`rvest` + `CARE1` + `shiny`
  - 參考: [data](https://github.com/JohnsonHsieh/OpenDataWithR/blob/master/data/npoList.csv), [hackpad](https://dsp.hackpad.com/-NPO-WcWRyZSZFge), [hackathon](http://hack.dsp.im/d4sg-hackathon/https%253A%252F%252Fgoo.gl%252FPFEpD2)
