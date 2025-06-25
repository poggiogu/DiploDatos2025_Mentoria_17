# DiploDatos2025_Mentoria_17

Diplomatura de Ciencia de Datos, Aprendizaje Automático 2025 - Mentoría 17  
Análisis y visualización de datos de inventarios forestales nacionales, cálculo de biomasa y evaluación del estado de los bosques nativos.

## Contenido

Este repositorio contiene notebooks y conjuntos de datos para el análisis y la visualización de datos forestales nacionales, con foco en Argentina.

### Notebooks principales

- `Mentoria_17_Grupo_1_TP1.ipynb`: Análisis y visualización de los conjuntos de datos principales.

## Instalación

- Clonar este repositorio:  
   ```bash
   git clone https://github.com/poggiogu/DiploDatos2025_Mentoria_17.git
   cd DiploDatos2025_Mentoria_17
   ```
## Requerimientos
Este proyecto utiliza Python 3.7+ y depende de las siguientes bibliotecas principales:
- numpy
- pandas
- matplotlib
- seaborn
- geopandas
- cartopy
- scipy

(Encontrarás la lista completa en requirements.txt)

Puedes instalar todas las bibliotecas del archivo de requisitos de una vez usando este comando en tu terminal:
   ```bash
   pip install -r requirements.txt
   ```

## Tabla de datos generales - Descripción de los datos:

**Dirección Nacional de Bosques, 2021.** Datos del Segundo Inventario Nacional de Bosques Nativos de la República Argentina. Ministerio de Ambiente y Desarrollo Sostenible de la Nación. :contentReference[oaicite:2]{index=2}

**Variables incluidas en la tabla de datos adjunta:**

