# 📊 Estadística Aplicada con Python y R

## Ingeniería Agrícola — Periodo académico 2026-2

Repositorio académico para el desarrollo de la asignatura **Estadística Aplicada con Python y R**.

El propósito de este repositorio es integrar el aprendizaje de los fundamentos y métodos estadísticos con su aplicación computacional mediante **Python** y **R**, utilizando problemas y conjuntos de datos relacionados principalmente con el contexto de la **Ingeniería Agrícola**.

---

## 🎯 Propósito de la asignatura

La asignatura busca desarrollar en el estudiante la capacidad de **analizar, interpretar y comunicar información obtenida a partir de datos**, empleando métodos estadísticos y herramientas computacionales para apoyar la solución de problemas propios de la Ingeniería Agrícola.

Python y R se utilizarán como herramientas complementarias para:

* organizar y depurar datos;
* realizar análisis exploratorio de datos;
* calcular medidas estadísticas;
* construir visualizaciones;
* estudiar distribuciones de probabilidad;
* realizar inferencia estadística;
* construir e interpretar modelos;
* analizar relaciones entre variables;
* trabajar con datos temporales;
* interpretar resultados desde el contexto del problema estudiado.

> **El propósito del curso no es aprender comandos de Python o R de manera aislada, sino utilizar la programación y la estadística como herramientas para comprender y resolver problemas de ingeniería.**

---

## 🧩 Metodología

La asignatura se desarrolla mediante **Aprendizaje Basado en Problemas (ABP)**.

Por esta razón, las actividades no comienzan con una fórmula estadística ni con una función de Python o R.

Cada tema parte de una **situación auténtica o verosímil de Ingeniería Agrícola** que plantea preguntas que deben ser respondidas mediante datos.

La secuencia general de trabajo será:

**Situación de Ingeniería → Preguntas → Datos → Exploración → Método estadístico → Python/R → Resultados → Interpretación → Decisión**

Los problemas podrán involucrar, entre otros contextos:

* precipitación;
* temperatura;
* variables climáticas;
* suelos;
* recursos hídricos;
* riego y drenaje;
* producción agrícola;
* cultivos;
* propiedades físicas y mecánicas;
* maquinaria agrícola;
* información ambiental;
* datos experimentales y observacionales.

---

# 🐍 Python y Google Colab

Los análisis desarrollados con Python estarán disponibles principalmente mediante **Jupyter Notebooks (`.ipynb`)**.

Se utilizará **Google Colab** como entorno principal para ejecutar los notebooks sin necesidad de instalar Python localmente.

Entre las bibliotecas que podrán utilizarse se encuentran:

```text
NumPy
Pandas
Matplotlib
Seaborn
SciPy
Statsmodels
Scikit-learn
Plotly
```

Las bibliotecas específicas dependerán de las necesidades estadísticas de cada problema.

---

# 📘 R y Posit Cloud

Los análisis realizados con R se desarrollarán principalmente mediante documentos:

```text
.Rmd
```

utilizando **R Markdown** y **Posit Cloud**.

Entre los paquetes que podrán utilizarse se encuentran:

```text
tidyverse
ggplot2
dplyr
tidyr
readr
GGally
ggstatsplot
MASS
car
forecast
```

La selección de paquetes dependerá del problema y del método estadístico estudiado.

---

# 🔄 Un problema, dos lenguajes

Python y R no constituyen dos cursos diferentes.

Siempre que resulte pedagógicamente apropiado, un mismo problema estadístico podrá estudiarse utilizando ambos lenguajes.

Por ejemplo:

```text
Problema de Ingeniería Agrícola
              │
              ▼
        Conjunto de datos
              │
       ┌──────┴──────┐
       │             │
       ▼             ▼
    Python           R
 Google Colab    Posit Cloud
       │             │
       └──────┬──────┘
              ▼
      Análisis estadístico
              │
              ▼
        Interpretación
              │
              ▼
     Decisión de ingeniería
```

El objetivo no será determinar cuál lenguaje es «mejor», sino reconocer las fortalezas de cada ecosistema y desarrollar la capacidad de utilizar diferentes herramientas computacionales para resolver problemas estadísticos.

---

# 📁 Organización del repositorio

El repositorio está organizado principalmente por **semanas de trabajo**.

```text
Estadistica_Aplicada_Python_R/
│
├── README.md
├── .gitignore
│
├── datos/
│
├── Semana_01/
│   ├── README.md
│   ├── Python/
│   │   └── Semana_01.ipynb
│   └── R/
│       └── Semana_01.Rmd
│
├── Semana_02/
│   ├── README.md
│   ├── Python/
│   │   └── Semana_02.ipynb
│   └── R/
│       └── Semana_02.Rmd
│
├── Semana_03/
│   ├── README.md
│   ├── Python/
│   └── R/
│
├── ...
│
├── Semana_16/
│   ├── README.md
│   ├── Python/
│   └── R/
│
├── recursos/
│   ├── guias/
│   └── lecturas/
│
└── imagenes/
```

---

# 📂 Carpeta `datos`

La carpeta:

```text
datos/
```

contiene conjuntos de datos utilizados durante el desarrollo de la asignatura.

