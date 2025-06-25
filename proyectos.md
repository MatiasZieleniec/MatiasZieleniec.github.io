# Proyectos

---

### Proyecto 1: Optimización del Cálculo de Estructuras mediante Modelos de Oredn Reducido y Aprendizaje Automático No Intrusivo

**Descripción:** Esta investigación se centra en la optimización temporal del cálculo de estructuras mediante el método de los elementos finitos (FEM). 
Se aborda el problema del alto costo computacional de las simulaciones de alta fidelidad, especialmente en análisis paramétricos , empleando Métodos de Orden Reducido (ROM) no intrusivos. 
Estos métodos son ventajosos, ya que no requieren acceso a las ecuaciones diferenciales gobernantes, sino únicamente a las soluciones (snapshots) generadas por softwares comerciales. 
Se proponen y evalúan dos enfoques basados en aprendizaje automático. El primer método utiliza una red neuronal para predecir los coeficientes de una base reducida, obtenida mediante Descomposición Ortogonal Propia (POD), que aproxima la solución del sistema. 
El segundo enfoque se centra en predecir la inversa de la matriz de rigidez reducida utilizando métodos de ensamble basados en árboles (Random Forest y Gradient Boosting). 
Se presentan resultados para dos casos de estudio: un bloque elástico y una losa de Kirchhoff-Love, evaluando la efectividad y precisión de cada metodología. 
Los hallazgos indican que ambos enfoques son prometedores, aunque su precisión varía según la complejidad del problema estructural y el método de aprendizaje automático empleado.

* **Empresa:** Ingenium
* **Supervisor Académico:** Franz Chouly
* **Supervisor Industrial:** Francisco Pons
* **Tecnologías:** Python, FEniCS (software para MEF), RBniCs (software para ROM), UQpy, Scikit-learn, Pytorch, LightGBM
* **Documentación y código:** [Ver en GitHub](https://github.com/matias-ingenium/Optimizacion_del_calculo_de_estructuras_con_ML)


### Proyecto 2: Desarrollo de un Agente Inteligente para Interacción Autónoma en X (Twitter)

**Descripción:** Este proyecto consistió en la creación de un bot completamente funcional para la plataforma X, capaz de ir más allá de respuestas predefinidas. El bot escucha activamente las menciones, utiliza un modelo de lenguaje avanzado (LLM) a través de la API de OpenAI para entender la intención y el sentimiento del tuit original, y elabora respuestas contextualmente relevantes. Se utilizó la API de Google Sheets como una solución de bajo costo y fácil acceso para el monitoreo y registro de la actividad del bot.

* **Supervisor:** Ariel Ehrlijman
* **Habilidades Demostradas:** Orquestación de múltiples servicios web (APIs), aplicación práctica de modelos de IA, manejo de flujos de datos en tiempo real y automatización de tareas.
* **Stack Tecnológico:** Python, Tweepy, OpenAI API, Google Sheets API.


### Proyecto 3: Análisis Estadístico del Coleccionismo, Un Modelo de Simulación para el Álbum del Mundial

**Descripción:** Este proyecto explora la fascinante matemática detrás de coleccionar el álbum del mundial. A través de una simulación, se construyó un modelo predictivo que no solo valida los resultados teóricos del clásico "problema del coleccionista de cupones", sino que también introduce capas de complejidad social y económica. Se investigó cómo la creación de una red de coleccionistas para el intercambio de duplicados reduce de manera significativa el costo y tiempo para finalizar el álbum. Además, se modeló un escenario con figuritas de diferente valor percibido, analizando cómo este factor altera el comportamiento y las estrategias de los coleccionistas.

* **Coautor:** Mauricio Conde
* **Habilidades Demostradas:** Fuerte capacidad para traducir un problema del mundo real a un modelo matemático y computacional, análisis estadístico de resultados de simulación y visualización de datos para comunicar conclusiones complejas de forma efectiva.
* **Stack Tecnológico:** Python, NumPy, Matplotlib.