| Variable               | Descripción                                                                                         |
|------------------------|-----------------------------------------------------------------------------------------------------|
| **UM_ID_UM**           | Identificador único de cada unidad de muestreo                                                      |
| **REGION_OFC**         | Región forestal                                                                                     |
| **SUBREG**             | Subregión forestal                                                                                  |
| **PROVINCIA**          | Código del Instituto Nacional de Estadísticas y Censos (INDEC)                                      |
| **MEDIA_ALTURA_UM_EST**| Valor medio de la altura de los individuos leñosos vivos en la unidad de muestreo (m)               |
| **SUMA_DAP_X_UM**      | Sumatoria del diámetro a la altura del pecho de los individuos leñosos vivos en la unidad (m)       |
| **AREA_BASAL_UM_HA**   | Área basal por hectárea de los individuos leñosos vivos (m²/ha)                                      |
| **VOL_M3_HA**          | Volumen comercial de madera por hectárea de los individuos leñosos vivos (m³/ha)                    |
| **CANTIDAD_IND_VIVOS_UM** | Número de individuos leñosos vivos en la unidad de muestreo                                      |
| **CANTIDAD_IND_VIVOS_HA** | Número estimado de individuos leñosos vivos por hectárea                                         |
| **PORCENTAJE_COB_3**   | Cobertura (%) de proyecciones aéreas de individuos arbóreos de 3 a 7 m de altura                     |
| **PORCENTAJE_COB_7**   | Cobertura (%) de proyecciones aéreas de individuos arbóreos > 7 m de altura                          |
| **PORCENTAJE_COB_TOTAL** | Cobertura total (%) (con superposición) de proyecciones aéreas de individuos arbóreos             |
| **PORCENTAJE_COB_ARBUSTIVA** | Cobertura (%) de proyecciones aéreas de individuos arbustivos                               |
| **PORCENTAJE_COB_INFERIOR**  | Cobertura (%) de proyecciones aéreas de gramíneas y herbáceas                            |
| **MEDIA_ALT_TOCONES**   | Altura media de tocones en la unidad de muestreo (cm)                                               |
| **MEDIA_DAB_TOCONES**   | Diámetro medio en la base de tocones en la unidad de muestreo (cm)                                  |
| **CANTIDAD_TOCONES_X_UM** | Número de tocones en la unidad de muestreo                                                     |
| **CANTIDAD_TOCONES_X_HA** | Número estimado de tocones por hectárea                                                          |
| **REGENERACION_UM**     | Número total de individuos de regeneración en subparcelas C de la unidad de muestreo                |
| **REGENERACION_HA**     | Número estimado de individuos de regeneración por hectárea                                         |
| **LONGITUD_GRILLA**     | Longitud de la cuadrícula para ubicación de la unidad de muestreo (°)                               |
| **LATITUD_GRILLA**      | Latitud de la cuadrícula para ubicación de la unidad de muestreo (°)                                |
| **LONGITUD_INSTALACION**| Longitud del centro de la unidad de muestreo (°)                                                    |
| **LATITUD_INSTALACION** | Latitud del centro de la unidad de muestreo (°)                                                     |
| **ALTITUD**             | Altitud media sobre el nivel del mar de la parcela (m s.n.m.)                                       |
| **PENDIENTE**           | Categoría de pendiente (sin_pendiente, suave, moderada, fuerte)                                     |
| **EXPOSICION**          | Orientación de la pendiente (N, NE, E, SE, S, SW, O, NO)                                            |
| **OTBN_CATEGORIA**      | Categoría según Ordenamiento Territorial de Bosques Nativos (I, II, III, sin_categoria)             |
| **FECHA_UM_ANIO**       | Año de colecta de datos en la unidad de muestreo                                                    |
| **FECHA_UM_MES**        | Mes de colecta de datos en la unidad de muestreo                                                    |
| **TIPO_PAISAJE**        | Tipo de paisaje predominante en la unidad de muestreo                                               |
| **SALINIDAD_PRESENCIA** | Evidencia de salinidad (TRUE/FALSE)                                                                 |
| **INCENDIOS_RASTROS**   | Rastros de incendios (TRUE/FALSE)                                                                   |
| **PASTOREO_PRESENCIA**  | Evidencia de pastoreo (TRUE/FALSE)                                                                  |
| **GANADO_BOVINO**       | Presencia de ganado bovino (TRUE/FALSE)                                                             |
| **GANADO_OVINO**        | Presencia de ganado ovino (TRUE/FALSE)                                                              |
| **GANADO_CAPRINO**      | Presencia de ganado caprino (TRUE/FALSE)                                                            |
| **GANADO_EQUINO**       | Presencia de ganado equino (TRUE/FALSE)                                                             |
| **GANADO_OTRO**         | Presencia de otro tipo de ganado (TRUE/FALSE)                                                       |
| **GANADO_OTRO_TIPO**    | Texto libre especificando otro tipo de ganado                                                       |
| **EROSION_PRESENCIA**   | Erosión presente (TRUE/FALSE)                                                                       |
| **EROSION_FISICA_PRESENCIA** | Erosión física (TRUE/FALSE)                                                                    |
| **EROSION_EOLICA_PRESENCIA** | Erosión eólica (TRUE/FALSE)                                                                   |
| **EROSION_HIDRICA_PRESENCIA** | Erosión hídrica (TRUE/FALSE)                                                                 |
| **PFNM_PRESENCIA_RESUMEN** | Resumen de especies no arbóreas de interés (texto)                                               |
| **PFNM_REGISTRO_1**     | Especie no arbórea 1 de 5 (nombre científico o “sin registro”)                                       |
| **PFNM_REGISTRO_2**     | Especie no arbórea 2 de 5 (nombre científico o “sin registro”)                                       |
| **PFNM_REGISTRO_3**     | Especie no arbórea 3 de 5 (nombre científico o “sin registro”)                                       |
| **PFNM_REGISTRO_4**     | Especie no arbórea 4 de 5 (nombre científico o “sin registro”)                                       |
| **PFNM_REGISTRO_5**     | Especie no arbórea 5 de 5 (nombre científico o “sin registro”)                                       |
| **FORMAS_HELECHOS**     | Presencia de helechos (TRUE/FALSE)                                                                  |
| **FORMAS_CACTACEAS**    | Presencia de cactáceas (TRUE/FALSE)                                                                 |
| **FORMAS_EPIFITAS**     | Presencia de epífitas (TRUE/FALSE)                                                                  |
| **FORMAS_BRIOFITAS**    | Presencia de briófitas (TRUE/FALSE)                                                                 |
| **FORMAS_LIANAS**       | Presencia de lianas (TRUE/FALSE)                                                                    |
| **FORMAS_ORQUIDEAS**    | Presencia de orquídeas (TRUE/FALSE)                                                                 |
| **FORMAS_GRAMINEAS**    | Presencia de gramíneas (TRUE/FALSE)                                                                 |
| **FORMAS_OTRAS**        | Presencia de otras formas de vida (TRUE/FALSE)                                                      |
| **Ley_N1_06**           | Leyenda Nivel 1 de Bosques Nativos (TF/OTF)                                                          |
| **Ley_N2_06**           | Leyenda Nivel 2 de Bosques Nativos (tipos forestales)                                                |
| **PRESENTA_IND_INVENTARIABLE** | Presencia (“SI”/“NO”) de individuos leñosos inventariables                                 |


**Para una descripción más detallada de los métodos y variables medidas, consultar el Manual de Campo Unificado disponible en:** 
<https://www.argentina.gob.ar/ambiente/bosques/segundo-inventario-nacional-bosques-nativos>

**Código INDEC Provincias:**  
<https://sitioanterior.indec.gob.ar/ftp/cuadros/menusuperior/clasificadores/anexo1_resol55_2019.pdf>
