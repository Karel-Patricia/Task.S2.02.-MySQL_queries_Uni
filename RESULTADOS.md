# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 23 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.49 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_profesor, PRIMARY,id_departamento

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_asignatura, id_profesor, id_departamento

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | tipo | total_creditos
+grau | tipus | total_creditos
 Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
 Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
 Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
 anyo_inicio | total
-2014.00 | 3.00
-2018.00 | 3.00
+2014.00 | 9.00
+2018.00 | 30.00
```

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_curso_escolar, PRIMARY

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY, PRIMARY,nif

---

## ❌ Query 25: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
 id | nif | nombre | apellido1 | apellido2 | ciudad | direccion | telefono | fecha_nacimiento | sexo | tipo
-4.00 | 17105885A | Pedro | Heller | Pagac | Almería | C/ Estrella fugaz | NULL | 2000-10-05 | H | alumno
+1.00 | 26902806M | Salvador | Sánchez | Pérez | Almería | C/ Real del barrio alto | 950254837 | 1991-03-28 | H | alumno
```

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---
