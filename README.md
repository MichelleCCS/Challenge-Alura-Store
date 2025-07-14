# 📊 Challenge-Alura-Store LATAM

Este proyecto corresponde al análisis de datos de la cadena **Alura Store** con el fin de ayudar al Sr. Juan a tomar una decisión estratégica: **¿cuál de sus tiendas debe vender para emprender un nuevo proyecto?**

Se trabajó en un entorno Google Colab, utilizando Python y bibliotecas como **Pandas** y **Matplotlib**.

---

## 📌 Objetivo

Identificar la tienda con el **menor rendimiento relativo** entre las cuatro que posee el Sr. Juan, para recomendar cuál debería vender.  
El análisis se basa en los siguientes factores:

- Ingresos totales por tienda
- Categorías de productos más y menos vendidas
- Calificaciones promedio de clientes
- Productos más y menos vendidos
- Coste promedio de envío

---

## 📥 Datos utilizados

Los datos fueron importados desde archivos CSV públicos mediante enlaces en GitHub.  
Cada archivo representa una tienda distinta:

- `tienda`, `tienda2`, `tienda3`, `tienda4`

---

## 📈 Análisis Realizado

### 1. Ingresos Totales

| Tienda | Ingresos |
|--------|----------|
| 1      | $1,150,880,400 |
| 2      | $1,116,343,500 |
| 3      | $1,098,019,600 |
| 4      | $1,038,375,700 |

✅ **Tienda 1 es igual a tienda** genera la mayor facturación.  
❌ **Tienda 4** es la que menos factura.

---

### 2. Calificaciones Promedio

| Tienda | Calificación Promedio |
|--------|------------------------|
| 1      | 3.98 |
| 2      | 4.04 |
| 3      | 4.05 |
| 4      | 3.99 |

📌 Tienda 3 se destaca con la mejor valoración por parte de clientes.

---

### 3. Costo Promedio de Envío

| Tienda | Costo Promedio |
|--------|----------------|
| 1      | $26,019 |
| 2      | $25,216 |
| 3      | $24,806 |
| 4      | $23,459 |

📦 **Tienda 4** tiene el envío más económico.

---

### 4. Categorías Más Vendidas

En las cuatro tiendas, la categoría **"Electrónicos"** es la más vendida.

| Tienda | Ventas Electrónicos |
|--------|----------------------|
| 1      | $429,493,500 |
| 2      | $410,831,100 |
| 3      | $410,775,800 |
| 4      | $409,476,100 |

---

### 5. Productos Más y Menos Vendidos

#### Más Vendidos (comunes en todas):
- iPhone 15
- TV LED UHD 4K
- Refrigerador / Smart TV

#### Menos Vendidos (comunes en todas):
- Cuerda para saltar
- Dinosaurio Rex
- Cubo mágico 8x8

---

## ✅ Recomendación Final

Se recomienda **vender la Tienda 4** por las siguientes razones:

- Tiene el **menor nivel de ingresos** totales.
- Aunque su costo de envío es más bajo, **no compensa el bajo rendimiento global**.
- Su calificación promedio y categoría principal son similares a otras, **sin destacarse especialmente**.

---

## 📚 Tecnologías Utilizadas

- Python 3.11+
- Pandas
- Matplotlib
- Google Colab

---

## 📎 Autor

Este análisis fue desarrollado como parte del **Challenge Data Science - Alura LATAM**.

