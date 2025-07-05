# ML_-Electronic_Music_Genres_EDA-Classifier-

(In english below)

"" Este es mi proyecto final para el Bootcamp de Data Science en The Bridge School Academy donde realicé un EDA y un modelo Clasificador de Machine Learning para géneros de música electrónica """


# PROBLEMA DE NEGOCIO
Somos un sello discográfico consolidado y reconocido por nuestra trayectoria en géneros de música tradicional (como folclore, jazz, blues y música regional). En respuesta a los cambios en el consumo musical global y el crecimiento de la música electrónica, la dirección del sello ha decidido explorar oportunidades de expansión hacia este nuevo mercado.

# Desafío estratégico:
A diferencia de los géneros tradicionales, la música electrónica presenta una estructura acústica diferente, con subgéneros menos delimitados, una producción digital más compleja, y una variedad de métricas poco conocidas para nuestro equipo curatorial. Antes de lanzar nuevas producciones o firmar artistas, necesitamos entender cómo se organiza, segmenta y comporta la música electrónica desde una perspectiva cuantitativa. 

# Objetivos del proyecto:
- Exploración del espacio sonoro de la música electrónica mediante análisis exploratorio de datos (EDA) sobre un conjunto de canciones etiquetadas por género y representadas por características acústicas extraídas (como MFCCs, entropía espectral, BPM, etc.).

- Desarrollo de un modelo de clasificación automática, que nos permita:
  - Clasificar nuevas producciones o maquetas dentro de los subgéneros electrónicos predominantes.
  - Identificar si una canción electrónica tiene una estructura compatible con la línea editorial de nuestro sello (a través de distribuciones de características acústicas similares).
  - Automatizar el análisis curatorial de demos entrantes.

<b>Buscaremos tener rendimientos que superen el 80% del F-1 Score weighted</b>

# Valor para el negocio:
Este sistema no solo acelera el proceso de exploración y filtrado de talento dentro del ámbito electrónico, sino que también reduce la incertidumbre creativa y comercial al permitirnos detectar automáticamente qué tipo de música electrónica se alinea con nuestras potenciales líneas editoriales.

# Datasets utilizados: 
'Electronic Music Features - 201611 BeatportTop100' - https://www.kaggle.com/datasets/caparrini/electronic-music-features-201611-beatporttop100<br>
'GTZAN Dataset - Music Genre Classification' - https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification


# Solución Empleada:

Un modelo de clasificación supervisado LGBMClassifier optimizado con GridSearchCV a partir de un feature engineering realizado con RFECV (Recursive feature elimination with cross-validation to select features) y técnica de Undersampling para balancear las clases objetivo.

--------------------------------------------------------------------------------------------------------------------------------------------------


English Version:

"" This is my final project for the Data Science Bootcamp at The Bridge School Academy, where I performed an EDA and built a Machine Learning classification model for electronic music genres. ""

# BUSINESS PROBLEM
We are a well-established and recognized record label known for our history in traditional music genres (such as folk, jazz, blues, and regional music). In response to changes in global music consumption and the growth of electronic music, the label’s management has decided to explore expansion opportunities into this new market.

# Strategic challenge:
Unlike traditional genres, electronic music presents a different acoustic structure, with less clearly defined subgenres, more complex digital production, and a variety of metrics that are unfamiliar to our curatorial team. Before launching new productions or signing artists, we need to understand how electronic music is organized, segmented, and behaves from a quantitative perspective.

# Project objectives:

- Explore the sound space of electronic music through exploratory data analysis (EDA) on a dataset of songs labeled by genre and represented by extracted acoustic features (such as MFCCs, spectral entropy, BPM, etc.).

- Develop an automatic classification model that allows us to:

  - Classify new productions or demos within the predominant electronic subgenres.

  - Identify whether an electronic song has a structure compatible with our label's editorial line (through distributions of similar acoustic features).

  - Automate the curatorial analysis of incoming demos.

<b>We aim to achieve performance exceeding 80% in the weighted F1 Score.</b>

# Business value:
This system not only accelerates the exploration and filtering process of talent within the electronic music domain but also reduces creative and commercial uncertainty by allowing us to automatically detect which types of electronic music align with our potential editorial lines.

# Datasets used:
'Electronic Music Features - 201611 BeatportTop100' - https://www.kaggle.com/datasets/caparrini/electronic-music-features-201611-beatporttop100<br>
'GTZAN Dataset - Music Genre Classification' - https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

# Implemented solution:
A supervised classification model using LGBMClassifier, optimized with GridSearchCV, built on feature engineering via RFECV (Recursive Feature Elimination with Cross-Validation to select features), and an undersampling technique to balance the target classes.
