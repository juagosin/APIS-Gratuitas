# APIs gratuitas para practicar en castellano

![Castellano](https://img.shields.io/badge/idioma-castellano-blue)
![Foco España y Latam](https://img.shields.io/badge/foco-Espa%C3%B1a%20y%20Latinoam%C3%A9rica-red)
![APIs gratuitas](https://img.shields.io/badge/APIs-gratuitas%20o%20free%20tier-green)
![Licencia CC BY 4.0](https://img.shields.io/badge/licencia-CC%20BY%204.0-lightgrey)

Recopilacion de APIs gratuitas pensadas para practicar desarrollo, con foco principal en recursos en castellano de Espana y Latinoamerica.

El objetivo de este repositorio es reunir APIs utiles para aprender, prototipar y construir pequenos proyectos sin tener que empezar desde cero buscando fuentes fiables.

## Resumen rapido

- Foco principal: Espana y Latinoamerica.
- Prioridad: APIs oficiales o claramente reutilizables.
- Acceso aceptado: publica, con registro o con `API key`.
- Estado recomendado: `Verificada` si se ha revisado bien, `Candidata` si faltan comprobaciones.

## Navegacion rapida

- [Enfoque del proyecto](#enfoque-del-proyecto)
- [Criterios de inclusion](#criterios-de-inclusion)
- [Como leer la tabla](#como-leer-la-tabla)
- [Estructura del contenido](#estructura-del-contenido)
- [APIs](#apis)
- [Primeros pasos para practicar](#primeros-pasos-para-practicar)
- [Ideas de uso para practicar](#ideas-de-uso-para-practicar)
- [Criterios de verificacion](#criterios-de-verificacion)
- [Como contribuir](#como-contribuir)

## Enfoque del proyecto

- APIs gratuitas o con plan gratuito.
- Prioridad para APIs con documentacion en castellano.
- Se aceptan APIs con documentacion bilingue si incluyen castellano.
- Se aceptan APIs publicas, con registro o con `API key`.
- Foco principal en Espana y Latinoamerica.
- El foco editorial actual es el castellano.

## Criterios de inclusion

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

## Como leer la tabla

- `Acceso`: indica si la API es publica, requiere registro o necesita `API key`.
- `Gratis`: indica si el acceso es totalmente gratuito o si existe free tier.
- `Oficial`: indica si la fuente pertenece a un organismo o servicio oficial.
- `Docs`: enlace a la documentacion oficial.
- `Estado`: indica si la API fue revisada recientemente o sigue pendiente de validar mejor.

Cuando una API no es oficial pero puede ser util para practicar, se marca como tal en la columna `Oficial` y normalmente queda como `Candidata` hasta revisarla mejor.

## Estructura del contenido

Las APIs se mantienen en un unico `README.md`.

Motivos:

- la lista es manejable
- un solo `README.md` facilita leer, buscar y contribuir
- mantener todo junto reduce complejidad innecesaria

Esta estructura puede cambiar si:

- crece mucho el numero de APIs
- aparecen muchas categorias con bastante contenido
- el `README.md` deja de ser comodo de mantener

## APIs

Listado curado de APIs y portales reutilizables para practica y aprendizaje.

### Espana

| Nombre | Categoria | Acceso | Gratis | Oficial | Docs | Notas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| datos.gob.es API | Gobierno y datos abiertos | Publica | Si | Si | https://datos.gob.es/es/apidata | API del catalogo de datos abiertos del portal oficial. Buena para practicar catalogos, filtros y metadatos. | Verificada |
| AEMET OpenData | Meteorologia | API key | Si | Si | https://www.aemet.es/es/datos_abiertos/AEMET_OpenData | API REST oficial de AEMET. Muy util para practicar peticiones autenticadas y consumo de datos meteorologicos. | Verificada |
| API eSIOS (REE) | Energia | Registro | Free tier | Si | https://api.esios.ree.es/ | API de Red Electrica de Espana. Requiere token personal y ofrece indicadores del sistema electrico. | Verificada |
| API de datos abiertos del BOE | Legal | Publica | Si | Si | https://www.boe.es/datosabiertos/api/api.php | API oficial para legislacion consolidada, sumarios BOE/BORME y tablas auxiliares. Muy util para practicar busquedas, filtros y datos juridicos. | Verificada |
| API JSON / OpenAPI de INEbase | Estadistica | Publica | Si | Si | https://www.ine.es/dyngs/DAB/es/index.htm?cid=1722 | El INE ofrece API JSON y documentacion OpenAPI para consultar tablas, series, metadatos y recursos estadisticos oficiales. Muy util para analisis, filtros y visualizaciones. | Verificada |
| CartoCiudad | Geografia | Publica | Si | Si | https://www.cartociudad.es/web/portal/documentacion | Servicio oficial para direcciones, geocodificacion, coordenadas y unidades administrativas. La documentacion publica incluye guias tecnicas y servicios reutilizables. | Verificada |
| Sede Electronica del Catastro | Geografia | Publica | Si | Si | https://www.sedecatastro.gob.es/ | Incluye buscador y difusion de datos catastrales, cartografia y servicios web. Buena candidata para ejercicios de datos inmobiliarios y mapas. | Verificada |
| Geoportal de Gasolineras | Transporte | Publica | Si | Si | https://geoportalgasolineras.es/ | Datos abiertos sobre estaciones de servicio y precios de carburantes. Muy util para filtros geograficos, comparadores y visualizaciones. | Verificada |
| Geoportal IDEE | Geografia | Publica | Si | Si | https://www.idee.es/ | Directorio y catalogos de servicios geoespaciales de Espana. Muy util para practicar descubrimiento de capas, mapas y metadatos. | Verificada |
| IGN Terremotos | Geografia | Publica | Si | Si | https://visualizadores.ign.es/tproximos | El visualizador oficial usa el recurso publico `https://www.ign.es/web/resources/sismologia/tproximos/terremotos.js`, sin autenticacion, con datos tipo GeoJSON embebido para 3, 10 y 30 dias. Muy util para mapas y eventos sismicos, aunque no es una API REST formal. | Verificada |
| API REST Zaragoza | Gobierno y datos abiertos | Publica | Si | Si | https://www.zaragoza.es/sede/portal/datos-abiertos/api | API oficial del Ayuntamiento de Zaragoza. Permite consultar catalogo y datos en `json`, `geojson`, `xml` o `csv`, con filtros, paginacion y ejemplos. El alta es opcional. | Verificada |
| Open Data BCN API | Gobierno y datos abiertos | Publica | Si | Si | https://opendata-ajuntament.barcelona.cat/es/desenvolupadors | Portal oficial para desarrolladores del Ayuntamiento de Barcelona. Explica la API CKAN del catalogo, consultas sobre recursos CSV y limites de uso. Algunos recursos pueden requerir token. | Verificada |
| OpenAPI de Eustat | Estadistica | Publica | Si | Si | https://es.eustat.eus/openapi/openapi.html | Documentacion interactiva del Instituto Vasco de Estadistica. Buena para practicar consumo de OpenAPI y datos estadisticos territoriales. | Verificada |
| API REST del BOPV | Legal | Publica | Si | Si | https://opendata.euskadi.eus/api-bopv/?api=bopv | API oficial de Open Data Euskadi para consultar actos administrativos del Boletin Oficial del Pais Vasco. Util para ejercicios de busqueda y datos normativos regionales. | Verificada |
| NAP Transporte API | Transporte | API key | Si | Si | https://nap.transportes.gob.es/api | API oficial del Punto de Acceso Nacional de transporte. Expone documentacion Swagger y permite consultar datasets, operadores, coberturas y recursos de movilidad. | Verificada |
| APIs de Open Data Euskadi | Gobierno y datos abiertos | Publica / Registro | Si | Si | https://opendata.euskadi.eus/apis/-/apis-open-data/ | Hub oficial con APIs REST de trafico, agua, aire, directorio, subvenciones, calendario laboral y mas. Algunas, como Euskalmet, requieren registro gratuito. | Verificada |
| APIs del Portal de Datos Abiertos de la Junta de Andalucia | Gobierno y datos abiertos | Publica | Si | Si | https://www.juntadeandalucia.es/datosabiertos/portal/aplicaciones/buscador-apis | Catalogo oficial con multiples APIs en OpenAPI 3.0.2 sobre empleo publico, inmuebles, organigrama, noticias y otros datos administrativos. | Verificada |
| API CKAN de Dades Obertes GVA | Gobierno y datos abiertos | Publica | Si | Si | https://dadesobertes.gva.es/api/3/action/package_search?rows=1 | API oficial del catalogo de datos abiertos de la Generalitat Valenciana. Util para practicar catalogos CKAN, metadatos y descubrimiento de recursos geograficos y administrativos. | Verificada |
| SIGPAC | Geografia | Publica | Si | Si | https://sigpac.mapa.gob.es/fega/visor/ | El visor oficial expone servicios reutilizables claros: configuracion publica en `https://sigpac.mapa.gob.es/fega/visor/cfg/cfg.js`, WMTS en `https://sigpac.mapa.gob.es/sdg/wmts?service=WMTS&request=GetCapabilities` y consultas JSON en `https://sigpac.mapa.gob.es/fega/serviciosvisorsigpac/query/cod_usosigpac`. | Verificada |

### Latinoamerica

| Nombre | Pais/Region | Categoria | Acceso | Gratis | Oficial | Docs | Notas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SIE API Banxico | Mexico | Economia y finanzas | API key | Si | Si | https://www.banxico.org.mx/SieAPIRest/service/v1/doc/consultaDatosSerieRango | API del Sistema de Informacion Economica de Banxico. Incluye tipos de cambio, tasas y series historicas. | Verificada |
| API de Indicadores INEGI | Mexico | Estadistica | API key | Si | Si | https://www.inegi.org.mx/servicios/api_indicadores.html | API util para practicar consultas por indicador, area geografica y series temporales. | Verificada |
| Datos Abiertos Colombia | Colombia | Gobierno y datos abiertos | Publica | Si | Si | https://www.datos.gov.co/ | Portal de datos abiertos con acceso JSON y CSV sobre datasets publicos. Util para practicar consumo de endpoints tipo Socrata. | Verificada |
| Dataset COVID-19 Colombia | Colombia | Salud | Publica | Si | Si | https://www.datos.gov.co/resource/gt2j-8ykr.json?$limit=1 | Ejemplo directo de endpoint JSON en datos.gov.co. Muy util para practicar paginacion, filtros y limpieza de datos. | Verificada |
| GeoRef Argentina API | Argentina | Geografia | Publica | Si | Si | https://datosgobar.github.io/georef-ar-api/ | API oficial para provincias, municipios, localidades y normalizacion geografica. Muy buena para autocompletado, filtros y mapas. | Verificada |
| API de Series de Tiempo de Argentina | Argentina | Estadistica | Publica | Si | Si | https://datosgobar.github.io/series-tiempo-ar-api/ | API oficial para consultar indicadores publicos en `json` o `csv`, con filtros temporales, busqueda y transformaciones. Muy util para series temporales y analisis. | Verificada |
| USIG Normalizador de Direcciones | Argentina | Geografia | Publica | Si | Si | https://servicios.usig.buenosaires.gob.ar/normalizar/ | Servicio oficial del Gobierno de la Ciudad de Buenos Aires para normalizar direcciones y geocodificar resultados basicos en CABA y AMBA. Muy util para buscadores y mapas. | Verificada |
| API CMF Bancos | Chile | Finanzas | Publica | Si | Si | https://api.cmfchile.cl/ | API de la Comision para el Mercado Financiero de Chile. Ofrece acceso a datos bancarios y reportes historicos. | Verificada |
| Sismos Chile (Gael Cloud) | Chile | Utilidades | Publica | Si | No | https://api.gael.cloud/general/public/sismos | Endpoint publico con documentacion en castellano y limite claro de uso. Util para practicar consumo de eventos sismicos recientes. | Verificada |
| Servicio Web de Indicadores Economicos BCCR | Costa Rica | Economia y finanzas | Publica | Si | Si | https://www.bccr.fi.cr/indicadores-economicos/servicio-web | Servicio oficial del Banco Central de Costa Rica para consultar indicadores economicos. Util para automatizacion de consultas y series de datos financieros. | Verificada |
| Datos Abiertos Ecuador | Ecuador | Gobierno y datos abiertos | Publica | Si | Si | https://www.datosabiertos.gob.ec/ | Portal oficial en castellano con catalogo amplio y recursos reutilizables en formatos abiertos como `csv`, `ods` o `xlsx`. Util para catalogos, ETL y limpieza de datos. | Verificada |
| BCRPData API para Desarrolladores | Peru | Economia y finanzas | Publica | Si | Si | https://estadisticas.bcrp.gob.pe/estadisticas/series/ayuda/api | API oficial del Banco Central de Reserva del Peru. Permite consultar series estadisticas en `json`, `xml`, `csv` y otros formatos, con filtros por periodo e idioma. | Verificada |
| Servicio web Tipo de Cambio BANGUAT | Guatemala | Economia y finanzas | Publica | Si | Si | https://www.banguat.gob.gt/variables/ws/TipoCambio.asmx?WSDL | Servicio oficial tipo SOAP/WSDL del Banco de Guatemala para consultar tipo de cambio del dia, rangos y monedas. Muy util para practicar XML y servicios SOAP. | Verificada |
| Datos Abiertos de Panama | Panama | Gobierno y datos abiertos | Publica | Si | Si | https://www.datosabiertos.gob.pa/ | Portal oficial con datos abiertos de multiples instituciones y formatos reutilizables. Bueno para practicar catalogos, filtros y procesamiento de datasets publicos. | Verificada |
| Datos.gov.py | Paraguay | Gobierno y datos abiertos | Publica | Si | Si | https://www.datos.gov.py/ | Portal oficial de Paraguay con datasets por temas y guias de uso. Util para practicar descubrimiento de datos, catalogos y consumo de recursos publicos. | Verificada |

## Primeros pasos para practicar

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

## Ideas de uso para practicar

- Construir un dashboard meteorologico con AEMET.
- Montar un buscador juridico con la API del BOE.
- Graficar tipos de cambio o tasas de interes con Banxico.
- Construir visualizaciones estadisticas con INE o Eustat.
- Explorar catalogos y recursos de transporte con el NAP de Transporte.
- Crear un comparador de gasolineras por zona y precio.
- Mostrar terremotos recientes en un mapa con datos del IGN.
- Crear un buscador geografico con GeoRef Argentina.
- Explorar series historicas de indicadores con la API de Series de Tiempo de Argentina.
- Normalizar direcciones y puntos de interes con USIG.
- Explorar datos urbanos y equipamientos con Zaragoza o Barcelona.
- Resolver direcciones y coordenadas con CartoCiudad.
- Descubrir capas y servicios geoespaciales con IDEE.
- Explorar indicadores de energia con eSIOS.
- Montar ejercicios de limpieza y visualizacion con datasets de Colombia.
- Practicar tablas, filtros y series temporales con INEGI y CMF.
- Consultar indicadores macroeconomicos con BCRP o BCCR.
- Practicar integracion SOAP y XML con el servicio de tipo de cambio de BANGUAT.

## Categorias previstas

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

## Criterios de verificacion

Antes de anadir una API o marcarla como `Verificada`, revisa:

- Si la documentacion oficial sigue activa y abre correctamente.
- Si el acceso gratuito sigue disponible o existe un free tier util.
- Si el tipo de acceso queda claro: publica, registro o `API key`.
- Si la documentacion esta en castellano o es bilingue con castellano.
- Si la API parece activa o con mantenimiento razonable.
- Si hay limites de uso importantes para quien quiera practicar.
- Si es una fuente oficial o una fuente no oficial claramente identificada.

Si alguno de estos puntos no puede confirmarse bien, es mejor dejar la API como `Candidata`.

## Como contribuir

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

## Objetivo del repositorio

Mantener una seleccion curada, clara y verificable de APIs utiles para practicar desarrollo en castellano, con foco principal en Espana y Latinoamerica.
