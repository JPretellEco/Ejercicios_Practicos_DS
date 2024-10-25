![BANNER GIT](https://github.com/user-attachments/assets/36b9346b-df80-4973-8b59-c9dfedb1e3ef)

# DSJefferssonPretell
MI camino a desarrollador como científico de datos:
![Static Badge](https://img.shields.io/badge/:badgeContent?style=flat&logo=github&logoColor=red)

---

# 🚗🔮 **Predicción de Siniestros en Seguros: Un Caso Empresarial **

### **Descripción del Proyecto**
Bienvenidos a un desafío clave que enfrenta una gran aseguradora: **predecir siniestros** antes de que ocurran. Imagina que eres un científico de datos en el equipo de esta aseguradora y tienes la misión de identificar a los clientes más propensos a tener siniestros. ¿El objetivo? Optimizar la **gestión de riesgos**, mejorar la **suscripción de pólizas** y ajustar los **precios de las primas** de forma más precisa.

### **Contexto:**
La empresa ha venido enfrentando grandes pérdidas por no detectar a tiempo qué clientes están en alto riesgo de tener siniestros. Además, algunos clientes de bajo riesgo están recibiendo tarifas más altas de lo necesario, lo que afecta la retención. Ahora, tu misión como **Data Scientist** es construir un modelo que prediga si un cliente tendrá un siniestro basado en su historial y otros factores.

### **Variables Clave del Dataset:**

- `CLIENTE_ID`: Identificador único del cliente.
- `Antiguedad_Máxima`: Los años que el cliente ha estado asegurado.
- `Nivel_Ingresos`: Clasificación de ingresos (0 = bajo, 5 = alto).
- `Saldo_Pendiente`: Monto de la deuda pendiente del cliente.
- `Puntaje_Morosidad`: Tasa de morosidad del cliente (0 = no moroso, 6 = muy moroso).
- `Saldo_Pendiente_Seg`: Monto pendiente de la póliza de seguro.
- `Siniestros`: Número de siniestros que el cliente ha tenido en su historial.
- `Estado_Siniestro`: **Variable objetivo**: 0 = No siniestro, 1 = Siniestro.

### **El Desafío:**
Tu reto es predecir el valor de `Estado_Siniestro` (0 o 1) para cada cliente en base a las otras variables del dataset. Este modelo será clave para:

1. **Optimizar las tarifas**: Evita que clientes de bajo riesgo paguen de más y ajusta las primas para los clientes de mayor riesgo.
2. **Reducir pérdidas**: Detecta a tiempo a los clientes que podrían presentar siniestros y actúa preventivamente.
3. **Mejorar la fidelización**: Identifica a los mejores clientes y ofréceles incentivos antes de que se vayan.

### **Metodología:**

1. 📊 **Análisis Exploratorio (EDA)**:
   - Exploración profunda de los datos para entender las relaciones clave. ¿Los clientes con mayor morosidad tienen más siniestros? ¿Los que llevan más tiempo asegurados son más o menos riesgosos?

2. 🛠 **Ingeniería de Características**:
   - Crear nuevas variables, como la proporción `Saldo_Pendiente / Nivel_Ingresos` o la frecuencia de siniestros por año (`Siniestros / Antiguedad_Máxima`).

3. 🧠 **Modelado Predictivo**:
   - Entrenar varios modelos de clasificación binaria (ej. **Random Forest, XGBoost, Regresión Logística**) para predecir `Estado_Siniestro`.

4. 🎯 **Optimización del Modelo**:
   - Ajustar los hiperparámetros y usar **validación cruzada** para garantizar un rendimiento robusto. Si el dataset es desbalanceado, implementamos **SMOTE** o técnicas de balanceo.

5. 🚀 **Despliegue del Modelo**:
   - Listo para producción: Integraremos el modelo con las operaciones de la aseguradora para tomar decisiones en tiempo real sobre los siniestros.

6. 🔄 **Monitoreo y Mejora Continua**:
   - Monitoreo del rendimiento del modelo en producción y ajuste continuo según los nuevos datos y patrones emergentes.

### **Resultados Esperados**:
- 📉 **Reducción de siniestros no anticipados**: Ahorros significativos para la aseguradora.
- 💸 **Tarifas más justas**: Mejores precios para clientes de bajo riesgo, lo que mejora la retención.
- 🎯 **Gestión de riesgos mejorada**: Identificación temprana de clientes problemáticos para mitigar riesgos.

---

¡Este proyecto es un gran ejemplo de cómo la **ciencia de datos** puede transformar decisiones empresariales críticas en el sector de seguros! 🚀


<h1> PRETELL </h1>
