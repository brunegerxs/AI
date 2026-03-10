# AI
¿Q es la ai?
q es el machine learning?(tipos de ml)(diferentes aprendizajes)
# 🤖 Inteligencia Artificial & Machine Learning 101

¡Bienvenido! Este es un resumen rápido y visual sobre los pilares de la tecnología moderna.

---

## ✨ ¿Qué es la Inteligencia Artificial (IA)?
La **IA** es el campo de la ciencia informática que busca crear sistemas capaces de realizar tareas que, normalmente, requieren del **razonamiento humano**. No es solo "código", es la capacidad de percibir, razonar, aprender y actuar.

> 💡 **En resumen:** Es el concepto paraguas que abarca todo lo que hace que una máquina parezca "inteligente".

---

## ⚙️ ¿Qué es el Machine Learning (ML)?
El **Aprendizaje Automático** es una subcapa de la IA. En lugar de programar reglas fijas (si pasa A, hace B), le damos datos a la computadora para que ella misma **descubra los patrones** y aprenda a tomar decisiones.

### 🛤️ Tipos de Aprendizaje (ML)


| Tipo | ¿Cómo funciona? | Ejemplo real |
| :--- | :--- | :--- |
| **Supervisado** | El modelo entrena con datos etiquetados (tiene las respuestas). | Filtro de Spam (Mail) |
| **No Supervisado** | El modelo busca patrones en datos sin etiquetas (encuentra grupos). | Segmentación de clientes |
| **Semi-supervisado** | Una mezcla: pocos datos etiquetados y muchos sin etiquetar. | Reconocimiento facial |
| **Por Refuerzo** | Aprende por ensayo y error mediante premios y castigos. | IA jugando Ajedrez o Mario |

---

## 🎯 Diferencias clave
- **IA:** El destino final (crear inteligencia).
- **ML:** El camino/método para llegar ahí (aprender de los datos).
- **Deep Learning:** Una técnica específica de ML basada en redes neuronales profundas.

---
Puntúa este repo con una ⭐ si te sirvió la info.
hcaer un resumen, de mark down
# 📝 Markdown: Guía Rápida (Cheat Sheet)

Markdown es un lenguaje de marcado ligero que permite añadir formato a textos de forma simple y rápida. ¡Ideal para documentar tus proyectos en GitHub!

---

## 🏗️ Estructura de Texto

# H1 - Título Principal
## H2 - Secciones
### H3 - Subsecciones
**Este texto es negrita** y *este es cursiva*.
~~Este texto está tachado~~.

---

## 📋 Listas y Tareas

**Lista de puntos:**
- Elemento A
- Elemento B
  - Subelemento

**Lista de tareas:**
- [x] Tarea terminada
- [ ] Tarea pendiente

---

## 💻 Código y Enlaces

Para código en línea usa `backticks`. Para bloques de código:

```python
def hola_mundo():
    print("¡Hola, GitHub!")
# 📂 Big Data: El Universo de los Datos Masivos

El **Big Data** se refiere a conjuntos de datos tan grandes y complejos que las herramientas tradicionales de procesamiento no pueden manejarlos. No se trata solo de cantidad, sino de extraer **valor** de ellos.

---

## 🚀 Las 5 "V" del Big Data
Para entender el Big Data, usamos estas dimensiones clave:


| Dimensión | Descripción |
| :--- | :--- |
| **📦 Volumen** | La cantidad masiva de datos generados cada segundo (Terabytes, Petabytes). |
| **⚡ Velocidad** | La rapidez con la que se crean, procesan y analizan los datos en tiempo real. |
| **🌈 Variedad** | Los distintos formatos: estructurados (tablas), semi-estructurados y no estructurados (fotos, videos, audios). |
| **🔍 Veracidad** | La calidad y confiabilidad de los datos. ¿Son datos reales o "ruido"? |
| **💎 Valor** | El pilar más importante: transformar esos datos en información útil para tomar decisiones. |

---

## 🛠️ ¿Para qué sirve?
- **Predicción:** Anticipar tendencias de mercado o comportamientos del usuario.
- **Personalización:** Recomendaciones precisas (como Netflix o Amazon).
- **Optimización:** Mejorar procesos industriales o rutas de logística en tiempo real.

> 📊 **Dato curioso:** Se estima que cada persona genera más de 1.7 MB de datos por segundo. ¡Eso es mucho Big Data!
# 📊 Análisis de Datos (Data Analysis)

> El arte de transformar datos crudos en historias que impulsan decisiones. ✨

---

## 🔍 ¿Qué es el Análisis de Datos?
Es el proceso de **inspeccionar, limpiar y modelar datos** con el objetivo de descubrir información útil, llegar a conclusiones y apoyar la toma de decisiones. No es solo mirar números, es entender el **"por qué"** detrás de ellos.

### 🔄 El Ciclo de Vida
`Definir Pregunta` ➔ `Recolectar` ➔ `Limpiar` ➔ `Analizar` ➔ `Visualizar`

---

## 🛠️ Toolbox: Herramientas del Analista


| Categoría | Herramientas Principales |
| :--- | :--- |
| **🐍 Programación** | `Python` (Pandas, NumPy) • `R` |
| **🗄️ Bases de Datos** | `SQL` (PostgreSQL, MySQL, BigQuery) |
| **📉 Visualización** | `Tableau` • `Power BI` • `Matplotlib` / `Seaborn` |
| **📓 Entornos** | `Jupyter Notebooks` • `Google Colab` |
| **Excel Pro** | `Pivot Tables` • `VBA` • `Power Query` |

---

## 💡 Tipos de Análisis

*   **1️⃣ Descriptivo:** ¿Qué pasó? *(Resúmenes históricos)*
*   **2️⃣ Diagnóstico:** ¿Por qué pasó? *(Búsqueda de causas)*
*   **3️⃣ Predictivo:** ¿Qué podría pasar? *(Modelos y tendencias)*
*   **4️⃣ Prescriptivo:** ¿Qué deberíamos hacer? *(Recomendaciones)*

---

```sql
SELECT insight, impacto 
FROM realidad_de_datos 
WHERE valor = 'Máximo';

# 📉 Dataset vs. DataFrame: Entendiendo la diferencia

Mucha gente los confunde, pero aunque están relacionados, cumplen funciones muy distintas en el mundo de los datos.

---

## 📂 ¿Qué es un Dataset? (El Conjunto)
Es la **fuente de información**. Imaginalo como el archivo bruto. Es una colección de datos que puede venir en muchos formatos (CSV, Excel, JSON, o incluso una carpeta llena de imágenes).

> 💡 **En resumen:** Es el "paquete" de datos que descargás de internet o extraés de una base de datos.

---

## 📋 ¿Qué es un DataFrame? (La Herramienta)
Es una **estructura de datos** que vive dentro de tu código (normalmente en Python con Pandas o en R). Es una tabla bidimensional (filas y columnas) que te permite manipular, filtrar y limpiar los datos del dataset de forma fácil.

> 💡 **En resumen:** Es como abrir tu archivo CSV en un "Excel superpotente" dentro de tu programa.

---

## ⚖️ Comparativa Rápida


| Característica | Dataset | DataFrame |
| :--- | :--- | :--- |
| **Naturaleza** | Es el archivo físico o la fuente. | Es un objeto en la memoria de la PC. |
| **Formato** | .csv, .xlsx, .sql, .json | Estructura de tabla (filas/columnas). |
| **Uso** | Almacenamiento y transporte. | Análisis, limpieza y cálculos. |
| **Ejemplo** | Un archivo `ventas_2023.csv`. | La variable `df` que creás en Python. |

---

## 🧩 La Analogía Perfecta
*   El **Dataset** es la **harina** (la materia prima que está en la bolsa).
*   El **DataFrame** es la **masa** (la harina ya preparada en la mesa para empezar a cocinar).

---

```python
# Así es como convertimos un Dataset en un DataFrame
import pandas as pd

# 'data.csv' es el DATASET
df = pd.read_csv('data.csv') 

# 'df' ahora es el DATAFRAME listo para usar
print(df.head())
