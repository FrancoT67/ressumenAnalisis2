# Guía Paso a Paso: Resolución de Ejercicios de Análisis Matemático II

Este documento contiene los pasos necesarios para resolver cada tipo de ejercicio de tu Práctico 5 de Análisis Matemático II, enfocado en funciones de varias variables.

## 1. Dominio y Gráficos
Para determinar el dominio de una función de varias variables:
   - **Identifica las restricciones**: Observa los términos en la función. Si hay una raíz cuadrada, el argumento debe ser mayor o igual a cero. Si hay fracciones, el denominador no puede ser cero.
   - **Expresa el dominio**: Especifica las restricciones en términos de x e y. Por ejemplo, si tienes \( f(x, y) = \sqrt{x + y} \), el dominio es donde \( x + y \geq 0 \).
   - **Grafica el dominio** en el plano XY, sombreando las áreas válidas para x e y.

## 2. Bosquejo de Gráficas
Para graficar superficies comunes:
   - **Paraboloide**: Ejemplo \( f(x, y) = x^2 + y^2 \). Esta superficie es como un "tazón" abierto hacia arriba. Dibuja su contorno en varias secciones horizontales.
   - **Cono**: Ejemplo \( f(x, y) = \sqrt{x^2 + y^2} \). Visualízalo como una superficie en punta; sus secciones son círculos concéntricos.
   - **Silla de montar**: Ejemplo \( f(x, y) = x^2 - y^2 \). La gráfica se curva hacia arriba y hacia abajo en diferentes direcciones.

## 3. Derivadas Parciales
   - **Derivación con respecto a una variable**: Mantén las demás variables constantes. Por ejemplo, para \( f(x, y) = x^2y + y^2 \):
       - Derivada con respecto a \( x \): \( \frac{\partial f}{\partial x} = 2xy \).
       - Derivada con respecto a \( y \): \( \frac{\partial f}{\partial y} = x^2 + 2y \).
   - **Evaluación en un punto**: Si se indica un punto (p.ej., \( (x_0, y_0) \)), reemplaza las variables por los valores dados.

## 4. Planos Tangentes y Rectas Normales
Para hallar la ecuación del plano tangente de \( f(x, y) \) en un punto \( (x_0, y_0) \):
   - Calcula \( \frac{\partial f}{\partial x} \) y \( \frac{\partial f}{\partial y} \).
   - Usa la fórmula: \( z = f(x_0, y_0) + \frac{\partial f}{\partial x}(x_0, y_0)(x - x_0) + \frac{\partial f}{\partial y}(x_0, y_0)(y - y_0) \).

## 5. Gradiente y Derivada Direccional
   - **Gradiente**: Es el vector \( \nabla f = \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right) \).
   - **Derivada direccional**: Para un vector unitario \( \vec{u} = (a, b) \), calcula la derivada en la dirección de \( \vec{u} \) como \( D_{\vec{u}} f = \nabla f \cdot \vec{u} = \frac{\partial f}{\partial x} \cdot a + \frac{\partial f}{\partial y} \cdot b \).

## 6. Regla de la Cadena y Derivadas Segundas
   - **Regla de la cadena**: Si \( z \) depende de \( x \) e \( y \), y a su vez \( x \) e \( y \) dependen de \( t \), entonces:  
     \[
     \frac{dz}{dt} = \frac{\partial z}{\partial x} \cdot \frac{dx}{dt} + \frac{\partial z}{\partial y} \cdot \frac{dy}{dt}
     \]

## 7. Puntos Críticos y Extremos
   - **Encuentra puntos críticos** resolviendo \( \nabla f = 0 \), es decir, igualando las derivadas parciales a cero.
   - **Clasifica los puntos** usando la segunda derivada. Un análisis común involucra el discriminante \( D = f_{xx}f_{yy} - (f_{xy})^2 \):
       - \( D > 0 \) y \( f_{xx} > 0 \): Mínimo.
       - \( D > 0 \) y \( f_{xx} < 0 \): Máximo.
       - \( D < 0 \): Punto silla.

## 8. Curvas y Superficies de Nivel
   - **Recta tangente a una curva de nivel**: Para una curva \( f(x, y) = c \), encuentra el gradiente \( \nabla f \) en el punto dado. La recta tangente es perpendicular al gradiente.
   - **Plano tangente a una superficie**: Para superficies de nivel de la forma \( f(x, y, z) = c \), calcula las derivadas parciales en el punto y construye el plano tangente similar al caso de funciones en dos variables.

---

¡Buena suerte en tu examen!
