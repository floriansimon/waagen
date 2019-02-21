# waagen
GeoJSON of public* scales in Vienna or elsewhere in Austria.  
https://symptomatis.ch/mikro/waagen/  

*mainly public. otherwise specified
## properties of GeoJSON
```
"properties": {
  "detail": "",
  "osmid": ,
  "public": ,
  "missing": ,
  "color": 
}
```
<dl>
  <dt>detail</dt>
  <dd>name of closest landmark</dd>
  <dt>osmid</dt>
  <dd>ID of corresponding openstreetmap node<br><em>null</em> if not provided</dd>
  <dt>public</dt>
  <dd>1 if publically available, else 0<br><em>null</em> if currently unknown</dd>
</dl>

### example
```
"properties": {
  "detail": "Haltestelle Dr.-Karl-Renner-Ring (D, 1, 2, 71, N25, N38, N60, N66)",
  "osmid": 4314602412,
  "public": 1,
  "missing": 0,
  "color": "grün"
}
```
