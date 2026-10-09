# MENDOZA MAMANI JAIR EDISSON
# Calculadora de Desviación Estándar

Aplicación web desarrollada con **HTML, CSS y JavaScript** para calcular estadísticamente la desviación estándar de un conjunto de datos.

## Características

- Ingreso de datos separados por comas, espacios o saltos de línea.
- Cálculo de la media aritmética.
- Cálculo de la varianza.
- Cálculo de la desviación estándar.
- Modo **muestra (n − 1)**.
- Modo **población (n)**.
- Procedimiento paso a paso.
- Tabla con las desviaciones y sus cuadrados.
- Diseño adaptable para computadora y celular.
- No utiliza librerías ni conexión a Internet.

## Cómo usar

1. Abre `index.html` en un navegador.
2. Introduce los valores numéricos.
3. Selecciona **Muestra** o **Población**.
4. Pulsa **Calcular**.

### Ejemplo

```text
10, 12, 15, 18, 20
```

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `README.md` y `.gitignore`.
3. Entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda los cambios.

GitHub generará una dirección para acceder a la aplicación publicada.

## Tecnologías

- HTML5
- CSS3
- JavaScript

## Fórmulas utilizadas

### Media

`x̄ = Σx / n`

### Varianza poblacional

`σ² = Σ(x − x̄)² / n`

### Desviación estándar poblacional

`σ = √σ²`

### Varianza muestral

`s² = Σ(x − x̄)² / (n − 1)`

### Desviación estándar muestral

`s = √s²`
