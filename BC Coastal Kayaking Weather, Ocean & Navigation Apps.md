---
Publish Status: Published
---
### 整合 / 導航

[**Navionics Boating**](https://apps.apple.com/us/app/navionics-boating/id744920098)  
海圖 + tide / current layer + route planning (整合視圖, 不是預測核心)

[**Garmin Marine Handhelds and Smartwatches**](https://www.garmin.com/en-CA/c/marine/handhelds-gps-and-watches/)  
實際導航 / track / 安全備援 / 天氣預報

### 天氣

**[WeatherCan](https://apps.apple.com/ca/app/weathercan/id1334221563) | [Marine Forecasts and Warnings for Canada](https://weather.gc.ca/marine/index_e.html)**  
- 官方預報與警報 (Marine Forecast / Wind Warning / Buoy) -> 用來確認風險底線
- Marine Forecasts and Warnings for Canada 是加拿大氣象局針對本地氣象提出預報/警報, Kayak Expedition 必聽.

**[PredictWind](https://apps.apple.com/us/app/predictwind-marine-forecasts/id477048487)** ([Web](https://www.predictwind.com/))  
基於 ECMWF / GFS 下採樣的高解析度模型 (PWE / PWG), 是多日預測最準確的.
- 1km 精度
- 多日趨勢 / window / swell
- 支援離線 GRIB

**[Windy](https://apps.apple.com/us/app/windy-com/id1161387262)** ([Web](https://www.windy.com/))  
多模型 (ECMWF / GFS / ICON) 視覺化, 用來理解風場 (flow)、地形影響、route 上的變化, 看模型分歧 (不穩定訊號), 是”模型”不是觀測.

**[Windfinder Pro](https://apps.apple.com/us/app/windfinder-pro-wind-weather/id336901296)**
- ECMWF (Superforecast) + spot-based UI
- 單點時間曲線 (何時變強 / gust)
- 適合 launch / landing / turning point 判斷

**[FishWeather](https://apps.apple.com/us/app/fishweather-marine-forecasts/id555644333)**
- 聚合 buoy / lighthouse / 私人站觀測 + 短期預測, 用來確認"現在"天氣海況.
- 即時風況 (real wind / gust / trend)
- 加拿大只有在溫哥華,維多利亞範圍才實用, 其他地區氣象站和buoy數量太少.

**[MyRadar](https://apps.apple.com/us/app/myradar-accurate-weather-radar/id322439990)**  
即時降雨 / 雷達 (storm / rain band) , 對風,海況,預測幫助有限.

### 海況 (Tide / Current)

**[DFO (Fisheries and Oceans Canada)](https://www.tides.gc.ca/en/stations)**
- 官方 tide + current tables / atlas
- 用來判斷 slack / current timing

**[OceanConnect](https://apps.apple.com/us/app/oceanconnect/id6739549480)** ([Web](https://oceanconnect.ca/))
- BC 專用視覺化 current flow + 預測 (約 40 小時)
- 顯示流向、渦流、背流 (空間理解)
- 無離線

**[AyeTides](https://apps.apple.com/ca/app/ayetides/id287316432)**  
離線潮汐表

**[Tides Near Me](https://apps.apple.com/us/app/tides-near-me/id585223877)**  
快速查看潮汐 (UI friendly)

### 天氣模型
- **ECMWF** (歐洲中期天氣預報中心)
  穩定且可靠的全球模型, 用於判斷大尺度天氣趨勢與風向基準.
    
- **GFS** (全球預報系統/美國)
  更新頻繁變動較大的全球模型, 用於觀察趨勢與不確定性.
    
- **HRDPS** (加拿大高解析模型)
  能反映 BC 沿岸與地形風場的細節.
    
- **PWE / PWG** (PredictWind 自有模型)
  以 ECMWF / GFS 為基礎再下採樣的高解析模型, 提升沿岸預測的準確度.