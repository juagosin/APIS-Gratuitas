# Contribuir

Gracias por querer mejorar este repositorio.

La idea del proyecto es mantener una seleccion util, clara y manejable de APIs gratuitas para practicar desarrollo, con foco principal en recursos en castellano de Espana y Latinoamerica.

## Que tipo de aportaciones se aceptan

Se aceptan especialmente:

- Nuevas APIs gratuitas o con free tier util para practicar.
- Correcciones de enlaces, estado o notas de APIs ya listadas.
- Mejora de descripciones para que sean mas claras.
- Ajustes en criterios, estructura o documentacion del proyecto.

## Antes de proponer una API

Por favor, revisa estos puntos:

- La API sigue activa.
- El acceso gratuito es real y util para practicar.
- La documentacion es clara.
- La documentacion esta en castellano, o es bilingue e incluye castellano.
- Queda claro si el acceso es publico, con registro o con `API key`.
- Queda claro si la API es oficial o no.

No anadas como verificada una API dudosa o que no hayas podido revisar bien.

## Prioridades del proyecto

Ahora mismo priorizamos:

1. APIs de Espana y Latinoamerica.
2. Fuentes oficiales.
3. Recursos utiles para aprendizaje y practica real.
4. Cambios pequenos, claros y faciles de mantener.

## Como proponer cambios

La forma recomendada es mediante un `Pull Request`.

Si el repositorio usa plantillas de GitHub, puedes apoyarte en ellas para abrir propuestas o revisiones de forma mas consistente.

Si propones una nueva API, intenta incluir esta informacion:

- Nombre de la API.
- Enlace oficial o fuente principal.
- Pais o region.
- Categoria.
- Tipo de acceso: publica, registro o `API key`.
- Si es gratis o tiene free tier.
- Idioma de la documentacion.
- Si es oficial o no.
- Nota breve sobre por que es util para practicar.
- Estado propuesto: `Verificada` o `Candidata`.

## Cuando usar `Verificada` y cuando `Candidata`

Usa `Verificada` solo si has comprobado al menos lo siguiente:

- La documentacion abre correctamente.
- El acceso gratuito sigue disponible.
- El tipo de autenticacion esta claro.
- La API parece activa o mantenida.

Usa `Candidata` si:

- La API parece util, pero falta revisar algo.
- La documentacion no es suficientemente clara.
- No pudiste confirmar algun detalle importante.
- No es oficial pero puede servir para practicar.

## Recomendaciones para editar el README

- Escribe en castellano.
- Usa texto corto, claro y util.
- Indica siempre autenticacion, gratuidad, oficialidad y notas importantes.
- Evita duplicados.
- No compliques la estructura sin una razon clara.

Por ahora el proyecto mantiene las APIs en el `README.md` principal. No hace falta proponer separar categorias en archivos distintos salvo que el volumen crezca de verdad.

## Formato recomendado para nuevas filas

### APIs de Espana

```md
| Nombre | Categoria | Acceso | Gratis | Oficial | Docs | Notas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Nombre API | Categoria | Publica / Registro / API key | Si / Free tier | Si / No | https://... | Nota breve y util. | Verificada / Candidata |
```

### APIs de Latinoamerica

```md
| Nombre | Pais/Region | Categoria | Acceso | Gratis | Oficial | Docs | Notas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Nombre API | Pais | Categoria | Publica / Registro / API key | Si / Free tier | Si / No | https://... | Nota breve y util. | Verificada / Candidata |
```

## Sugerencia para la descripcion del PR

Puedes usar algo tan simple como esto:

```md
## Resumen
- Añado/actualizo ...

## Verificacion
- Revise la documentacion
- Confirme acceso gratuito o free tier
- Revise idioma de la documentacion
- Marque la API como Verificada o Candidata segun corresponda
```

## Cambios que es mejor evitar

Por ahora, intenta evitar:

- Meter muchas APIs de golpe sin revisar.
- Anadir APIs solo porque son populares.
- Incluir APIs solo en ingles si no encajan con el foco actual.
- Dar por verificado algo que no lo esta.

## Dudas o propuestas

Si no tienes claro si una API encaja, es mejor abrir una propuesta conservadora o dejarla como `Candidata` con una nota breve explicando que falta revisar.
