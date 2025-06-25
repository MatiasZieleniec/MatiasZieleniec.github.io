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
* **Documentación y código:** https://github.com/matias-ingenium/Optimizacion_del_calculo_de_estructuras_con_ML
