# Curso de aprendizaje profundo 2021-I, IIMAS, UNAM.
Este repositorio tiene los resultados de mi asistencia a la clase de [Aprendizaje Profundo, UNAM.](http://turing.iimas.unam.mx/~gibranfp/cursos/aprendizaje_profundo/) 2021-I.

## Temario
1. Redes densas
2. Redes convolucionales
3. Redes recurrentes
4. Estrategias y trucos de entrenamiento
5. Mecanismos de atención y memoria externa
6. Modelos generativos
7. Redes generativas
8. Sesgo e imparcialidad
9. Temas selectos


## Ambiente de programación

En este caso los ejercicios son ejecutados en ambiente local

* Ambiente local: para aquellos que deseen crear correr los ejemplos en su equipo.


<!-- * Python (>= 3.6)
* [Tensorflow 2](https://www.tensorflow.org/), que adopta [Keras](https://www.tensorflow.org/versions/r2.0/api_docs/python/tf/keras) como interfaz de alto nivel para construir y entrenar redes neuronales.
* [Tensorflow Probability](https://www.tensorflow.org/probability/)
* [Tensorboard](https://www.tensorflow.org/tensorboard/)
* [Tensorflow Hub](https://www.tensorflow.org/hub/)
* [scikit-learn 0.21.3](https://scikit-learn.org/)
* [matplotlib 3.1.1](https://matplotlib.org/)
* [seaborn 0.9.0](https://seaborn.pydata.org/)

Puedes usar [Google Colab](https://colab.research.google.com) o crear un ambiente local en tu computadora usando [Anaconda](https://www.anaconda.com/). -->


### Ambiente local

Para instalar el ambiente en nuestra computadora primero debemos instalar Anaconda siguiendo las [instrucciones](https://docs.anaconda.com/anaconda/install/) oficiales. Después, creamos el ambiente con el archivo de dependencias:

```
conda env create --f environment.yml
```

Adicionalmente he instalado librerias como numba y cupy para probar aceleracion de procesamiento en operaciones crudas.

Enseguida, activamos el ambiente:

```
conda activate cap
```

Posteriormente, para comenzar a trabajar con las libretas lanzamos Jupyter Notebooks:

```
jupyter notebook
```

Este comando abrirá una pestaña o ventana en tu navegador web, como se muestra en la siguiente captura de pantalla:

![](figs/jupyter_notebook.png)

Aquí puedes crear una nueva libreta seleccionando el botón `New` y posteriormente `Python 3`. También puedes cargar uno existente seleccionando un archivo con extensión `.ipynb` dentro del directorio donde se lanzó el comando. Con `Upload` agregas archivos que se encuentran en otra parte de tu computadora a este directorio. Para salir, simplemente presiona el botón `Quit` y cierra la pestaña o ventada correspondiente.

Para desactivar el ambiente

```
conda deactivate
```
