# Covid-19: información multilingüe en el Perú

"Los pueblos indígenas se encuentran entre las poblaciones más vulnerables a la diseminación del COVID-19 en el país. Nuestro país se encuentra hoy ante un grave peligro de etnocidio por la demora de una atención temprana y pertinente a los pueblos indígenas" ([Roberto Zariquiey, Nota en El Comercio](https://elcomercio.pe/eldominical/entrevista/roberto-zariquiey-el-mapa-de-la-covid-19-es-el-mapa-de-la-exclusion-y-la-pobreza-comunidades-amazonicas-pandemia-noticia/?ref=ecr))

El Ministerio de Salud (MINSA) del Perú, ha publicado [material de coronavirus en lenguas originarias](https://www.gob.pe/institucion/minsa/colecciones/748-material-de-coronavirus-en-lenguas-originarias); sin embargo, sólo contiene afiches básicos hasta el momento. Para apoyar en la democratización de la información, ponemos a disposición este repositorio para publicar información más detallada sobre coronavirus en las lenguas originarias del Perú. 

Esta iniciativa se basa en muchas otras a nivel mundial. Por ejemplo:
- [covid19-datashare](https://github.com/neulab/covid19-datashare)
- [TranslateForSG](https://translatefor.sg/)
- [Translations for Africa (Univ. of Cambridge](https://www.cam.ac.uk/stories/Translations-for-Africa)

# Roadmap
Todas las sesiones serán abiertas, para que todos los interesados puedan participar

## Planeamiento (y Marketing)
- Determinar plan de difusión del bot
- Administrar página asociada al bot
- Administrar lista de contactos y comunidades (y potenciales sinergias)
  - Howl: MinCul
  - Yudith: Quechua para todos
  - Arturo: Traductores (shipibo-konibo)
  - Joe: Traducciones (lenguas de la selva)
- Team: Arturo (contactar a MinCul o hablantes de comunidades nativas). Todos → compartirlo

## Product
- Definir funcionalidades y alcances
- Definir versiones para cada iteración
- Llevar la visión de producto
- Cada semana discutir propuestas con el resto del equipo 
- Team: Arturo, Robert

## Project Management
- Ciclos de 2 semanas

## UX 
- Mantener comunicación constante con usuarios finales para validar las interfaces
- Investigar referencias de otros bots/websites de traducción
- Diseñar mockups del flujo de interacción
- Cada semana* discutir propuestas con el resto del equipo 

#### Chatbot
- Mockup en botsociety.io
- Team: Arturo, Juanjo, 

#### Website
- Mockup
- Team: Sonia, Camila, Arturo, Joe

## FrontEnd 
- Implementar interfaces
- Consumir servicios del backend

#### Chatbot
- Team: Juanjo, Daniel^2, Robert, Patrick, Rodrigo

#### Website * 2 (para traductores (generación) y para la gente (consumo))
- Team: Fabricio, Yudith, Patrick, Robert, Joe

## BackEnd 
- Definir lógica para determinar ejemplos a traducir
- Arquitectura serverless (AWS Lambda)
- Base de datos (AWS RDS o DynamoDB)
- Team: Howl, Robert, Rodrigo, Patrick

## Data
- Recolección de data (Web Scraping)
- Almacenamiento de archivos csv, txt (GitHub, AWS S3)
- Definir lineamientos para la calidad de data
- Definir criterios para seleccionar los datos para traducir
- Team: Marco, Fabricio 
