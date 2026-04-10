# 📊 Plan de Acción – Laboratorio 6 KNN (Avance 1–5)

## 👥 Integrantes
- Integrante A
- Integrante B
- Integrante C

---

# 🎯 Objetivo del avance
Desarrollar:
- Modelo KNN de regresión (precio)
- Evaluación del modelo
- Comparación con modelos previos
- Modelo KNN de clasificación (categoría de precio)
- Evaluación en conjunto de prueba

---

# ⚙️ Organización General

- Dataset: listings.RData   
- Condición crítica: usar el mismo split train/test de entregas anteriores  
- Lenguaje: R o Python (consistente entre todos)
- Repositorio: obligatorio con commits individuales

---

# 🧠 División de Trabajo

## 🔵 Integrante A – KNN Regresión + Predicción + Evaluación en Test (Puntos 1, parte de 2 y parte de 5)

### Tareas:
1. Cargar y preparar dataset
2. Asegurar mismo split (train/test)
3. Normalizar variables (CRÍTICO para KNN)
4. Implementar modelo KNN de regresión:
   - Selección inicial de K
5. Realizar predicciones sobre test set
6. **[Punto 5]** Evaluar el modelo de regresión sobre el conjunto de prueba:
   - Reportar RMSE, MAE, R² en test set
   - Explicar qué tan bien predice el modelo en datos no vistos
7. Documentar:
   - Cómo funciona KNN en este contexto
   - Decisiones tomadas (K, normalización, features)

### Entregables:
- Código KNN regresión
- Predicciones generadas
- Métricas del modelo en test set (RMSE, MAE, R²)
- Explicación inicial del modelo

---

## 🟢 Integrante B – Evaluación + Comparación (Puntos 2 y 3)

### Tareas:
1. Evaluar modelo de regresión KNN:
   - Métricas:
     - RMSE
     - MAE
     - R²
2. Analizar desempeño:
   - ¿Sobreestima? ¿Subestima?
   - ¿Qué tan bien predice?
3. Comparar contra:
   - Regresión lineal
   - Árbol de regresión
   - Naive Bayes
4. Asegurar:
   - Misma data de entrenamiento/prueba
   - Comparación justa

### Entregables:
- Tabla comparativa de modelos
- Gráficos (opcional pero recomendado)
- Conclusión: mejor modelo hasta ahora

---

## 🟡 Integrante C – KNN Clasificación + Evaluación (Puntos 4 y 5)

### Tareas:
1. Crear variable categórica:
   - Precio → {barata, media, cara}
   - Definir criterio (ej: terciles)
2. Implementar KNN clasificación
3. Predecir sobre test set
4. Evaluar modelo:
   - Accuracy
   - Precision / Recall (si posible)
5. Analizar resultados:
   - ¿Dónde falla más?
   - ¿Clases desbalanceadas?

### Entregables:
- Código KNN clasificación
- Variable categórica documentada
- Métricas del modelo
- Interpretación inicial

---

# 🔗 Integración Final (TODOS)

### Reunión de integración:
- Unir notebooks/scripts
- Homogeneizar:
  - formato
  - nombres de variables
  - gráficos

### Redacción conjunta:
- Introducción
- Metodología clara
- Flujo lógico (tipo consultoría)
- NO usar los enunciados como subtítulos

---

# 📅 Cronograma Sugerido

| Día | Actividad |
|-----|----------|
| Hoy | División + setup + carga datos |
| Día 1 | Modelos individuales |
| Día 2 | Evaluaciones + comparación |
| Día 3 | Integración + redacción |

---

# ⚠️ Riesgos a Evitar

- ❌ No normalizar datos → KNN falla
- ❌ Usar distinto train/test → comparación inválida
- ❌ No versionar código → pérdida de puntos
- ❌ No justificar métricas → penalización fuerte

---

# ✅ Checklist Final

- [ ] KNN regresión implementado
- [ ] Métricas correctas calculadas
- [ ] Comparación con modelos anteriores
- [ ] Variable categórica creada
- [ ] KNN clasificación evaluado
- [ ] Código versionado (mínimo 3 commits por persona)

---

# 🚀 Resultado Esperado

Un avance sólido donde:
- Ya tienen ambos modelos KNN funcionando
- Ya saben si KNN compite o no con modelos anteriores
- Base lista para:
  - matriz de confusión
  - tuning
  - validación cruzada (entrega final)

--****