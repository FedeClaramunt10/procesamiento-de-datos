# Procesamiento de Datos

Trabajos de la materia Procesamiento de Datos (2° cuatrimestre) de la Tecnicatura en Análisis de Datos e Inteligencia Artificial: limpieza, transformación y tratamiento de datasets reales.

## Notebooks

| Notebook | Contenido |
|----------|-----------|
| `notebooks/Limpieza_de_dataset_LEGOs.ipynb` | Limpieza y preparación del dataset público LEGO Sets: normalización, tipos y valores faltantes. |
| `notebooks/Tratamiento_de_valores_nulos.ipynb` | Técnicas de detección y tratamiento de valores nulos. |
| `notebooks/actividad_clase_spotify.ipynb` | Actividad de clase: análisis y transformación de datos de Spotify. |
| `notebooks/limpieza_de_dataset_legos.py` | Versión en script del pipeline de limpieza de LEGO. |

## Datos

- `data/lego_sets.csv` — dataset LEGO Sets (~3.800 registros).
- `data/lego_sets_data_dictionary.csv` — diccionario de datos del dataset.

## Cómo ejecutarlos

```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook notebooks/Limpieza_de_dataset_LEGOs.ipynb
```

Las rutas dentro de los notebooks son relativas a `data/`.

## Temas cubiertos

- Exploración inicial de datos
- Detección y tratamiento de valores nulos
- Normalización y cambio de tipos
- Filtrado, agregación y derivación de columnas
- Exportación de datos limpios

## Licencia

MIT
