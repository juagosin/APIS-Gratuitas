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
- [API clara vs recurso reutilizable](#api-clara-vs-recurso-reutilizable)
- [Estructura del contenido](#estructura-del-contenido)
- [Paginas de contenido](#paginas-de-contenido)
- [Para empezar rapido](#para-empezar-rapido)
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
- Si no es una API formal, ser al menos un recurso reutilizable claro y mantenible para practicar.

Quedan fuera de este listado:

- APIs de pago sin acceso gratuito.
- APIs sin documentacion clara.
- APIs caidas o abandonadas.
- APIs cuyo uso en castellano no sea razonable.
- Recursos oficiales utiles que no funcionen realmente como API clara o mantenible para este listado.

## 🗂️ Como leer cada ficha

Cada API incluye estos campos:

- `URL`: documentacion oficial o recurso principal.
- `Tipo`: forma principal de acceso o tecnologia mas util para practicar.
- `Acceso`, `Gratis`, `Oficial` y `Estado`: se muestran de forma compacta con badges.

Debajo de cada bloque se incluye una descripcion breve de lo que ofrece la API y por que puede servir para practicar.

## 🔀 API clara vs recurso reutilizable

Este listado mezcla dos casos validos para practicar:

- `API clara`: tiene endpoints o protocolos de consulta relativamente directos, como `REST`, `SOAP`, `SPARQL`, `OAI-PMH`, `CKAN` o `OpenAPI`.
- `Recurso reutilizable`: no siempre ofrece una API formal unica, pero si acceso tecnico util y mantenible, como `Portal de datos`, `Datasets`, `Geoservicios`, `Catalogo / JSON` o casos similares.

Regla editorial simple:

- si una ficha permite consumir datos de forma directa y razonablemente estable, puede entrar
- si un portal o geovisor ofrece descargas, ficheros estructurados, geoservicios o consultas reutilizables claras, puede seguir en el listado principal aunque no sea una API REST clasica
- si solo es una landing sin acceso tecnico claro, no deberia entrar
- si hay dudas, es mejor dejarla como `Candidata` o fuera del listado principal

## 🧱 Estructura del contenido

El repositorio mantiene una portada editorial en este `README.md` y mueve el listado largo a paginas sencillas.

Motivos:

- el contenido ya ha crecido bastante
- una portada corta mejora lectura y navegacion
- varias paginas simples siguen siendo faciles de mantener
- se evita pasar demasiado pronto a una estructura compleja

## 📚 Paginas de contenido

- [España](pages/espana.md)
- [Latinoamerica](pages/latinoamerica.md)
- [Recursos abiertos reutilizables](pages/recursos-abiertos.md)

## ⚡ Para empezar rapido

Si quieres probar algo sin complicarte mucho, estas son buenas opciones de entrada:

- **datos.gob.es API**  
  Publica, oficial y sencilla para practicar catalogos, filtros y metadatos.
- **GeoRef Argentina API**  
  Publica, oficial y muy buena para busquedas geograficas, autocompletado y mapas.
- **API de datos abiertos del BOE**  
  Publica, oficial y util para practicar consultas sobre datos juridicos reales.
- **AEMET OpenData**  
  Muy buena para empezar con autenticacion simple mediante `API key` y datos meteorologicos.
- **Sismos Chile (Gael Cloud)**  
  No oficial, pero muy facil de probar y util para ejercicios rapidos con JSON.
- **Datos Abiertos MINEDUC**  
  Buena opcion si prefieres practicar limpieza, ETL y analisis con datasets educativos.

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
- Explorar vocabularios culturales y linked data con los Tesauros del Patrimonio Cultural.
- Explorar catalogos y recursos de transporte con el NAP de Transporte.
- Construir utilidades de movilidad urbana con EMT Madrid.
- Crear un comparador de gasolineras por zona y precio.
- Mostrar terremotos recientes en un mapa con datos del IGN.
- Crear un buscador geografico con GeoRef Argentina.
- Explorar series historicas de indicadores con la API de Series de Tiempo de Argentina.
- Normalizar direcciones y puntos de interes con USIG.
- Explorar datos urbanos y equipamientos con Zaragoza o Barcelona.
- Reutilizar datasets municipales amplios con Madrid, Bilbao o Donostia.
- Explorar portales institucionales amplios como Canarias, Galicia o Malaga.
- Explorar hemerotecas y patrimonio digital con la Biblioteca Virtual de Prensa Historica.
- Resolver direcciones y coordenadas con CartoCiudad.
- Descubrir capas y servicios geoespaciales con IDEE.
- Explorar indicadores de energia con eSIOS.
- Montar ejercicios de limpieza y visualizacion con datasets de Colombia.
- Practicar tablas, filtros y series temporales con INEGI y CMF.
- Consultar indicadores macroeconomicos con BCRP o BCCR.
- Practicar integracion SOAP y XML con el servicio de tipo de cambio de BANGUAT.
- Explorar catalogos nacionales adicionales de Chile, Uruguay o Republica Dominicana.
- Analizar equipamientos, festivales y patrimonio con Cultura en Datos o el SIC de Mexico.

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
