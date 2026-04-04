test if webpage only can get data from other website and process and display in real time.


2026-04-04 update:

not ok due to no CORS:
https://www.1823.gov.hk/common/ical/tc.json

ok:
https://data.weather.gov.hk/weatherAPI/opendata/lunardate.php?date=2023
CORS: 
access-control-allow-headers
	Origin, Content-Type, X-Auth-Token
access-control-allow-methods
	GET
access-control-allow-origin
	*

API reference doc:
https://www.hko.gov.hk/en/weatherAPI/doc/files/HKO_Open_Data_API_Documentation.pdf

OK: 學校位置地理參考數據及其他相關資料
https://www.edb.gov.hk/attachment/en/student-parents/sch-info/sch-search/sch-location-info/SCH_LOC_EDB.json
