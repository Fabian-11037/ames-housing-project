# Project_Modelos_Lineales

## Instrucciones para compilar el Jupyter-book
### Paso 1: Instalación de Jupyter-book y librerías a utilizar

Para compilar el libro, es necesario instalar Jupyter-book usando pip. La versión de jupyter-book a usar puede encontrarse en el archivo requirement.txt.

Puede instalar todos los paquetes requeridos utilizando el siguiente comando en una consola de texto.:

```pip install -r ../requirements.txt```

### Paso 2: Inicializar el Jupyter-Book

Tras instalar Jupyter-book, inicializar un libro con el comando:

```jupyter-book create .```

Tras lo cual, se debe agregar los capítulos en book/_toc.yml.


### Paso 3: Compilar el libro

Una vez agregado los capítulos, compilar el libro usando el comando:

```jupyter-book build .```

Verificar que no haya errores. El resultado estará en _build/html/.

### Paso 4: Publicar en GitHub Pages

Use el siguiente comando para publicar el libro en GitHub Pages:

```ghp-import -n -p -f _build/html```

Es necesario tener un repositorio activo en la carpeta del libro. Se creará un nuevo branch con los archivos necesario para la visualización del libro.


## Descargar datos

Puede encontrar los datos del dataset Ames Housing en:

https://www.kaggle.com/datasets/prevek18/ames-housing-dataset

Adicionalmente, puede descargarlo también usando la API de Kaggle:

```kaggle datasets download -d prevek18/ames-housing-dataset```

## Estructura del libro

El libro contiene los siguientes notebooks:

root: README.md
chapters:
  - file: Notebooks/00-instructions
  - file: Notebooks/01-introduction
  - file: Notebooks/02-data-cleaning
  - file: Notebooks/03-eda
  - file: Notebooks/04-ols-matrix
  - file: Notebooks/05-inference
  - file: Notebooks/06-diagnostics
  - file: Notebooks/07-robust-methods
  - file: Notebooks/08-validation
  - file: Notebooks/09-interpretation
  - file: Notebooks/10-conclusions