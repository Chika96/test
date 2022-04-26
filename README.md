# test
## testtest
置換には、Visual Studio EditorやXMLEDITOR.NETなどのツールをご利用ください。  
名前空間及びschemaLcationは、3D都市モデル（CityGML形式）の、`<core:CityModel>`の開始タグに記載されています。  
置換前後の3D都市モデル（CityGML形式）の例を以下に示します。太字部分が置換対象となる箇所です。  
### 置換前
<core:CityModel xmlns:uro="**`http://www.kantei.go.jp/jp/singi/tiiki/toshisaisei/itoshisaisei/iur/uro/1.4`**" xmlns:core="http://www.opengis.net/citygml/2.0"
xmlns:luse="http://www.opengis.net/citygml/landuse/2.0" xmlns:bldg="http://www.opengis.net/citygml/building/2.0"
xmlns:tran="http://www.opengis.net/citygml/transportation/2.0" xmlns:grp="http://www.opengis.net/citygml/cityobjectgroup/2.0"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:gml="http://www.opengis.net/gml" xmlns:xlink="http://www.w3.org/1999/xlink"
xsi:schemaLocation="**`http://www.kantei.go.jp/jp/singi/tiiki/toshisaisei/itoshisaisei/iur/uro/1.4
http://www.kantei.go.jp/jp/singi/tiiki/toshisaisei/itoshisaisei/iur/schemas/uro/1.4/urbanObject.xsd`** http://www.opengis.net/citygml/2.0
http://schemas.opengis.net/citygml/2.0/cityGMLBase.xsd http://www.opengis.net/citygml/landuse/2.0 http://schemas.opengis.net/citygml/landuse/2.0/landUse.xsd
http://www.opengis.net/citygml/building/2.0 http://schemas.opengis.net/citygml/building/2.0/building.xsd http://www.opengis.net/citygml/transportation/2.0
http://schemas.opengis.net/citygml/transportation/2.0/transportation.xsd http://www.opengis.net/citygml/cityobjectgroup/2.0
http://schemas.opengis.net/citygml/cityobjectgroup/2.0/cityObjectGroup.xsd http://www.opengis.net/gml http://schemas.opengis.net/gml/3.1.1/base/gml.xsd">
### 置換後
<core:CityModel xmlns:uro="**`https://www.chisou.go.jp/tiiki/toshisaisei/itoshisaisei/iur/uro/1.5`**" xmlns:core="http://www.opengis.net/citygml/2.0"
xmlns:luse="http://www.opengis.net/citygml/landuse/2.0" xmlns:bldg="http://www.opengis.net/citygml/building/2.0"
xmlns:tran="http://www.opengis.net/citygml/transportation/2.0" xmlns:grp="http://www.opengis.net/citygml/cityobjectgroup/2.0"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:gml="http://www.opengis.net/gml" xmlns:xlink="http://www.w3.org/1999/xlink"
xsi:schemaLocation="**`https://www.chisou.go.jp/tiiki/toshisaisei/itoshisaisei/iur/uro/1.5 https://www.chisou.go.jp/tiiki/toshisaisei/itoshisaisei/iur/schemas/uro/1.5/urbanObject.xsd`** http://www.opengis.net/citygml/2.0 http://schemas.opengis.net/citygml/2.0/cityGMLBase.xsd http://www.opengis.net/citygml/landuse/2.0
http://schemas.opengis.net/citygml/landuse/2.0/landUse.xsd http://www.opengis.net/citygml/building/2.0 http://schemas.opengis.net/citygml/building/2.0/building.xsd
http://www.opengis.net/citygml/transportation/2.0 http://schemas.opengis.net/citygml/transportation/2.0/transportation.xsd http://www.opengis.net/citygml/cityobjectgroup/2.0
http://schemas.opengis.net/citygml/cityobjectgroup/2.0/cityObjectGroup.xsd http://www.opengis.net/gml http://schemas.opengis.net/gml/3.1.1/base/gml.xsd">
