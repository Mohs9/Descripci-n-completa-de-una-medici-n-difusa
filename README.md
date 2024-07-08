# Descripción-completa-de-una-medición-difusa
En este programa se busca exhibir el mapa de probabilidades y el estado resultante luego de la medición, a partir de un estado inicial y un observable  dado en un sistema de varias partículas.

Para ejecutar las rutinas principales de manera adecuada del programa, en primer lugar, se debe brindar el número de partículas con las que se desea trabajar en la variable N. Luego, el observable de forma matricial. Si el observable es factorizable se deben brindar cada uno de los operadores que lo conforman. Asimismo el estado inicial debe  proporcionarse en forma matricial, si este factorizable se debe dar cada uno de los factores que lo conforman.

Posteriormente, para obtener el mapeo de probabilidades debe ejecutarse la rutina "mapeo_fm(salidas,estado,probabilidades )", el cual necesita la lista que contenga las salidas de cada uno de la medición de los observables y la lista que contenga las probabilidades de intercambio. Para obtener el estado posterior a la medición se debe ejecutar la función "estado_final(salidas, probabilidades)".

Adicionalmente es posible graficar la distribución de probabilidad, con la función de mostrar_graficas(1,1).
