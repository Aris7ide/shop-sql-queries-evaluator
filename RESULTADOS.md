# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 14 correctas de 22 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio truncado
-Disco duro SATA3 1TB | 86.00
-Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.00
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.00
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.00
-Impresora HP Laserjet Pro M26nw | 180.00
+precio_truncado
+86.00
+120.00
+150.00
+185.00
+755.00
+202.00
+245.00
+559.00
+444.00
+59.00
+180.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.34 ms
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

⏱ Tiempo: 0.27 ms
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

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Error
- **Descripción**: 1146 (42S02): Table 'tienda.product' doesn't exist


## ❌ Query 19: Error
- **Descripción**: 1146 (42S02): Table 'tienda.product' doesn't exist


## ❌ Query 20: Error
- **Descripción**: 1146 (42S02): Table 'tienda.product' doesn't exist


## ❌ Query 21: Error
- **Descripción**: 1146 (42S02): Table 'tienda.product' doesn't exist


## ❌ Query 22: Error
- **Descripción**: 'NoneType' object is not iterable

