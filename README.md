# wienerwaagen.at
GeoJSON of public* scales in Vienna or elsewhere in Austria.  
https://symptomatis.ch/mikro/waagen/  

*mainly public. otherwise specified
## properties of GeoJSON
```
"properties": {
  "detail": "",
  "osmid": ,
  "public": 
}
```
<dl>
  <dt>detail</dt>
  <dd>name of closest landmark</dd>
  <dt>osmid</dt>
  <dd>ID of corresponding openstreetmap node</dd>
  <dt>public</dt>
  <dd>1 if publically available, else 0</dd>
</dl>

### example
```
"properties": {
  "detail": "Haltestelle Dr.-Karl-Renner-Ring (D, 1, 2, 71, N25, N38, N60, N66)",
  "osmid": 4314602412,
  "public": 1
}
```
