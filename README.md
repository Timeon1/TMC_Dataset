# TMC_Dataset
TMC(Travel Management Companies)，资料集，中国国内机场城市列表（城市三字码、机场三字码）

## 数据列表

| 文件列表                     | JSON | 
|:--------------------------------|:-----|
| 中国城市三字码(按首字母拼音分组) | [citys-cn-code.json](https://github.com/Timeon1/TMC_Dataset/blob/master/citys-cn-code.json) |
| 航司二字码(全球 共计934条) | [airline.json](https://github.com/Timeon1/TMC_Dataset/blob/master/airline.json) |
| 航司二字码(中国 共计43条) | [airline-cn.json](https://github.com/Timeon1/TMC_Dataset/blob/master/airline-cn.json) |
| 航司Logo图片(中国 共计40张) | [asserts/airlineCnImg](https://github.com/Timeon1/TMC_Dataset/tree/master/asserts/airlineCnImg) |
| 机型三字码 | [planeThreeCode.json](https://github.com/Timeon1/TMC_Dataset/blob/master/planeThreeCode.json) |
| 机场接机点(国内) | [airport-terminal-cn.json](https://github.com/Timeon1/TMC_Dataset/blob/master/airport-terminal-cn.json) |


***中国城市三字码预览***
```json
{
    "cityId": "321",
    "cityCode": "SHA",
    "cityFullName": "上海",
    "cityShortName": "上海",
    "cityFullPinyin": "Shanghai",
    "cityShortPinyin": "SH",
    "airportCode": "SHA;PVG",
    "airportName": "上海虹桥国际机场;上海浦东国际机场",
    "airportShortName": "虹桥机场;浦东机场",
    "isHaveAirport": 2,
    "mainAirportCode": "SHA",
    "provinceId": "25",
    "provinceFullName": "上海直辖市",
    "provinceShortName": "上海",
    "provinceFullPinyin": "Shanghai",
    "provinceShortPinyin": "SH",
    "countryId": "1",
    "countryCNName": "中国",
    "cityWeight": 9995,
    "groupKey": "S"
}
```
***航司二字码预览***
```json
{"value":"A1","text":"APG航空"},{"value":"A2","text":"阿斯特拉航空"},{"value":"A3","text":"爱琴海航空"}
```
***航司二字码(国内)预览***
```json
{
    "value": "MU",
    "text": "东方航空(MU)",
    "filterText": "MU,东方航空,东方航空,China Eastern Airlines"
},
{
    "value": "CZ",
    "text": "南方航空(CZ)",
    "filterText": "CZ,南方航空,南方航空,China Southern Airlines"
},
```
***航司LOGO预览***

![image](https://github.com/Timeon1/TMC_Dataset/blob/master/asserts/airlineCnImg/MU.svg)

***机型三字码预览***
```json
"743":{
    "ID":1118,
    "ThreeCode":"743",
    "FourCode":"B743",
    "Longname":"B747-300",
    "Aclevel":"FCYK",
    "Seats":"295",
    "Speed":"8",
    "Actype":"C1",
    "Aptime":"65",
    "citypairactype":"机型8",
    "PickOutTime":"75",
    "OtherTime":"65",
    "UpdateName":null,
    "UpdateType":null,
    "pd":"P"
}
```

***机场接机点(国内)预览***
```json
[
  {
    "AirportName": "浦东国际机场",
    "AirportCode": "PVG",
    "CityName": "上海",
    "CityCode": "310000",
    "Terminal": "T2 (国内到达)",
    "Longitude": 121.808118,
    "Latitude": 31.151526
  },
  {
    "AirportName": "浦东国际机场",
    "AirportCode": "PVG",
    "CityName": "上海",
    "CityCode": "310000",
    "Terminal": "T2 (国际港澳台到达)",
    "Longitude": 121.808905,
    "Latitude": 31.149461
  },
  {
    "AirportName": "虹桥国际机场",
    "AirportCode": "SHA",
    "CityName": "上海",
    "CityCode": "310000",
    "Terminal": "T2 (出发南)",
    "Longitude": 121.327843,
    "Latitude": 31.192462
  },
  {
    "AirportName": "虹桥国际机场",
    "AirportCode": "SHA",
    "CityName": "上海",
    "CityCode": "310000",
    "Terminal": "T1",
    "Longitude": 121.34726,
    "Latitude": 31.195412
  },
  {
    "AirportName": "虹桥国际机场",
    "AirportCode": "SHA",
    "CityName": "上海",
    "CityCode": "310000",
    "Terminal": "T2 (出发北)",
    "Longitude": 121.325606,
    "Latitude": 31.195008
  }
]
```