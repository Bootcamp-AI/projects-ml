# Contenido: aprendizaje no supervisado
## Proyecto: Creación de segmentos de clientes

### Instalar

Este proyecto requiere ** Python 2.7 ** y las siguientes bibliotecas de Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

También necesitará tener un software instalado para ejecutar y ejecutar [Jupyter Notebook](http://jupyter.org/index.html)


Si aún no tiene Python instalado, se recomienda encarecidamente que instale la distribución [Anaconda] (http://continuum.io/downloads) de Python, que ya tiene los paquetes anteriores y más incluidos. Asegúrese de seleccionar el instalador de Python 2.7 y no el instalador de Python 3.x.


### Code

El código de la plantilla se proporciona en el archivo de cuaderno `customer_segments.ipynb`. También deberá utilizar el archivo Python `visuals.py` incluido y el archivo de conjunto de datos` customers.csv` para completar su trabajo. Si bien ya se ha implementado algún código para comenzar, deberá implementar una funcionalidad adicional cuando se le solicite para completar con éxito el proyecto. Tenga en cuenta que el código incluido en `visuals.py` está diseñado para usarse de inmediato y no para que los estudiantes lo manipulen. Si está interesado en cómo se crean las visualizaciones en el cuaderno, no dude en explorar este archivo de Python.



### Run

En una terminal o ventana de comandos, navegue hasta el directorio de proyecto de nivel superior `customer_segments /` (que contiene este archivo README) y ejecute uno de los siguientes comandos:

```bash
ipython notebook customer_segments.ipynb
```  
or
```bash
jupyter notebook customer_segments.ipynb
```

Esto abrirá el software Jupyter Notebook y el archivo de proyecto en su navegador.


## Data

Los datos de los segmentos de clientes se incluyen como una selección de 440 puntos de datos recopilados a partir de los datos encontrados de los clientes de un distribuidor mayorista en Lisboa, Portugal. Puede encontrar más información en el [Repositorio de aprendizaje automático de UCI] (https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Nota (m.u.) es una abreviatura de * unidades monetarias *.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal) 

