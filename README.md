# waagen
GeoJSON of public* scales in Vienna or elsewhere in Austria.  
https://symptomatis.ch/mikro/waagen/  

*mainly public. otherwise specified
## properties of GeoJSON
```
"properties": {
  "detail": "",
  "comment": "",
  "color": "",
  "status": "",
  "osmid": 
},
"geometry": {
  "type": "Point",
  "coordinates": [
    Longitude,
    Latitude
  ]
}
```

<dl>
  <dt>detail</dt>
  <dd>name of closest landmark</dd>
  <dt>comment</dt>
  <dd>additional information not suitable for detail field<br><em>null</em> if not provided</dd>
  <dt>osmid</dt>
  <dd>ID of corresponding openstreetmap node<br><em>null</em> if not provided</dd>
  <dt>status</dt>
  <dl>
    <dt>public</dt>
    <dd>scale publically available</dd>
    <dt>private</dt>
    <dd>scale on private property (museum etc.)</dd>
    <dt>missing</dt>
    <dd>scale no longer available</dd>
    <dt>null</dt>
    <dd>null if unknown</dd>
  </dl>
  <dt>color</dt>
  <dd>available colors: <strong>silver</strong>, <strong>gold</strong>, <strong>bronze</strong>, <strong>red</strong>, <strong>green</strong> and <strong>blue</strong>.<br><em>null</em> if unknown</dd>
</dl>

### example
```
"properties": {
  "detail": "Haltestelle Dr.-Karl-Renner-Ring (D, 1, 2, 71, N25, N38, N60, N66)",
  "comment": ,
  "color": "green",
  "status": "public",
  "osmid": 4314602412
},
"geometry": {
  "type": "Point",
  "coordinates": [
    16.360078,
    48.206868
  ]
}
```
