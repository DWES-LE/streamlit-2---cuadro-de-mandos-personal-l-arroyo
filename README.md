# 馃搱 Cuadro de mandos personal 馃搳
 
> Usa este repositorio para crear un cuadro de mandos personal con Streamlit. Documenta los siguientes apartados del README.
> Incluye en tu README la url de donde has publicado tu aplicaci贸n. Pon la `url` tambi茅n en el `About` de tu repositorio.

## Objetivo
Dise帽o de un cuadro de mandos personal para visualizaci贸n e interacci贸n con un conjunto de datos.

## Los datos
He escogido hacer un test con los datos del videojuego Animal Crossing: New Horizons. En concreto, he escogido los datos de los vecinos que puedes tener, sus gustos, mes de nacimiento y sus personalidades.

## B煤squeda de los datos
Los datos han sido extra铆dos de [esta p谩gina](https://www.kaggle.com/datasets/jessicali9530/animal-crossing-new-horizons-nookplaza-dataset?select=villagers.csv), y he hecho un scrapping de [este datasheet](https://nookipedia.com/wiki/Community:ACNH_Spreadsheet) para a帽adir los links de las im谩genes de cada vecino (el script puede verse en [scrapping.py](./scrapping.py)).

## Documentaci贸n de los datos
Los datos est谩n en formato csv, y he hecho uso de las siguientes columnas: 
 - `name`: nombre del vecino
 - `personality`: personalidad del vecino
 - `birthday`: fecha de nacimiento del vecino
 - `hobby`: hobbies del vecino
 - `image`: link de la imagen del vecino que he extra铆do del scrapping

## Aplicaci贸n y dependencias.
La aplicaci贸n se llama `app.py`. Y las dependencias est谩n registradas en el fichero `requirements.txt`.

## Prepara la aplicaci贸n (cuadro de mandos) con Streamlit
Prepara y prueba la aplicaci贸n.

## Publica la aplicaci贸n.
Publica la aplicaci贸n en Streamlit Cloud, en Heroku o en el servicio que prefieras https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app