Siempre que sea posible, los mismos datos serán utilizados desde Python y R para facilitar la comparación de procedimientos y resultados.

Los datos podrán proceder de:

* fuentes públicas;
* repositorios institucionales;
* organismos nacionales e internacionales;
* paquetes estadísticos;
* conjuntos de datos académicos;
* datos construidos con propósitos didácticos.

Cuando corresponda, se indicará la fuente original de los datos.

---

# 🗓️ Organización semanal

Cada semana podrá contener:

### 1. Situación problema

Descripción del problema de Ingeniería Agrícola que da origen al análisis.

### 2. Preguntas orientadoras

Preguntas que permitan identificar qué información se necesita obtener de los datos.

### 3. Datos

Presentación, descripción y procedencia del conjunto de datos.

### 4. Análisis exploratorio

Exploración inicial antes de seleccionar procedimientos estadísticos.

### 5. Fundamentos estadísticos

Conceptos necesarios para comprender el método utilizado.

### 6. Implementación con Python

Desarrollo mediante Google Colab.

### 7. Implementación con R

Desarrollo mediante R Markdown y Posit Cloud.

### 8. Interpretación

Los resultados numéricos y gráficos deberán interpretarse dentro del contexto del problema.

### 9. Actividad del estudiante

Aplicación de los conceptos estudiados a un problema relacionado.

---

# 🤖 Uso de Inteligencia Artificial

Las herramientas de Inteligencia Artificial podrán utilizarse como **apoyo al aprendizaje**, no como sustituto del razonamiento del estudiante.

Su utilización deberá favorecer actividades como:

* comprender código;
* detectar y corregir errores;
* comparar alternativas de solución;
* documentar programas;
* explorar métodos estadísticos;
* formular preguntas;
* revisar interpretaciones;
* desarrollar soluciones mediante interacción con asistentes de IA.

El estudiante deberá conservar la capacidad de:

1. explicar el problema;
2. justificar el procedimiento estadístico utilizado;
3. comprender el código;
4. interpretar los resultados;
5. detectar resultados incoherentes;
6. modificar la solución;
7. defender sus decisiones.

> **Un resultado generado por Inteligencia Artificial que el estudiante no pueda explicar no constituye evidencia suficiente de aprendizaje.**

---

# 🧠 Reserva cognitiva y aprendizaje

El uso de herramientas computacionales e Inteligencia Artificial debe acompañarse del desarrollo del razonamiento propio.

Durante la asignatura podrán combinarse actividades computacionales con ejercicios de análisis, interpretación, argumentación, escritura y resolución manual.

El objetivo es utilizar la tecnología para **ampliar las capacidades del estudiante**, preservando al mismo tiempo las habilidades fundamentales necesarias para comprender y evaluar críticamente los resultados.

---

# 🌐 Herramientas de trabajo

| Herramienta       | Uso principal                        |
| ----------------- | ------------------------------------ |
| **GitHub**        | Repositorio central del curso        |
| **Google Colab**  | Ejecución de notebooks de Python     |
| **Python**        | Análisis estadístico y computacional |
| **Posit Cloud**   | Entorno de trabajo para R            |
| **R**             | Análisis estadístico                 |
| **R Markdown**    | Documentos reproducibles             |
| **Git**           | Control de versiones                 |
| **IA generativa** | Apoyo al aprendizaje y desarrollo    |

---

# 🔁 Flujo de trabajo

El repositorio GitHub funciona como punto central de integración:

```text
                        GitHub
                           │
              ┌────────────┴────────────┐
              │                         │
              ▼                         ▼
        Google Colab                Posit Cloud
              │                         │
           Python                        R
          .ipynb                       .Rmd
              │                         │
              └────────────┬────────────┘
                           │
                           ▼
                     Análisis de datos
                           │
                           ▼
                     Interpretación
                           │
                           ▼
                  Problema de Ingeniería
```

---

# 📌 Recomendaciones para los estudiantes

Antes de ejecutar código:

**Comprenda el problema.**

Antes de aplicar una técnica estadística:

**Explore los datos.**

Antes de aceptar un resultado:

**Pregúntese si tiene sentido.**

Antes de presentar una gráfica:

**Determine qué información comunica.**

Antes de aceptar código generado por IA:

**Comprenda qué hace y por qué funciona.**

Y antes de concluir:

**Regrese al problema original de Ingeniería Agrícola.**

---

# 📚 Principio orientador

> **Los datos por sí solos no resuelven problemas. La estadística permite convertir datos en evidencia; la programación permite realizar el análisis de manera reproducible; y el criterio profesional permite transformar los resultados en decisiones de ingeniería.**

---

## 👨‍🏫 Docente

**Justo Fuentes**

Universidad de Sucre
Facultad de Ingeniería
Programa de Ingeniería Agrícola

**Asignatura:** Estadística Aplicada con Python y R
**Periodo académico:** 2026-2

---

## 📄 Uso académico

Este repositorio contiene material preparado con fines académicos para apoyar los procesos de enseñanza y aprendizaje de la asignatura **Estadística Aplicada con Python y R**.

Los conjuntos de datos, documentos y demás recursos provenientes de fuentes externas conservarán las condiciones de uso, licencias y atribuciones establecidas por sus respectivos autores o instituciones.
