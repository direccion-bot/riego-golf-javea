# Riego — Club de Golf Jávea

Herramienta de gestión del plan de riego diario del Club de Golf Jávea.

## Funcionalidades

- Recomendación de m³ de riego diario basada en temperatura, lluvia y viento
- Datos meteorológicos en tiempo real (Open-Meteo · ECMWF)
- Panel de estación local Meteoxabia con entrada manual de mm de lluvia
- Registro diario de consumo real por lectura de contador
- Historial mensual con comparativa frente al plan base
- Funciona offline tras la primera carga (datos cacheados en el dispositivo)

## Uso

Accede directamente desde el navegador en:  
`https://<tu-usuario>.github.io/riego-golf-javea/`

## Datos meteorológicos

- **Fuente principal:** [Open-Meteo](https://open-meteo.com) (modelo ECMWF, resolución ~9 km)
- **Estación local:** [Meteoxabia · Club de Golf Jávea](https://www.meteoxabia.com/golf.htm) (entrada manual)

## Notas técnicas

- Todos los datos se guardan localmente en el dispositivo (localStorage)
- No requiere servidor ni base de datos
- Compatible con iPhone/Android como PWA (añadir a pantalla de inicio)
