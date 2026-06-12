# APIs gratuitas para practicar en castellano

![Castellano](https://img.shields.io/badge/idioma-castellano-blue)
![Foco España y Latam](https://img.shields.io/badge/foco-Espa%C3%B1a%20y%20Latinoam%C3%A9rica-red)
![APIs gratuitas](https://img.shields.io/badge/APIs-gratuitas%20o%20free%20tier-green)
![Licencia CC BY 4.0](https://img.shields.io/badge/licencia-CC%20BY%204.0-lightgrey)

Recopilacion de APIs gratuitas pensadas para practicar desarrollo, con foco principal en recursos en castellano de España y Latinoamerica.

El objetivo de este repositorio es reunir APIs utiles para aprender, prototipar y construir pequenos proyectos sin tener que empezar desde cero buscando fuentes fiables.

## 📌 Resumen rapido

- Foco principal: España y Latinoamerica.
- Prioridad: APIs oficiales o claramente reutilizables.
- Acceso aceptado: publica, con registro o con `API key`.
- Estado recomendado: `Verificada` si se ha revisado bien, `Candidata` si faltan comprobaciones.

## 🧭 Navegacion rapida

- [Enfoque del proyecto](#enfoque-del-proyecto)
- [Criterios de inclusion](#criterios-de-inclusion)
- [Como leer cada ficha](#como-leer-cada-ficha)
- [Estructura del contenido](#estructura-del-contenido)
- [APIs](#apis)
- [Indice de categorias](#indice-de-categorias)
- [Primeros pasos para practicar](#primeros-pasos-para-practicar)
- [Ideas de uso para practicar](#ideas-de-uso-para-practicar)
- [Criterios de verificacion](#criterios-de-verificacion)
- [Como contribuir](#como-contribuir)

## 🎯 Enfoque del proyecto

- APIs gratuitas o con plan gratuito.
- Prioridad para APIs con documentacion en castellano.
- Se aceptan APIs con documentacion bilingue si incluyen castellano.
- Se aceptan APIs publicas, con registro o con `API key`.
- Foco principal en España y Latinoamerica.
- El foco editorial actual es el castellano.

## ✅ Criterios de inclusion

Una API deberia cumplir la mayor parte de estos puntos:

- Ser gratuita o tener un free tier util para practicar.
- Tener documentacion clara y accesible.
- Estar orientada a casos de uso reales.
- Estar activa o con senales razonables de mantenimiento.
- Indicar claramente si requiere registro o `API key`.

Quedan fuera de este listado:

- APIs de pago sin acceso gratuito.
- APIs sin documentacion clara.
- APIs caidas o abandonadas.
- APIs cuyo uso en castellano no sea razonable.
- Recursos oficiales utiles que no funcionen realmente como API clara o mantenible para este listado.

## 🗂️ Como leer cada ficha

Cada API incluye estos campos:

- `URL`: documentacion oficial o recurso principal.
- `Acceso`: publica, registro o `API key`.
- `Gratis`: acceso gratuito o free tier.
- `Oficial`: si pertenece a un organismo o servicio oficial.
- `Estado`: `Verificada` o `Candidata`.

Debajo de cada bloque se incluye una descripcion breve de lo que ofrece la API y por que puede servir para practicar.

## 🧱 Estructura del contenido

Las APIs se mantienen en un unico `README.md`.

Motivos:

- la lista es manejable
- un solo `README.md` facilita leer, buscar y contribuir
- mantener todo junto reduce complejidad innecesaria

Esta estructura puede cambiar si:

- crece mucho el numero de APIs
- aparecen muchas categorias con bastante contenido
- el `README.md` deja de ser comodo de mantener

## 📚 APIs

Listado curado de APIs y portales reutilizables para practica y aprendizaje.

## 🧩 Indice de categorias

### España

- [Gobierno y datos abiertos](#gobierno-y-datos-abiertos-espana)
- [Meteorologia](#meteorologia-espana)
- [Transporte](#transporte-espana)
- [Energia](#energia-espana)
- [Estadistica](#estadistica-espana)
- [Legal](#legal-espana)
- [Geografia](#geografia-espana)

### Latinoamerica

- [Gobierno y datos abiertos](#gobierno-y-datos-abiertos-latinoamerica)
- [Economia y finanzas](#economia-y-finanzas-latinoamerica)
- [Estadistica](#estadistica-latinoamerica)
- [Salud](#salud-latinoamerica)
- [Geografia](#geografia-latinoamerica)
- [Utilidades](#utilidades-latinoamerica)

## 🇪🇸 España

> APIs y portales oficiales de España para practica, aprendizaje y reutilizacion.

---

### 🏛️ Gobierno y datos abiertos (España)

### datos.gob.es API

- URL: `https://datos.gob.es/es/apidata`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API del catalogo de datos abiertos del portal oficial. Buena para practicar catalogos, filtros y metadatos.

### API REST Zaragoza

- URL: `https://www.zaragoza.es/sede/portal/datos-abiertos/api`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial del Ayuntamiento de Zaragoza. Permite consultar catalogo y datos en `json`, `geojson`, `xml` o `csv`, con filtros, paginacion y ejemplos. El alta es opcional.

### Open Data BCN API

- URL: `https://opendata-ajuntament.barcelona.cat/es/desenvolupadors`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial para desarrolladores del Ayuntamiento de Barcelona. Explica la API CKAN del catalogo, consultas sobre recursos CSV y limites de uso. Algunos recursos pueden requerir token.

### APIs de Open Data Euskadi

- URL: `https://opendata.euskadi.eus/apis/-/apis-open-data/`
- Acceso: Publica / Registro
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Hub oficial con APIs REST de trafico, agua, aire, directorio, subvenciones, calendario laboral y mas. Algunas, como Euskalmet, requieren registro gratuito.

### APIs del Portal de Datos Abiertos de la Junta de Andalucia

- URL: `https://www.juntadeandalucia.es/datosabiertos/portal/aplicaciones/buscador-apis`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Catalogo oficial con multiples APIs en OpenAPI 3.0.2 sobre empleo publico, inmuebles, organigrama, noticias y otros datos administrativos.

### API CKAN de Dades Obertes GVA

- URL: `https://dadesobertes.gva.es/api/3/action/package_search?rows=1`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial del catalogo de datos abiertos de la Generalitat Valenciana. Util para practicar catalogos CKAN, metadatos y descubrimiento de recursos geograficos y administrativos.

### Portal de Datos Abiertos del Ayuntamiento de Madrid

- URL: `https://datos.madrid.es/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial con catalogo amplio, `API`, `SPARQL` y multiples datasets de movilidad, medio ambiente y servicios municipales. Muy util para catalogos, filtros y reutilizacion de datos urbanos.

### Bilbao Open Data

- URL: `https://www.bilbao.eus/opendata/es/inicio`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial del Ayuntamiento de Bilbao con catalogo reutilizable y recursos en `JSON`, `CSV`, `RDF` y `RSS`. Util para practicar agenda, callejero, demografia y datos urbanos.

### Datos Abiertos de Donostia / San Sebastian

- URL: `https://www.donostia.eus/datosabiertos/catalogo`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial basado en CKAN con `API /api/3`, recursos CSV, GeoJSON y WMS. Muy util para datos urbanos, demografia, callejero y capas geograficas.

---

### 🌦️ Meteorologia (España)

### AEMET OpenData

- URL: `https://www.aemet.es/es/datos_abiertos/AEMET_OpenData`
- Acceso: API key
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API REST oficial de AEMET. Muy util para practicar peticiones autenticadas y consumo de datos meteorologicos.

---

### 🚌 Transporte (España)

### Geoportal de Gasolineras

- URL: `https://geoportalgasolineras.es/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Datos abiertos sobre estaciones de servicio y precios de carburantes. Muy util para filtros geograficos, comparadores y visualizaciones.

### NAP Transporte API

- URL: `https://nap.transportes.gob.es/api`
- Acceso: API key
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial del Punto de Acceso Nacional de transporte. Expone documentacion Swagger y permite consultar datasets, operadores, coberturas y recursos de movilidad.

### EMT Open Data / MobilityLabs Madrid

- URL: `https://datos.emtmadrid.es/`
- Acceso: Registro / API key
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial de EMT Madrid con documentacion y API REST para autobuses, bicimad, aparcamientos y datos de movilidad. Muy util para tiempo real, rutas y aplicaciones urbanas.

---

### ⚡ Energia (España)

### API eSIOS (REE)

- URL: `https://api.esios.ree.es/`
- Acceso: Registro
- Gratis: Free tier
- Oficial: Si
- Estado: Verificada

API de Red Electrica de España. Requiere token personal y ofrece indicadores del sistema electrico.

---

### 📊 Estadistica (España)

### API JSON / OpenAPI de INEbase

- URL: `https://www.ine.es/dyngs/DAB/es/index.htm?cid=1722`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

El INE ofrece API JSON y documentacion OpenAPI para consultar tablas, series, metadatos y recursos estadisticos oficiales. Muy util para analisis, filtros y visualizaciones.

### OpenAPI de Eustat

- URL: `https://es.eustat.eus/openapi/openapi.html`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Documentacion interactiva del Instituto Vasco de Estadistica. Buena para practicar consumo de OpenAPI y datos estadisticos territoriales.

---

### ⚖️ Legal (España)

### API de datos abiertos del BOE

- URL: `https://www.boe.es/datosabiertos/api/api.php`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial para legislacion consolidada, sumarios BOE/BORME y tablas auxiliares. Muy util para practicar busquedas, filtros y datos juridicos.

### API REST del BOPV

- URL: `https://opendata.euskadi.eus/api-bopv/?api=bopv`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial de Open Data Euskadi para consultar actos administrativos del Boletin Oficial del Pais Vasco. Util para ejercicios de busqueda y datos normativos regionales.

---

### 🗺️ Geografia (España)

### CartoCiudad

- URL: `https://www.cartociudad.es/web/portal/documentacion`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Servicio oficial para direcciones, geocodificacion, coordenadas y unidades administrativas. La documentacion publica incluye guias tecnicas y servicios reutilizables.

### Sede Electronica del Catastro

- URL: `https://www.sedecatastro.gob.es/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Incluye buscador y difusion de datos catastrales, cartografia y servicios web. Buena candidata para ejercicios de datos inmobiliarios y mapas.

### Geoportal IDEE

- URL: `https://www.idee.es/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Directorio y catalogos de servicios geoespaciales de España. Muy util para practicar descubrimiento de capas, mapas y metadatos.

### IGN Terremotos

- URL: `https://visualizadores.ign.es/tproximos`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

El visualizador oficial usa el recurso publico `https://www.ign.es/web/resources/sismologia/tproximos/terremotos.js`, sin autenticacion, con datos tipo GeoJSON embebido para 3, 10 y 30 dias. Muy util para mapas y eventos sismicos, aunque no es una API REST formal.

### SIGPAC

- URL: `https://sigpac.mapa.gob.es/fega/visor/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

El visor oficial expone servicios reutilizables claros: configuracion publica en `https://sigpac.mapa.gob.es/fega/visor/cfg/cfg.js`, WMTS en `https://sigpac.mapa.gob.es/sdg/wmts?service=WMTS&request=GetCapabilities` y consultas JSON en `https://sigpac.mapa.gob.es/fega/serviciosvisorsigpac/query/cod_usosigpac`.

## 🌎 Latinoamerica

> APIs y portales oficiales o claramente reutilizables de Latinoamerica para practicar con datos reales.

---

### 🏛️ Gobierno y datos abiertos (Latinoamerica)

### Datos Abiertos Colombia

- Pais/Region: Colombia
- URL: `https://www.datos.gov.co/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal de datos abiertos con acceso JSON y CSV sobre datasets publicos. Util para practicar consumo de endpoints tipo Socrata.

### Datos Abiertos Ecuador

- Pais/Region: Ecuador
- URL: `https://www.datosabiertos.gob.ec/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial en castellano con catalogo amplio y recursos reutilizables en formatos abiertos como `csv`, `ods` o `xlsx`. Util para catalogos, ETL y limpieza de datos.

### Datos Abiertos de Panama

- Pais/Region: Panama
- URL: `https://www.datosabiertos.gob.pa/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial con datos abiertos de multiples instituciones y formatos reutilizables. Bueno para practicar catalogos, filtros y procesamiento de datasets publicos.

### Datos.gov.py

- Pais/Region: Paraguay
- URL: `https://www.datos.gov.py/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Portal oficial de Paraguay con datasets por temas y guias de uso. Util para practicar descubrimiento de datos, catalogos y consumo de recursos publicos.

---

### 💰 Economia y finanzas (Latinoamerica)

### SIE API Banxico

- Pais/Region: Mexico
- URL: `https://www.banxico.org.mx/SieAPIRest/service/v1/doc/consultaDatosSerieRango`
- Acceso: API key
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API del Sistema de Informacion Economica de Banxico. Incluye tipos de cambio, tasas y series historicas.

### API CMF Bancos

- Pais/Region: Chile
- URL: `https://api.cmfchile.cl/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API de la Comision para el Mercado Financiero de Chile. Ofrece acceso a datos bancarios y reportes historicos.

### Servicio Web de Indicadores Economicos BCCR

- Pais/Region: Costa Rica
- URL: `https://www.bccr.fi.cr/indicadores-economicos/servicio-web`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Servicio oficial del Banco Central de Costa Rica para consultar indicadores economicos. Util para automatizacion de consultas y series de datos financieros.

### BCRPData API para Desarrolladores

- Pais/Region: Peru
- URL: `https://estadisticas.bcrp.gob.pe/estadisticas/series/ayuda/api`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial del Banco Central de Reserva del Peru. Permite consultar series estadisticas en `json`, `xml`, `csv` y otros formatos, con filtros por periodo e idioma.

### Servicio web Tipo de Cambio BANGUAT

- Pais/Region: Guatemala
- URL: `https://www.banguat.gob.gt/variables/ws/TipoCambio.asmx?WSDL`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Servicio oficial tipo SOAP/WSDL del Banco de Guatemala para consultar tipo de cambio del dia, rangos y monedas. Muy util para practicar XML y servicios SOAP.

---

### 📊 Estadistica (Latinoamerica)

### API de Indicadores INEGI

- Pais/Region: Mexico
- URL: `https://www.inegi.org.mx/servicios/api_indicadores.html`
- Acceso: API key
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API util para practicar consultas por indicador, area geografica y series temporales.

### API de Series de Tiempo de Argentina

- Pais/Region: Argentina
- URL: `https://datosgobar.github.io/series-tiempo-ar-api/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial para consultar indicadores publicos en `json` o `csv`, con filtros temporales, busqueda y transformaciones. Muy util para series temporales y analisis.

---

### 🩺 Salud (Latinoamerica)

### Dataset COVID-19 Colombia

- Pais/Region: Colombia
- URL: `https://www.datos.gov.co/resource/gt2j-8ykr.json?$limit=1`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Ejemplo directo de endpoint JSON en datos.gov.co. Muy util para practicar paginacion, filtros y limpieza de datos.

---

### 🗺️ Geografia (Latinoamerica)

### GeoRef Argentina API

- Pais/Region: Argentina
- URL: `https://datosgobar.github.io/georef-ar-api/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

API oficial para provincias, municipios, localidades y normalizacion geografica. Muy buena para autocompletado, filtros y mapas.

### USIG Normalizador de Direcciones

- Pais/Region: Argentina
- URL: `https://servicios.usig.buenosaires.gob.ar/normalizar/`
- Acceso: Publica
- Gratis: Si
- Oficial: Si
- Estado: Verificada

Servicio oficial del Gobierno de la Ciudad de Buenos Aires para normalizar direcciones y geocodificar resultados basicos en CABA y AMBA. Muy util para buscadores y mapas.

---

### 🧰 Utilidades (Latinoamerica)

### Sismos Chile (Gael Cloud)

- Pais/Region: Chile
- URL: `https://api.gael.cloud/general/public/sismos`
- Acceso: Publica
- Gratis: Si
- Oficial: No
- Estado: Verificada

Endpoint publico con documentacion en castellano y limite claro de uso. Util para practicar consumo de eventos sismicos recientes.

## 🚀 Primeros pasos para practicar

Una forma simple de usar este repositorio es esta:

1. Elige una API `Verificada`.
2. Revisa su documentacion y el tipo de acceso.
3. Prueba primero un endpoint publico o un ejemplo minimo.
4. Pasa despues a tu lenguaje o framework.

Ejemplo rapido con el dataset publico de Colombia:

### `curl`

```bash
curl "https://www.datos.gov.co/resource/gt2j-8ykr.json?$limit=1"
```

### JavaScript

```js
fetch("https://www.datos.gov.co/resource/gt2j-8ykr.json?$limit=1")
  .then((res) => res.json())
  .then((data) => console.log(data));
```

### Python

```python
import requests

url = "https://www.datos.gov.co/resource/gt2j-8ykr.json?$limit=1"
data = requests.get(url, timeout=10).json()
print(data)
```

## 💡 Ideas de uso para practicar

- Construir un dashboard meteorologico con AEMET.
- Montar un buscador juridico con la API del BOE.
- Graficar tipos de cambio o tasas de interes con Banxico.
- Construir visualizaciones estadisticas con INE o Eustat.
- Explorar catalogos y recursos de transporte con el NAP de Transporte.
- Construir utilidades de movilidad urbana con EMT Madrid.
- Crear un comparador de gasolineras por zona y precio.
- Mostrar terremotos recientes en un mapa con datos del IGN.
- Crear un buscador geografico con GeoRef Argentina.
- Explorar series historicas de indicadores con la API de Series de Tiempo de Argentina.
- Normalizar direcciones y puntos de interes con USIG.
- Explorar datos urbanos y equipamientos con Zaragoza o Barcelona.
- Reutilizar datasets municipales amplios con Madrid, Bilbao o Donostia.
- Resolver direcciones y coordenadas con CartoCiudad.
- Descubrir capas y servicios geoespaciales con IDEE.
- Explorar indicadores de energia con eSIOS.
- Montar ejercicios de limpieza y visualizacion con datasets de Colombia.
- Practicar tablas, filtros y series temporales con INEGI y CMF.
- Consultar indicadores macroeconomicos con BCRP o BCCR.
- Practicar integracion SOAP y XML con el servicio de tipo de cambio de BANGUAT.

## 🧪 Categorias previstas

- Gobierno y datos abiertos
- Meteorologia
- Transporte
- Economia y finanzas
- Estadistica
- Energia
- Educacion
- Cultura
- Salud
- Geografia
- Legal
- Utilidades

## 🔎 Criterios de verificacion

Antes de anadir una API o marcarla como `Verificada`, revisa:

- Si la documentacion oficial sigue activa y abre correctamente.
- Si el acceso gratuito sigue disponible o existe un free tier util.
- Si el tipo de acceso queda claro: publica, registro o `API key`.
- Si la documentacion esta en castellano o es bilingue con castellano.
- Si la API parece activa o con mantenimiento razonable.
- Si hay limites de uso importantes para quien quiera practicar.
- Si es una fuente oficial o una fuente no oficial claramente identificada.

Si alguno de estos puntos no puede confirmarse bien, es mejor dejar la API como `Candidata`.

## 🤝 Como contribuir

Si quieres proponer cambios, revisa tambien la guia de [CONTRIBUTING.md](CONTRIBUTING.md).

Se aceptan colaboraciones mediante `Pull Requests`, sobre todo para:

- proponer APIs que encajen con el foco del proyecto
- corregir enlaces o estados
- mejorar notas y descripciones
- ajustar criterios o documentacion

Si abres un `Pull Request`, intenta que sea pequeno, claro y facil de revisar.

Cada propuesta deberia incluir:

- La propuesta puede enviarse mediante `Pull Request`.
- Nombre de la API.
- Enlace oficial.
- Pais o region.
- Categoria.
- Tipo de acceso.
- Evidencia de que es gratuita o tiene free tier.
- Idioma de la documentacion.

El repositorio acepta aportaciones mediante `PRs`, manteniendo el foco en APIs utiles para practicar.

## 🎯 Objetivo del repositorio

Mantener una seleccion curada, clara y verificable de APIs utiles para practicar desarrollo en castellano, con foco principal en España y Latinoamerica.

---

## ⭐ Dale una estrella

Si te gusta este proyecto, ¡dale una estrella! ⭐ Ayuda a otros desarrolladores a encontrarlo.
