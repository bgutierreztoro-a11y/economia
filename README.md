# Laboratorio de Mercado

App interactiva para aprender oferta y demanda haciendo, no leyendo. El alumno arrastra curvas, mueve precios y cumple misiones que se verifican solas.

**Cómo usarla:** abre `index.html` en cualquier navegador. No necesita instalación ni conexión, salvo para cargar las tipografías.

## Módulos

| # | Módulo | Qué hace el alumno |
|---|--------|--------------------|
| 1 | Equilibrio | Arrastra la línea de precio y ve la escasez y el excedente en vivo. Busca el equilibrio y predice hacia dónde se ajusta el mercado. |
| 2 | Cambios en el mercado | Lee un hecho (sequía, ingreso, tecnología, expectativas…) y **arrastra la curva** que se desplaza. Después lee el nuevo precio y la nueva cantidad. Incluye un caso trampa (movimiento a lo largo de la curva) y un laboratorio libre con retos. |
| 3 | Elasticidad | Arrastra dos puntos sobre la demanda y ve el ingreso (P × Q) como rectángulos. Predice antes de ver los números, encuentra el ingreso máximo (\|E\| = 1) y compara la elasticidad de distintos bienes. |
| 4 | Excedentes | Toca las áreas de excedente del consumidor y del productor, calcula una de ellas y fija precios máximos o mínimos arrastrando la línea para ver la pérdida irrecuperable. |
| 5 | Desafío | Ejercicios con números nuevos en cada intento (equilibrio, elasticidad por punto medio, excedente y desplazamientos), con solución paso a paso. |

El progreso de las misiones se guarda en el navegador del alumno.

## En qué se basa

Revisé herramientas parecidas: el analizador de shocks de elysiatools, el modelo de oferta y demanda de iwant2study, la práctica de excedentes de Marginal Revolution University y la demostración de Wolfram. Casi todas muestran un gráfico con sliders y dejan al alumno mirando. Esta app pide que el alumno decida primero (qué curva se mueve, hacia dónde, qué pasa con el ingreso) y solo después le muestra el resultado.

## Modelo

- Demanda inversa: `P = 100 − Q`
- Oferta inversa: `P = 20 + 0,6·Q`
- Equilibrio: `P* = 50`, `Q* = 50`
