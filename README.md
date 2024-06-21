# AluraFlix
AluraFlix es una aplicación realizada con tecnología <strong>React.js</strong>. Aún no está del todo terminada, tengo pensado agregarle otras páginas en las cuales se pueda ver los videos junto con la descripción de los mismos y agregar la página en inglés.

En la página principal (HOME) hay un listado de videos dividido en 3 categorías: "Front End", "Back End" e "Innovación y gestión", la aplicación reconoce en cuál categoría debe estar el video y lo coloca automáticamente en la categoría correspondiente. Para obtener los videos se consume API, creada en

https://mockapi.io

En la página para crear nuevos videos (NUEVO VIDEO), hay un formulario donde se coloca todos los datos y crea una nueva tarjeta en la categría correspondiente, además de agregar los datos en la API.

Dentro de cada tarjeta, de la página principal, hay dos botones uno "Borrar" el cual borra el video de la base de datos (fake API) y otro "Editar" el cual abre un Modal que contiene un formulario con todos los datos correspondientes al video seleccionado, puede editarse la información y enviará los cambios a nuestra base de datos.

<h1>Métodos HTTP que utiliza esta aplicación React.js</h1>

- <strong>Get:</strong> Se solicitan los datos de nuestra fake API para mostrar los videos en forma de tarjetas en HOME.
- <strong>Post:</strong> Mediante la página NUEVO VIDEO se crean datos que se guardan en nuestra API.
- <strong>Put:</strong> El Modal permite realizar cambios a los datos de los videos, los cuales son guardados en nuestra API.
- <strong>Delete:</strong> Mediante el botón borrar de cada tarjeta, el video seleccionado se borrará de nuestra API.

# AluraFlix
AluraFlix is an app made with <strong>React.js</strong> tecnology. It is not finished yet, I want to add other pages where we can watch the videos and see their description, also I want to add a button for an english version of the app.

In the HOME page the videos are listed and divided into 3 categories: "Front End", "Back End" and "Managment and innovation", the app recognices in which category the video should be and it automatically puts it in the corresponding category. To get the videos API consumption is needed, I created an API with

https://mockapi.io

In the NEW VIDEO page, there is a form that can be filled with the data of a new video and it creates a new card in the corresponding category and adds that data into the API.

In the HOME page, each card, has two buttons, one "Erase" which erases the video data from the database (fake API) and another "Edit" which opens a Modal that has a form that is already filled with the corresponding data of the selected video, the data can be edited and it will send the changes to our databese.

<h1>HTTP methods that are used by the React.js app</h1>

- <strong>Get:</strong> The data is solicited from our fake API to be shown as cards in the HOME page.
- <strong>Post:</strong> On the NEW VIDEO page we can create data that is saved in our API.
- <strong>Put:</strong> The Modal let us change the videos data, which is saved in our API.
- <strong>Delete:</strong> Each card's erase button, deletes the selected video from our API.
