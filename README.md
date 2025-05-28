# 🏪 AluraStore LATAM - Análisis de Rendimiento de Tiendas

<div align="center">
  
![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-v1.3+-green.svg)
![Matplotlib](https://img.shields.io/badge/matplotlib-v3.3+-red.svg)
![Status](https://img.shields.io/badge/status-complete-success.svg)

*Análisis exhaustivo de datos para la toma de decisiones empresariales estratégicas*

</div>

---

## 📋 Descripción del Proyecto

Este proyecto realiza un **análisis comparativo integral** de cuatro tiendas de AluraStore LATAM para determinar cuál representa la **menor eficiencia operativa** y, por tanto, debería ser considerada para venta. El análisis se basa en múltiples métricas de rendimiento empresarial y utiliza técnicas de visualización de datos para facilitar la toma de decisiones.

### 🎯 Objetivo Principal
Proporcionar una recomendación fundamentada al Sr. Juan sobre qué tienda vender, basándose en un análisis cuantitativo de:
- Rendimiento financiero
- Satisfacción del cliente
- Eficiencia operativa
- Distribución geográfica de ventas

---

## 🔍 Metodología de Análisis

### 📊 Métricas Evaluadas

| Métrica | Descripción | Importancia |
|---------|-------------|-------------|
| **Ingresos Totales** | Facturación total por tienda | Alto |
| **Calificación Promedio** | Satisfacción del cliente (1-5) | Alto |
| **Costo de Envío** | Promedio de gastos logísticos | Medio |
| **Ventas por Categoría** | Distribución de productos vendidos | Medio |
| **Productos Top/Bottom** | Rendimiento por producto individual | Bajo |

### 🎨 Visualizaciones Implementadas

- **Gráficos de Barras Comparativos**: Ingresos, calificaciones y costos de envío
- **Gráficos de Pastel**: Distribución de ventas por categoría
- **Gráficos de Barras Horizontales**: Top 10 productos más/menos vendidos
- **Mapas Interactivos**: Distribución geográfica de ventas (Folium)
- **Mapas de Calor**: Concentración de ventas e ingresos

---

## 🛠️ Tecnologías y Dependencias

### Lenguajes y Frameworks
```python
Python 3.7+
```

### Librerías Principales
```bash
pandas>=1.3.0          # Manipulación y análisis de datos
matplotlib>=3.3.0      # Visualización estática
folium>=0.12.0         # Mapas interactivos
numpy>=1.19.0          # Operaciones numéricas
```

### Instalación de Dependencias
```bash
# Para entorno local
pip install pandas matplotlib folium numpy

# Para Google Colab
!pip install folium -q
```

---

## 🚀 Estructura del Proyecto

```
AluraStoreLatam/
│
├── alurastorelatam.py          # Script principal de análisis
├── README.md                   # Documentación del proyecto
│
├── data/                       # Fuentes de datos (URLs)
│   ├── tienda_1.csv           # Datos Tienda 1
│   ├── tienda_2.csv           # Datos Tienda 2
│   ├── tienda_3.csv           # Datos Tienda 3
│   └── tienda_4.csv           # Datos Tienda 4
│
└── outputs/                    # Visualizaciones generadas
    ├── graficos_comparativos/
    ├── mapas_interactivos/
    └── informe_final.txt
```

---

## 💻 Uso del Proyecto

### 1. Clonar el Repositorio
```bash
git clone https://github.com/tu-usuario/alurastore-latam-analysis.git
cd alurastore-latam-analysis
```

### 2. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 3. Ejecutar el Análisis
```python
python alurastorelatam.py
```

### 4. Para Google Colab
1. Abrir el notebook en Google Colab
2. Ejecutar todas las celdas secuencialmente
3. Las visualizaciones se generarán automáticamente

---

## 📈 Resultados Principales

### 💰 Análisis Financiero
- **Tienda 1**: $1,150,880,400.00 (Mayor ingreso)
- **Tienda 2**: $1,116,343,500.00
- **Tienda 3**: $1,098,019,600.00
- **Tienda 4**: $1,038,375,700.00 (Menor ingreso)

### ⭐ Satisfacción del Cliente
- **Tienda 3**: Mejor calificación promedio
- **Tienda 1**: Menor calificación promedio

### 🚚 Eficiencia Logística
- **Tienda 4**: Menor costo de envío
- **Tienda 1**: Mayor costo de envío

### 🏆 Recomendación Final
**TIENDA 4** - Candidata para venta por:
- Menores ingresos totales
- Dependencia de categoría de bajo volumen (muebles)
- Menor costo de envío (ventaja operativa limitada)

---

## 📊 Visualizaciones Destacadas

### Gráficos Comparativos
- Ingresos totales por tienda
- Calificaciones promedio por tienda
- Costos de envío comparativos

### Análisis Geoespacial
- Distribución de ventas por ubicación
- Mapas de calor de ingresos
- Concentración de clientes por zona

### Análisis por Categorías
- Distribución de ventas por categoría (gráficos de pastel)
- Productos más/menos vendidos por tienda

---

## 🔧 Funcionalidades Técnicas

### Procesamiento de Datos
- Limpieza automática de datos nulos
- Conversión de tipos de datos numéricos
- Agregación de métricas por tienda

### Visualizaciones Interactivas
- Mapas con Folium
- Tooltips informativos
- Capas de calor superpuestas

### Generación de Reportes
- Informe ejecutivo automatizado
- Tabla resumen de métricas clave
- Justificación fundamentada de decisiones

---

## 📋 Fuentes de Datos

Los datos provienen de cuatro archivos CSV alojados en el repositorio oficial de Alura:

```python
# URLs de las fuentes de datos
TIENDA_1 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv"
TIENDA_2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv"
TIENDA_3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv"
TIENDA_4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"
```

---

## 🎯 Casos de Uso

### Para Empresarios
- Evaluación de rendimiento de sucursales
- Decisiones de expansión o cierre
- Optimización de portafolio de tiendas

### Para Analistas de Datos
- Ejemplo de análisis comparativo
- Técnicas de visualización empresarial
- Metodología de análisis multivariable

### Para Estudiantes
- Proyecto práctico de Data Science
- Aplicación de pandas y matplotlib
- Análisis geoespacial con Python

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para detalles.

---

## 👨‍💻 Autor

**Marco Rodrigo Polo Silva**
- GitHub: [@MarteDevs](https://github.com/MarteDevs)
- LinkedIn: [Tu Perfil](linkedin.com/in/noark-mps)
- Email: soumartex@gmail.com

---

## 🙏 Agradecimientos

- **Alura LATAM** por proporcionar los datos del desafío
- **Google Colab** por la plataforma de desarrollo
- **Comunidad Python** por las librerías utilizadas

---

<div align="center">

### ⭐ Si este proyecto te fue útil, ¡dale una estrella!

**Hecho con ❤️ para la comunidad de Data Science**

</div>
