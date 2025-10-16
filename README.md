# Tarea Dev Junior - Ruuf

## 🎯 Objetivo

El objetivo de este ejercicio es poder entender tus habilidades como programador/a, la forma en que planteas un problema, cómo los resuelves y finalmente cómo comunicas tu forma de razonar y resultados.

## 🛠️ Problema

El problema a resolver consiste en encontrar la máxima cantidad de rectángulos de dimensiones "a" y "b" (paneles solares) que caben dentro de un rectángulo de dimensiones "x" e "y" (techo).

## Soluciones
para resolver este problema se considerarón 2 opciones 
la primera opcion  al ser dos figuras rectangulares al comparar las areas directamente es posible saber cuantos paneles caben en el techo independientemente de la posicion 

la segunda opcion es tratar el techo como una matriz, y recorrerla probando en cada posicion si un panel puede ser colocado en la matriz, si se logra colocar con exito se contabiliza y se continua en la siguiente posicion vacia.

se escogio la primera opcion por la simplicidad de aplicación y la baja complejidad algoritmica


## 🚀 Cómo Empezar
### Solución en Python
```bash
cd python
python3 main.py
```

## ✅ Casos de Prueba

Tu solución debe pasar los siguientes casos de prueba:
- Paneles 1x2 y techo 2x4 ⇒ Caben 4
- Paneles 1x2 y techo 3x5 ⇒ Caben 7
- Paneles 2x2 y techo 1x10 ⇒ Caben 0

---

## 📝 Tu Solución

video explicando la solucion https://www.youtube.com/watch?v=ZWS2KqHGT6U
---

## 💰 Bonus (Opcional)

Si completaste alguno de los ejercicios bonus, explica tu solución aquí:

### Bonus Implementado
*[Indica cuál bonus implementaste: Opción 1 (techo triangular) o Opción 2 (rectángulos superpuestos)]*




### Explicación del Bonus
*[Explica cómo adaptaste tu algoritmo para resolver el bonus]*




---

## 🤔 Supuestos y Decisiones

*[Si tuviste que tomar algún supuesto o decisión de diseño, explícalo aquí]*

