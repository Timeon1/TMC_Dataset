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