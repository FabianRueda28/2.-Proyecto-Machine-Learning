# Proyecto Individual No.2 - Machine Learning 

# Mercado inmobiliario
​
Dentro de la sociedad globalizada e industrializada, es sabido que los precios de los inmuebles han presentado un constante cambio, por lo que quienes deseen invertir o vender una propiedad se enfrentan al fenómeno especulativo existente en la valorización de éstos. Esto, debido a la constante tendencia de las ciudades a crecer demográfica y comercialmente, llegando a un punto en donde no se tiene certeza de la valorización real dentro del sector en donde se desee invertir. 
​
Pese a que el precio depende, en cierta medida, de las tendencias que esté teniendo el mercado inmobiliario en un determinado tiempo, poder estimar adecuadamente el valor de una propiedad es una referencia clave para entender si es una buena oportunidad, ya sea de compra o de venta.
​
# Descripción del problema
​
Usted ha sido contactado de una importante empresa inversora dentro del rubro de la inmobiliaria en Colombia, con el fin de que implemente un modelo de clasificación que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición correspondientes al año 2020.
​
Para esto, específicamente, debe predecir la **categorización** de las propiedades entre baratas o caras, considerando como criterio el valor promedio de los precios (la media). 

# Metodología 
Se realizó el EDA (análisis exploratorio de los datos). Todo el trabajo fue realizado exclusivamente en Python. Para ello también se utilizaron librerías como Pandas, Scikit-learn, Matplotlib, Seaborn y Numpy.

El modelo elegido, en este caso, fue el de arboles de decisión y el criterio de la “entropía”. Si bien la capacidad predictiva es superada por otros algoritmos, la razón fundamental de su aplicación radicó en su sencilla implementación y fácil interpretación.

El archivo “pred.csv” es el que se utiliza para el score del modelo, tiene solamente una columna con los valores predichos y es lo que se solicita por parte de los mentores, para la comprobación del modelo.

