# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 0 correctas de 2 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre
-Disco duro SATA3 1TB
-Memoria RAM DDR4 8GB
-Disco SSD 1 TB
-GeForce GTX 1050Ti
-GeForce GTX 1080 Xtreme
-Monitor 24 LED Full HD
-Monitor 27 LED Full HD
-Portátil Yoga 520
-Portátil Ideapd 320
-Impresora HP Deskjet 3720
-Impresora HP Laserjet Pro M26nw
+codigo | nombre | precio | codigo_fabricante
+1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
+2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
+3.00 | Disco SSD 1 TB | 150.99 | 4.00
+4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
+6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
+7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
+11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
```

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 2: Error
- **Descripción**: 'NoneType' object is not iterable

