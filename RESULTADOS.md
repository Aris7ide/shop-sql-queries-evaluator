# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 28 correctas de 36 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio truncado
+nombre | precio_truncado
 Disco duro SATA3 1TB | 86.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 150.00
```

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.11 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.11 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.10 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 16: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,6 @@
-codigo | nombre
-1.00 | Asus
-2.00 | Lenovo
-3.00 | Hewlett-Packard
-4.00 | Samsung
-5.00 | Seagate
+nombre
+Asus
+Lenovo
+Hewlett-Packard
+Samsung
+Seagate
```

⏱ Tiempo: 0.11 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 17: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-codigo | nombre
-4.00 | Samsung
-5.00 | Seagate
+nombre
+Samsung
+Seagate
```

⏱ Tiempo: 0.11 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.11 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.10 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.12 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.13 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricant
+nombre | precio | fabricante
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
```

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 27: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 28: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 29: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1 @@
 nombre | precio | fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
```

⏱ Tiempo: 0.20 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ✅ Query 30: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 31: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,7 @@
 nombre | precio | fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+GeForce GTX 1050Ti | 185.00 | Gigabyte
+Portátil Yoga 520 | 559.00 | Lenovo
+Portátil Ideapd 320 | 444.00 | Lenovo
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
 Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
```

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 32: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 33: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-codigo | nombre
+codigo | fabricante
 1.00 | Asus
 2.00 | Lenovo
 3.00 | Hewlett-Packard
```

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 34: Correcto

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 35: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 36: Error
- **Descripción**: 'NoneType' object is not iterable

