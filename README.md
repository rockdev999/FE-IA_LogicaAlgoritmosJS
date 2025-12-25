# Planificador de Viajes

Aplicación simple para registrar destinos de viaje y calcular costos totales basados en transporte y destino.

## Descripción

Este proyecto es un planificador de viajes que permite:
- Registrar destinos con fecha y tipo de transporte
- Calcular automáticamente el costo del viaje
- Mostrar un itinerario completo de los viajes registrados

## Tecnologías utilizadas

- JavaScript ES6+
- Módulos ES6 (import/export)
- HTML5

## Estructura del proyecto
```
proyecto-viajes/
├── index.html
├── viajes.js
├── app.js
└── README.md
```

## Instalación y uso

1. Clona o descarga este repositorio
2. Abre el archivo `index.html` en tu navegador
3. Abre la consola del navegador (F12) para ver los resultados

## Funcionalidades

### Registrar destinos
La función `registrarDestino()` permite agregar nuevos viajes al sistema.

### Calcular costos
El sistema calcula automáticamente el costo basándose en:
- Costo base por destino (París: $500, Londres: $400, Nueva York: $600)
- Costo adicional por transporte (Avión: +$200, Tren: +$100)

### Mostrar itinerario
La función `mostrarItinerario()` muestra todos los viajes registrados con sus detalles.

## Mejoras implementadas (ES6+)

- Uso de `const` y `let` en lugar de `var`
- Funciones flecha para sintaxis moderna
- Template literals para concatenación de strings
- Módulos ES6 con export/import
- Bucles for...of en lugar de for tradicional

## Autor

Tu nombre

## Fecha

Diciembre 2025
