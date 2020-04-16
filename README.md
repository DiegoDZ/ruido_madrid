# Análisis del ruido en Madrid


Este notebook presenta un análisis del índice de ruido $$LAeq^i$$ en la ciudad de Madrid para los años 2015-2019,ambos incluidos, y el año 2020 hasta el mes de mayo. 

1. En la primera parte se presentan una comparativa de las 31 estaciones presentes en la capital. Observaremos cómo el ruido es estacional en prácticamente todas ellas, las ordenaremos de acuerdo al ruido medio diario que registran y veremos, mediante un gráfico de violín, las desviaciones de todos los registros con respecto a la media diaria para cada una de las estaciones. 

2. En la segunda parte, compararemos la evolución de la media mensual del índice $$LAeq$$ para las distintas estaciones, permitiéndonos observar un claro descenso en el año 2020 debido a las medidas de aislamiento establecidas por la crisis de la pandemia COVID-19. Posteriormente, descenderemos a una escala diaria para analizar en detalle el efecto de las distintas etapas del aislamiento sobre el ruido registrado en las estaciones de Madrid. 


(i) El índice de ruido $$LAeq$$ es el parámetro acústico aceptado internacionalmente como medida del nivel sonoro continuo equivalente. Este índice representa la contaminación acústica acumulada a lo largo de un periodo de tiempo en el lugar de medición. Puesto que el oído humano es más sensible a las medias frecuencias, se realiza una ponderación de frecuencias, dando menos importancia a las bajas y altas frecuencias frente a las medias, con el fin de establecer una medida del nivel de ruido que soporta el ser humano cercano a la estación de medición. 

-----------

Análisis realizado por [@ClaudiaGEscribano](https://github.com/ClaudiaGEscribano) y [@ddzumajo](https://github.com/ddzumajo)


Los datos han sido obtenidos del [Portal de datos abiertos del Ayuntamiento de Madrid](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=2ec892874870b410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default).




