## SIMTARU
> #### Daftar Isi
> * [Arsitektur Web GIS](#arsitektur-web-gis)
> * [Fitur yang diharapkan](#fitur-yang-diharapkan)
> * [Referensi](#referensi)

### Arsitektur Web GIS
![image](http://geo.ifip.tuwien.ac.at/imak/2009/stack_workshop/doc/_images/stack.png)
![image](https://storage.googleapis.com/cdn.thenewstack.io/media/2017/09/2f021b01-boundless3.png)

### Fitur yang diharapkan
Sisi klien (peta web)
> * Mobile friendly (responsive)
> * Mengecek status kawasan oleh publik melalui:
>   * My location (lokasi saat ini berbasis GPS perangkat)
>   * Form isian titik koordinat
>   * Unggah/drag-drop data spasial vektor (titik, garis, poligon)
> * Layer dan legenda
>   * Informasi atribut layer muncul saat feature di muka peta diklik
>   * Terdapat kontrol layer sekaligus legenda
>   * Data default adalah rencana tata ruang (pola, struktur) dan basemap (Google Maps/OSM, citra satelit)
>   * Filter dan pencarian data/layer
> * Tautan ke fitur lain (form pengaduan)

Sisi klien (desktop)
> * Services (WMS / WFS), data bisa ditarik ke software desktop GIS

Sisi server atau database
> * Input data tabular/spasial untuk dapat masuk ke database/server
> * Dapat dilakukan secara remote via login, tidak harus di komputer Server
> * Data baru yang diinput dapat tampil di sisi klien (sebagai peta web/services)


### Referensi
Aplikasi infrastruktur Web GIS
> * [ArcGIS Server](https://enterprise.arcgis.com/en/server/latest/get-started/windows/what-is-arcgis-for-server-.htm)
> * [PostgreSQL/PostGIS](https://postgis.net/)
> * [Geoserver](https://https://www.osgeo.org/projects/geoserver/)
> * [Leaflet Javascript](https://leafletjs.com/)
> * [Geonode](http://geonode.org/)

Bacaan
> * [Open Source GIS Implementation](https://opengislab.com/blog/2017/3/22/open-source-gis-implementation-an-experiment)
> * [Webmapping for Dummies](https://www.xyht.com/spatial-itgis/web-mapping-for-dummies-my-personal-experience/)
> * [Leaflet Drag & Drop Github Repo](https://github.com/calvinmetcalf/leaflet.workspace)

Contoh Web GIS dan Services
> * [Leaflet Drag & Drop](https://leaflet.calvinmetcalf.com)
> * [Web GIS BPOM](https://gis.pom.go.id/)
> * [Geoserver Web GIS BPOM](http://gis.pom.go.id:8080/geoserver/web/wicket/bookmarkable/org.geoserver.web.demo.MapPreviewPage?1)
> * [ArcGIS Rest Service One Data One Map Kaltim](http://222.124.31.141:6080/arcgis/rest/services)
> * [Simpul Jaringan Infrastruktur Data Spasial Indonesia](https://github.com/ppids-ugm/simpul-jaringan-indonesia/blob/master/daftar-simpul-jaringan.md#kalimantan-timur)
> * [SPACeMAP LAPAN](http://spacemap.lapan.go.id/)
