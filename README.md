# WeatherAPI

Pruebas de API para la materia de Control de Calidad de Software.

## Estructura del Proyecto

```text
WeatherAPI/
├── src/
│   └── (Código fuente del proyecto / scripts de automatización)
├── testing/
│   ├── casos-de-prueba.xlsx
│   ├── hoppscotch/
│   │   └── weather-api-collection.json
│   └── evidencias/
│       ├── Evidencia_Hoppscotch_2026-11-07.json
│       ├── Evidencia_Weather_API_repruebas_2026-11-07.json
│       ├── TC-AL-01/ ... TC-AL-06/
│       ├── TC-FC-01/ ... TC-FC-08/
│       ├── TC-HS-01/ ... TC-HS-07/
│       └── TC-RT-01/ ... TC-RT-07/
└── README.md
```

## Contenido

- **`src/`**: Carpeta reservada para el código fuente o scripts asociados al proyecto.
- **`testing/casos-de-prueba.xlsx`**: Matriz de casos de prueba exportada desde Google Sheets con precondiciones, pasos, datos de prueba, resultados esperados y enlaces a evidencias.
- **`testing/hoppscotch/weather-api-collection.json`**: Colección de peticiones configuradas para Hoppscotch con los endpoints y casos de prueba sobre WeatherAPI.
- **`testing/evidencias/`**: Respuestas de ejecución (y repruebas) en formato JSON obtenidas para cada caso de prueba (ej. `TC-RT-01`, `TC-FC-01`, etc.), además de los consolidados de ejecución.
