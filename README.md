<p align="center">
  <img src="pontificia_universidad_javeriana_logo.jpg" alt="Pontificia Universidad Javeriana" width="260"/>
</p>

<h1 align="center">Procesamiento de Datos a Gran Escala</h1>
<h3 align="center">Fundamentos de Python — Cuadernos de Clase y Práctica Bono</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.x"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
  <img src="https://img.shields.io/badge/Cuadernos-10-blue?style=flat-square" alt="10 cuadernos"/>
  <img src="https://img.shields.io/badge/Estado-En%20curso-yellow?style=flat-square" alt="Estado: en curso"/>
  <img src="https://img.shields.io/badge/Licencia-Uso%20académico-lightgrey?style=flat-square" alt="Licencia: uso académico"/>
</p>

<table align="center">
  <tr>
    <td><b>Universidad</b></td>
    <td>Pontificia Universidad Javeriana</td>
  </tr>
  <tr>
    <td><b>Facultad</b></td>
    <td>Facultad de Ingeniería</td>
  </tr>
  <tr>
    <td><b>Materia</b></td>
    <td>Procesamiento de Datos a Gran Escala</td>
  </tr>
  <tr>
    <td><b>Número de clase</b></td>
    <td>1055</td>
  </tr>
  <tr>
    <td><b>Profesor</b></td>
    <td>John Jairo Corredor Franco</td>
  </tr>
  <tr>
    <td><b>Autora</b></td>
    <td>Monica Maria Castro Benitez</td>
  </tr>
</table>

<p align="center">
  <a href="#-descripción">Descripción</a> •
  <a href="#-qué-encontrarás-aquí">Contenido</a> •
  <a href="#-estructura-del-repositorio">Estructura</a> •
  <a href="#-cómo-usar-este-repositorio">Cómo usarlo</a> •
  <a href="#-requisitos">Requisitos</a> •
  <a href="#-metodología-de-los-cuadernos">Metodología</a> •
  <a href="#-licencia">Licencia</a>
</p>

---

## Descripción

Este repositorio reúne los cuadernos de Jupyter desarrollados para la asignatura **Procesamiento de Datos a Gran Escala**, correspondientes al módulo introductorio de **Python**. Cada cuaderno cubre un tema fundamental del lenguaje —desde tipos de datos básicos hasta programación orientada a objetos— con teoría, ejemplos ejecutables, ejercicios resueltos y un examen final de repaso.

Todos los cuadernos, además del contenido original del curso, incluyen **fichas de explicación** después de cada bloque de código: recuadros que describen en lenguaje claro qué hace la instrucción, por qué produce ese resultado y qué conceptos de Python están en juego.

## ¿Qué encontrarás aquí?

- **10 cuadernos de Jupyter** organizados progresivamente, del nivel básico al intermedio.
- **Fichas de explicación** en cada celda de código, con el detalle de cada instrucción.
- **Ejemplos integradores** al final de cada tema, que combinan todos los conceptos vistos.
- **Cuestionarios resueltos** para practicar y autoevaluar lo aprendido.
- Un **cuaderno de práctica bono**, con ejercicios de repaso de dificultad creciente.

## Estructura del repositorio

```
ProcesamientoDatos/
│
├── README.md
└── Cuadernos - Primer laboratorio/
    │
    ├── 01-Python-Cadenas_MC.ipynb          # Cadenas (strings): indexación, slicing, métodos
    ├── 02-Python-Tuplas_MC.ipynb           # Tuplas: indexación, concatenación, anidamiento
    ├── 03-Python-Listas_MC.ipynb           # Listas: mutabilidad, copia por referencia vs. clonación
    ├── 04-Python-Conjuntos_MC.ipynb        # Conjuntos: operaciones lógicas (unión, intersección...)
    ├── 05-Python-Diccionarios_MC.ipynb     # Diccionarios: llaves, valores, keys()/values()
    ├── 06-Python-Condiciones_MC.ipynb      # Condicionales: if/elif/else, operadores lógicos
    ├── 07-Python-Bucles_MC.ipynb           # Bucles: range(), for, while
    ├── 08-Python-Funciones_MC.ipynb        # Funciones: parámetros, return, alcance de variables
    ├── 09_Python_Clases_MC.ipynb           # Clases y objetos: atributos, métodos, __init__
    ├── Practico_Bono_1_MC.ipynb            # Práctica bono: ejercicios de repaso integrador
    └── pontificia_universidad_javeriana_logo.jpg
```

## Cómo usar este repositorio

1. **Clona o descarga** el repositorio en tu equipo.
2. **Abre los cuadernos en orden** (01 → 09) si estás siguiendo el curso desde cero, ya que cada uno se apoya en conceptos del anterior.
3. **Ejecuta las celdas de código** con `Shift + Enter` y lee la ficha de explicación que aparece justo debajo de cada una.
4. **Resuelve los cuestionarios** de cada cuaderno antes de revisar la solución sugerida en los comentarios.
5. Revisa `Practico_Bono_1_MC.ipynb` como repaso final una vez completados los nueve cuadernos temáticos.

## Requisitos

Para ejecutar los cuadernos localmente necesitas:

- **Python 3.8** o superior
- **Jupyter Notebook** o **JupyterLab**
- **matplotlib** (usado en el cuaderno 09 - Clases, para dibujar figuras)

Instalación rápida de las dependencias:

```bash
pip install notebook matplotlib
```

Y para iniciar Jupyter:

```bash
jupyter notebook
```

## Metodología de los cuadernos

Cada cuaderno sigue la misma estructura:

| Sección | Contenido |
|---|---|
| **Introducción** | Contexto general del tema y su relevancia |
| **Objetivos** | Objetivo general y objetivos específicos de aprendizaje |
| **Resumen de conceptos clave** | Glosario rápido de los términos que se van a usar |
| **Desarrollo teórico-práctico** | Explicación de cada operación, con celdas de código y su ficha de explicación |
| **Ejemplo integrador** | Un caso que combina todos los conceptos del cuaderno |
| **Cuestionario** | Ejercicios prácticos con solución oculta para autoevaluación |
| **Conclusiones** | Cierre con las ideas más importantes del cuaderno |

Las fichas de explicación siguen un formato visual consistente en todo el repositorio:

> **Explicación del bloque**
> Descripción clara de qué hace el código, qué resultado produce y por qué.

## Autora

**Monica Maria Castro Benitez**
Facultad de Ingeniería — Pontificia Universidad Javeriana

## Licencia

Material desarrollado con fines **académicos** para la asignatura Procesamiento de Datos a Gran Escala de la Pontificia Universidad Javeriana. Su uso y distribución quedan sujetos a las políticas académicas de la universidad.

---

<p align="center">
  <i>README elaborado siguiendo la <a href="https://github.com/Organization-DevXP/Guia-para-crear-READMEs-Profesionales">Guía para Crear READMEs Profesionales</a> de Organization-DevXP.</i>
</p>
