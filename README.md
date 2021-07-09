# MachineLearning
Machine learning studies &amp; investigation

En este estudio se quiere analizar un experimento relacionado con la predición del diagnóstico de 4 tipos de cáncer y de pacientes sanos mediante técnicas de microarrays.
El objetivo es implementar una red neuronal artificial y el support vector machine para predecir los cinco tipos de diagnóstico.
Como el algoritmo de red neuronal artificial es muy costoso si el número de variables es alto, se opta por realizar un análisis de componentes principales para reducir la dimensión de las variables iniciales y usar solo las 10 primeras en
el algoritmo, en cambio, con algoritmo support vector machine admite un número muy elevado de variables sin un incremento sustancial en su coste computacional. Por tanto, se puede utilizar los datos originales.


Las características de los diferentes tipos son:
1) Acute Lymphoblastic Leukemia (ALL). Subtype: c-ALL / pre-B-ALL without t(9;22)
2) Acute Myeloid Leukemia (AML). Subtype: Normal karyotype
3) Chronic Lymphocytic Leukemia (CLL)
4) Chronic Myeloid Leukemia (CML)
5) Non-leukemia and healthy bone marrow (NoL)
