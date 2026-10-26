# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 17 correctas de 28 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.17 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.13 ms
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

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.14 ms
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

⏱ Tiempo: 0.13 ms
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

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 21: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '.nombre, precio, f.nombre AS f.nombre FROM producto p JOIN fabricante f ON p.cod' at line 2


## ❌ Query 22: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'AS 'nombre del fabricante' ASC' at line 2


## ❌ Query 23: Error
- **Descripción**: 1052 (23000): Column 'codigo' in field list is ambiguous


## ❌ Query 24: Error
- **Descripción**: 1052 (23000): Column 'nombre' in field list is ambiguous


## ❌ Query 25: Error
- **Descripción**: 1052 (23000): Column 'nombre' in field list is ambiguous


## ❌ Query 26: Error
- **Descripción**: 1052 (23000): Column 'nombre' in field list is ambiguous


## ❌ Query 27: Error
- **Descripción**: 1052 (23000): Column 'nombre' in field list is ambiguous


## ❌ Query 28: Error
- **Descripción**: 'NoneType' object is not iterable

