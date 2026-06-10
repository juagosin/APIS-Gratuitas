# APIs gratuitas para practicar en castellano

Recopilacion de APIs gratuitas pensadas para practicar desarrollo, con foco principal en recursos en castellano de Espana y Latinoamerica.

El objetivo de este repositorio es reunir APIs utiles para aprender, prototipar y construir pequenos proyectos sin tener que empezar desde cero buscando fuentes fiables.

## Enfoque del proyecto

- APIs gratuitas o con plan gratuito.
- Prioridad para APIs con documentacion en castellano.
- Se aceptan APIs con documentacion bilingue si incluyen castellano.
- Se aceptan APIs publicas, con registro o con `API key`.
- Foco principal en Espana y Latinoamerica.
- En el futuro podrian incluirse APIs en ingles, pero no es el objetivo principal ahora.

## Criterios de inclusion

Una API deberia cumplir la mayor parte de estos puntos:

- Ser gratuita o tener un free tier util para practicar.
- Tener documentacion clara y accesible.
- Estar orientada a casos de uso reales.
- Estar activa o con senales razonables de mantenimiento.
- Indicar claramente si requiere registro o `API key`.

Quedan fuera por ahora:

- APIs de pago sin acceso gratuito.
- APIs sin documentacion clara.
- APIs caidas o abandonadas.
- APIs cuyo uso en castellano no sea razonable.

## Como leer la tabla

- `Acceso`: indica si la API es publica, requiere registro o necesita `API key`.
- `Gratis`: indica si el acceso es totalmente gratuito o si existe free tier.
- `Oficial`: indica si la fuente pertenece a un organismo o servicio oficial.
- `Docs`: enlace a la documentacion oficial.
- `Estado`: indica si la API fue revisada recientemente o sigue pendiente de validar mejor.

Cuando una API no es oficial pero puede ser util para practicar, se marca como tal en la columna `Oficial` y normalmente queda como `Candidata` hasta revisarla mejor.

## APIs

Primera seleccion de APIs candidatas para arrancar el proyecto. La idea es ir ampliando y revisando esta tabla de forma iterativa.

### Espana

| Nombre | Categoria | Acceso | Gratis | Oficial | Docs | Notas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| datos.gob.es API | Gobierno y datos abiertos | Publica | Si | Si | https://datos.gob.es/es/apidata | API del catalogo de datos abiertos del portal oficial. Buena para practicar catalogos, filtros y metadatos. | Verificada |
| AEMET OpenData | Meteorologia | API key | Si | Si | https://www.aemet.es/es/datos_abiertos/AEMET_OpenData | API REST oficial de AEMET. Muy util para practicar peticiones autenticadas y consumo de datos meteorologicos. | Verificada |
| API eSIOS (REE) | Energia | Registro | Free tier | Si | https://api.esios.ree.es/ | API de Red Electrica de Espana. Requiere token personal y ofrece indicadores del sistema electrico. | Verificada |
| API de datos abiertos del BOE | Legal | Publica | Si | Si | https://www.boe.es/datosabiertos/api/api.php | API oficial para legislacion consolidada, sumarios BOE/BORME y tablas auxiliares. Muy util para practicar busquedas, filtros y datos juridicos. | Verificada |
| CartoCiudad | Geografia | Publica | Si | Si | https://www.cartociudad.es/ | Servicio oficial para direcciones, geocodificacion, coordenadas y unidades administrativas. Muy buena para buscadores y utilidades de mapas. | Verificada |
| Sede Electronica del Catastro | Geografia | Publica | Si | Si | https://www.sedecatastro.gob.es/ | Incluye buscador y difusion de datos catastrales, cartografia y servicios web. Buena candidata para ejercicios de datos inmobiliarios y mapas. | Verificada |
| Geoportal de Gasolineras | Transporte | Publica | Si | Si | https://www.geoportalgasolineras.es/ | Datos abiertos sobre estaciones de servicio y precios de carburantes. Muy util para filtros geograficos, comparadores y visualizaciones. | Verificada |
| Geoportal IDEE | Geografia | Publica | Si | Si | https://www.idee.es/ | Directorio y catalogos de servicios geoespaciales de Espana. Muy util para practicar descubrimiento de capas, mapas y metadatos. | Verificada |
| IGN Terremotos | Geografia | Publica | Si | Si | https://www.ign.es/web/ign/portal/terremotos-proximos-viewer | Servicio publico del IGN para consultar terremotos recientes y sismicidad. Util para mapas, series temporales y alertas. | Candidata |
| SIGPAC | Geografia | Publica | Si | Si | https://sigpac.mapama.gob.es/fega/visor/ | Sistema oficial de informacion geografica de parcelas agricolas. Muy interesante para practicar consultas espaciales y cartografia. | Candidata |

