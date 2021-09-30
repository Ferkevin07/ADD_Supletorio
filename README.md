# ADD_Supletorio
1.- Transportar datos mediante scripts desde una base de datos relacional hasta MongoDB, en cada extremo del flujo de datos debe ser un usuario validado (login y password) 

2.- Crear un script que inserte n documentos con elementos al azar en CouchDB, donde uno de los campos debe ser un número. Sobre esta base de datos, crear una vista que emita mediante "curl" un json con los elementos en orden descendente.

# 3.- Crear un modelo descriptivo mediante RapidMiner o Knime, sobre el dataset del titanic, respondiento a las preguntas:

Se hizo este modelo en RapidMiner para el modelo descriptivo de Titanic, aqui se uso el dataset Training que proporciona la herramienta, junto a un bloque Set Role para asignar prioridad a la columna "Survived" y por ultimo se aplico el algoritmo "Deep Learning" para resultados más precisos

![img01](https://user-images.githubusercontent.com/66317435/135542368-42316346-74fc-4647-b5e4-e41ed7a276e6.jpeg)

Esta es la tabla resultante de la aplicacion del modelo anterior

![img02](https://user-images.githubusercontent.com/66317435/135542401-d7b157f6-6ff4-46ca-869e-a2a5316ad18e.jpeg)

¿Qué genero es el que más falleció?

El genero que mas sobrevivo es el de las mujeres como lo muestra la siguiente grafica de barras

![img03](https://user-images.githubusercontent.com/66317435/135542413-1339cb43-0d98-4d11-a4f9-d1fc86621c7d.jpeg)

¿Qué rangos de edad fueron los que sobrevivieron?

Los rangos de edad que más sobrevivieron fue entre 16 y 32 años

![img04](https://user-images.githubusercontent.com/66317435/135542438-e6999abb-c7ba-47db-a306-11fdb87d365c.jpeg)

¿Qué rangos de precio pagaron los ticket tripulantes que sobrevivieron?

Los tripulantes que sobrevivieron pagaron el precio de su ticket entre 0 a 150 aproximadamente, siendo los de mayor frecuencia aquellas personas que pagaron de 0 a 51

![img05](https://user-images.githubusercontent.com/66317435/135542462-3df41ad1-5a2d-4abb-90ec-883c85c7dd63.jpeg)

# 4.- Crear un modelo predictivo mediante RapidMiner o Knime, sobre el dataset del titanic, indique 3 conclusiones.

Se creo un dataset aparte para ilustrar de mejor manera el modelo predicitvo. Esto se hizo mediante un excel

![img06](https://user-images.githubusercontent.com/66317435/135542594-0d9b54e7-3a2a-47ca-999b-c91c7430a7a2.jpeg)

Al importar los datos hacia un lector de excel de RapidMiner se asigna la columna "Survivied" como "label"

![img07](https://user-images.githubusercontent.com/66317435/135542620-e040662b-36f7-470e-97cc-82d255cbdc30.jpeg)

Se obtiene la siguiente estructura para generar el modelo predictivo

![img08](https://user-images.githubusercontent.com/66317435/135542665-8e3b9e6c-7d11-49ca-8952-6bc563793aa8.jpeg)

Aqui se presenta la tabla generada del modelo anterior

![img09](https://user-images.githubusercontent.com/66317435/135542782-43cea5ce-c16d-4457-912b-faac6f2a5780.jpeg)

La primera conclusion es que las personas de Segunda clase tienen mayor probabilidad de sobrevivir

![img10](https://user-images.githubusercontent.com/66317435/135542949-eccaa6e5-a3ef-43f1-8678-d053a49d58f8.jpeg)

Otra conclusion es que las mujeres tienen mucho mas posibilidades de sobrevivir que los hombres

![img11](https://user-images.githubusercontent.com/66317435/135543156-91371af2-8002-4645-b3e2-13ab45663fa1.jpeg)

Una ultima conclusion es que las personas que tenian mas de 1 hermano o esposa abordo, tenian menos probabilidades de sobrevivir

![img12](https://user-images.githubusercontent.com/66317435/135543338-d0ace9d8-9821-4544-9989-3a7062245ee2.jpeg)

# 5.- Cree un dashboard sobre un dataset de COVID-19 con al menos 5 visualizaciones con sus respectivas conclusiones. Puede usar, Tableau, PowerBI o Kibana.

El dataset a usar para las visualizaciones se tomo de Kaggle

![img13](https://user-images.githubusercontent.com/66317435/135544191-dd3c3206-7eb4-464c-ae85-fb326c312a6c.jpeg)

Para trabajar con PowerBi es necesario transformar el archivos CSV a XLS

![img14](https://user-images.githubusercontent.com/66317435/135544207-890bdb3f-eaca-4465-b75a-35986d697357.jpeg)

Archivo transformado y listo para ser importado

![img15](https://user-images.githubusercontent.com/66317435/135544223-8dcd0bb0-cf70-4b1b-b31c-cb6b0a38f7bd.jpeg)

Visualizacion previa de los datos en PowerBi

![img16](https://user-images.githubusercontent.com/66317435/135544253-24e346fd-e730-4bb2-b937-3ed9f7ccfd0c.jpeg)

A partir del dataset anterior se obtuvo las siguientes visualizaciones

![img17](https://user-images.githubusercontent.com/66317435/135544274-6300b56c-13b8-4a4d-a66d-b03f1e0c20b6.jpeg)

En el caso de la visualizacion geografica (expandida) se puede concluir que la mayor cantidad de contagios se da en Asia

![img18](https://user-images.githubusercontent.com/66317435/135544297-7968d5b8-3c93-42ab-918a-fa71d244f529.jpeg)

Por otro lado, la mayor cantidad de repuntes del grafico de pastel (expandido) se da principalmente en America y en el Sureste de Asia

![img19](https://user-images.githubusercontent.com/66317435/135544315-52dbbb95-a78c-4ad3-a618-e9614a7ebefa.jpeg)

Además, en la graficas de barras horizontales se tiene que la mayor cantidad de muertes por país se da en Estados Unidos, seguido por Brasil y Reino Unido

![img20](https://user-images.githubusercontent.com/66317435/135544332-67f0e0a9-935e-4e49-b87b-7a21ec09f9ff.jpeg)

Con respecto al incremento de casos de la última semana de Agosto se tiene que disminuye de manera exponencial en países como Las Bahamas, Suriname, Costa Rica, etc.

![img21](https://user-images.githubusercontent.com/66317435/135544343-ce97e043-e371-490e-8dad-f6fbb4e5c5e0.jpeg)

Y de manera mundial se tiene que los casos de Covid-19 han incrementado la ultima semana en 245 mil

![img22](https://user-images.githubusercontent.com/66317435/135544367-3407f516-66b5-4869-b049-b0424b755d03.jpeg)




