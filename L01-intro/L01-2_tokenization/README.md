# Tokenización

Los tokens son componentes textuales independientes y mínimos que tienen alguna sintaxis o semántica definida.

La tokenización puede ser definida como el proceso de separa datos textuales en pequeños componentes con significado llamados tokens.

## Tokenización de oraciones

La **tokenización de oraciones** es el proceso de separar un [[corpus de texto]] en sentencias que actúan como el primer nivel de tokens que componen el corpus. 

Existen varias formas de realizar la tokenización de sentencias. Las técnicas básicas incluyen buscar delimitares específicos entre sentencias, como el punto y aparte (**.**) o un caracter de nueva linea (\n), y algunos otras veces punto y coma (;). 

[Ejemplo 1. Tokenización de oraciones](./code/tokenization_nltk.ipynb)

## Tokenización de palabras

La **tokenización de palabras** es el proceso de separar o sementar oraciones en las palabras que la conforman. Una oración es una colección de palabras, y con la tokenización se obtiene una lista de palabras a partir de la oración que pueden ser utilizadas para reconstruir la oración. 

La tokenización de palabras es importante en muchos procesos, especialmente en la limpieza y normalización de los textos donde operaciones como stemming o lematización se aplica sobre cada palabra basado en sus respectivos stems (raíces) o lemas.

[Ejemplo 2. Tokenización de palabras](./code/tokenization_words.nltk.ipynb)