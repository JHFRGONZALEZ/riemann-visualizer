[README.md](https://github.com/user-attachments/files/32309861/README.md)
# Visualizador Interactivo de Sumas de Riemann

Aplicación web educativa para visualizar y comprender las sumas de Riemann y su relación con la integral definida.

## Vista previa

La aplicación permite observar cómo los rectángulos aproximan el área bajo una curva y cómo la suma converge al valor de la integral cuando aumenta el número de subintervalos.

## Funciones principales

- Selección de funciones matemáticas predefinidas:
  - $f(x)=x^2$
  - $f(x)=x^3-x$
  - $f(x)=\sin(x)$
  - $f(x)=e^x$
  - $f(x)=\sqrt{x}$
  - $f(x)=1/x$
- Introducción de funciones personalizadas.
- Configuración de los límites de integración $a$ y $b$.
- Selección del número de subintervalos $n$.
- Métodos de suma:
  - Izquierda
  - Derecha
  - Punto medio
  - Superior
  - Inferior
- Gráfico interactivo mediante HTML Canvas.
- Gráfico de convergencia.
- Comparación con la integral exacta en funciones conocidas.
- Desarrollo paso a paso con fórmulas matemáticas mediante KaTeX.
- Animación del aumento de subintervalos.
- Exportación del gráfico como PNG.
- Exportación de resultados como archivo TXT.
- Diseño adaptable para ordenador, tablet y móvil.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- HTML Canvas
- [KaTeX](https://katex.org/) para representar fórmulas matemáticas

## Instalación y ejecución local

No se necesita instalar dependencias.

1. Descarga o clona este repositorio:

```bash
git clone https://github.com/TU_USUARIO/riemann-visualizer.git
```

2. Entra en la carpeta del proyecto:

```bash
cd riemann-visualizer
```

3. Abre `index.html` en un navegador.

También puedes abrir la carpeta en Visual Studio Code y utilizar la extensión **Live Server** para ejecutar la aplicación localmente.

## Uso

1. Selecciona una función o activa la opción **Función personalizada**.
2. Escribe los límites de integración.
3. Define el número de subintervalos.
4. Selecciona el tipo de suma.
5. Pulsa **Calcular**.
6. Usa **Comparar**, **Exacto** o **Animar** para explorar el resultado.
7. Exporta el gráfico o la tabla cuando sea necesario.

Ejemplo de función personalizada:

```text
x^2 + sin(x)
```

Funciones disponibles para expresiones personalizadas:

```text
sin, cos, sqrt, log, exp, abs, pi
```

## Publicar con GitHub Pages

1. Sube `index.html` y `README.md` al repositorio.
2. En GitHub, abre **Settings**.
3. Selecciona **Pages**.
4. En **Build and deployment**, elige:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - Carpeta: `/ (root)`
5. Pulsa **Save**.
6. GitHub generará una dirección similar a:

```text
https://TU_USUARIO.github.io/riemann-visualizer/
```

## Estructura del proyecto

```text
riemann-visualizer/
├── index.html
└── README.md
```

## Contribuciones

Las contribuciones son bienvenidas. Puedes crear un *fork*, realizar cambios y enviar un *pull request*.

## Licencia

Este proyecto se publica bajo la licencia MIT. Puedes reutilizarlo y modificarlo indicando la autoría original.
