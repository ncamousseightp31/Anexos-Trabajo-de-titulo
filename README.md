# Anexos-Trabajo-de-titulo-Excel

# Resultados de Simulación: Red SEN Académico 📊

En esta rama (`tablas-excel`) se almacenan los resultados exportados de las simulaciones realizadas sobre el modelo de la Red del Sistema Eléctrico Nacional (SEN). Los datos se encuentran en formato Excel y están categorizados según el tipo de evento, el tipo de simulación y los KPIs evaluados.

## 📌 Nomenclatura de Archivos

Para facilitar la búsqueda de resultados, los archivos siguen una lógica de numeración en su prefijo:

* **Identificador de Evento y Simulación (Primer dígito):**
    * `1.x`: Variación de Carga (Simulación EMT)
    * `2.x`: Variación de Carga (Simulación RMS)
    * `3.x`: Cortocircuito (Simulación EMT)
    * `4.x`: Cortocircuito (Simulación RMS)
    * `5.x`: Sobreinstalación (Simulación EMT)
* **Identificador de KPIs (Segundo dígito):**
    * `x.1`: Contiene los KPIs de **Tensión y Frecuencia**.
    * `x.2`: Contiene los KPIs de **Corriente**.

---

## 📂 Directorio de Archivos

A continuación se detalla el contenido de cada planilla Excel disponible en esta rama:

| Prefijo | Evento Simulado | Tipo de Simulación | Variables / KPIs | Nombre Completo del Archivo |
| :---: | :--- | :---: | :--- | :--- |
| **1.1** | Variación de Carga | **EMT** | Tensión y Frecuencia | `1.1-Red SEN Academico-Evento de Variacion de Carga-KPI de Tension y Frecuencia-Resultados por escenarios-EMT` |
| **1.2** | Variación de Carga | **EMT** | Corriente | `1.2-Red SEN Academico-Evento de Variacion de Carga-KPI de Corriente-Resultados por escenarios-EMT` |
| **2.1** | Variación de Carga | **RMS** | Tensión y Frecuencia | `2.1-Red SEN Academico-Evento de Variacion de Carga-KPI de Tension y Frecuencia-Resultados por escenarios-RMS` |
| **2.2** | Variación de Carga | **RMS** | Corriente | `2.2-Red SEN Academico-Evento de Variacion de Carga-KPI de Corriente-Resultados por escenarios-RMS` |
| **3.1** | Cortocircuito | **EMT** | Tensión y Frecuencia | `3.1-Red SEN Academico-Evento de Cortocircuito-KPI de Tension y Frecuencia-Resultados por escenarios-EMT` |
| **3.2** | Cortocircuito | **EMT** | Corriente | `3.2-Red SEN Academico-Evento de Cortocircuito-KPI de Corriente-Resultados por escenarios-EMT` |
| **4.1** | Cortocircuito | **RMS** | Tensión y Frecuencia | `4.1-Red SEN Academico-Evento de Cortocircuito-KPI de Tension y Frecuencia-Resultados por escenarios-RMS` |
| **4.2** | Cortocircuito | **RMS** | Corriente | `4.2-Red SEN Academico-Evento de Cortocircuito-KPI de Corriente-Resultados por escenarios-RMS` |
| **5.1** | Sobreinstalación | **EMT** | Tensión y Frecuencia | `5.1-Red SEN Academico-Evento de sobreinstalacion-KPI de Tension y Frecuencia-Resultados por escenarios-EMT` |
| **5.2** | Sobreinstalación | **EMT** | Corriente | `5.2-Red SEN Academico-Evento de sobreinstalacion-KPI de Corriente-Resultados por escenarios-EMT` |

> **Nota:** Todos los resultados están organizados por escenarios dentro de cada archivo Excel.