### Latinoamerica

| Nombre | Pais/Region | Categoria | Acceso | Gratis | Oficial | Docs | Notas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SIE API Banxico | Mexico | Economia y finanzas | API key | Si | Si | https://www.banxico.org.mx/SieAPIRest/service/v1/doc/consultaDatosSerieRango | API del Sistema de Informacion Economica de Banxico. Incluye tipos de cambio, tasas y series historicas. | Verificada |
| API de Indicadores INEGI | Mexico | Estadistica | API key | Si | Si | https://www.inegi.org.mx/servicios/api_indicadores.html | API util para practicar consultas por indicador, area geografica y series temporales. | Verificada |
| Datos Abiertos Colombia | Colombia | Gobierno y datos abiertos | Publica | Si | Si | https://www.datos.gov.co/ | Portal de datos abiertos con acceso JSON y CSV sobre datasets publicos. Util para practicar consumo de endpoints tipo Socrata. | Verificada |
| Dataset COVID-19 Colombia | Colombia | Salud | Publica | Si | Si | https://www.datos.gov.co/resource/gt2j-8ykr.json?$limit=1 | Ejemplo directo de endpoint JSON en datos.gov.co. Muy util para practicar paginacion, filtros y limpieza de datos. | Verificada |
| GeoRef Argentina API | Argentina | Geografia | Publica | Si | Si | https://datosgobar.github.io/georef-ar-api/ | API oficial para provincias, municipios, localidades y normalizacion geografica. Muy buena para autocompletado, filtros y mapas. | Verificada |
| API CMF Bancos | Chile | Finanzas | Publica | Si | Si | https://api.cmfchile.cl/ | API de la Comision para el Mercado Financiero de Chile. Ofrece acceso a datos bancarios y reportes historicos. | Verificada |
| Sismos Chile (Gael Cloud) | Chile | Utilidades | Publica | Si | No | https://api.gael.cloud/general/public/sismos | Endpoint publico sencillo para practicar consumo de eventos sismicos recientes. Pendiente revisar documentacion mas completa. | Candidata |

## Ideas de uso para practicar

- Construir un dashboard meteorologico con AEMET.
- Montar un buscador juridico con la API del BOE.
- Graficar tipos de cambio o tasas de interes con Banxico.
- Crear un comparador de gasolineras por zona y precio.
- Mostrar terremotos recientes en un mapa con datos del IGN.
- Crear un buscador geografico con GeoRef Argentina.
- Resolver direcciones y coordenadas con CartoCiudad.
- Descubrir capas y servicios geoespaciales con IDEE.
- Explorar indicadores de energia con eSIOS.
- Montar ejercicios de limpieza y visualizacion con datasets de Colombia.
- Practicar tablas, filtros y series temporales con INEGI y CMF.

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

## Propuesta de campos a revisar por API

Antes de anadir una API, conviene validar:

- Si la documentacion sigue activa.
- Si el acceso gratuito sigue disponible.
- Si requiere registro o `API key`.
- Si la documentacion esta en castellano o bilingue con castellano.
- Si hay limites de uso relevantes para quien quiera practicar.

## Como contribuir

De momento el repositorio esta en fase inicial. Cuando se abra a colaboraciones, idealmente cada propuesta deberia incluir:

- La propuesta puede enviarse mediante `Pull Request`.
- Nombre de la API.
- Enlace oficial.
- Pais o region.
- Categoria.
- Tipo de acceso.
- Evidencia de que es gratuita o tiene free tier.
- Idioma de la documentacion.

La idea es que el repositorio pueda crecer tambien con aportaciones de otras personas mediante `PRs`, siempre manteniendo el foco en APIs utiles para practicar.

## Objetivo a corto plazo

Construir una primera seleccion curada de APIs utiles para practicar, priorizando calidad y claridad antes que cantidad.
