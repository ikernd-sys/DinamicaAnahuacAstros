# Anáhuac Astros · Simulador de despegue

Simulador interactivo en 3D del despegue de un cohete tripulado, de la plataforma a la órbita.
Proyecto final de Dinámica, Universidad Anáhuac México (otoño 2026).

**Autores:** Iker Navarro Dávila y Regina Gasca Rodríguez

## Qué hace

- Integra el ascenso del cohete con gravedad, arrastre atmosférico, masa de tanques y etapas.
- Muestra el vuelo en tres vistas: exterior, cabina y mapa orbital, con una cámara de pasajeros.
- Dibuja los vectores de empuje, peso, arrastre y velocidad sobre el cohete.
- Resuelve el problema paso a paso: velocidad orbital, ecuación del cohete, impulso específico y empuje.
- Calcula el precio del boleto en cuatro escenarios de costo y busca el vuelo más económico.
- Destinos: órbita terrestre (1, 6, 14 o 30 vueltas), Luna, Marte, Saturno y el Sol.

## Cómo usarlo

Abre `index.html` en un navegador reciente (Chrome, Edge, Firefox o Safari). No necesita instalación ni conexión a internet; solo las tipografías se descargan de Google Fonts cuando hay conexión.

## Fuente del problema

C. L. Adler, *Wizards, Aliens, and Starships: Physics and Math in Fantasy and Science Fiction*, Princeton University Press, 2014, capítulo 6, «Vacations in Space». Los viajes a la Luna y a los planetas usan la transferencia de Hohmann de la sección 9.3.

## Créditos

- Gráficos 3D con [three.js](https://threejs.org) r128 (licencia MIT), incluido dentro de `index.html`.
- Imagen de la Tierra: NASA Blue Marble.
- Los precios del combustible, las masas de la nave y varios parámetros de costo son supuestos del equipo; se indican en el simulador.
