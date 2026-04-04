test if webpage only can get data from other website and process and display in real time.


2026-04-04 update:

not ok due to no CORS:
https://www.1823.gov.hk/common/ical/tc.json

ok:
https://www.hko.gov.hk/en/weatherAPI/doc/files/HKO_Open_Data_API_Documentation.pdf
CORS: 
access-control-allow-headers
	Origin, Content-Type, X-Auth-Token
access-control-allow-methods
	GET
access-control-allow-origin
	*
