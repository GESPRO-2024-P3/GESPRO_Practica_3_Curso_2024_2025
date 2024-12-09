Nombre de los miembros: Daniel Bedoya Romero, Sergio Gómez Gónzalez e Íñigo Velasco Gómez-


INDICE
1. Guia Secuencia de Acciones.
1.1 Guia mediante Capturas.
2.1 Grafico de la lista de Commits del Repositorio.
2.2 Captura Primer Commit.
2.3 Captura Ultimo Commit.
3.1 Informacion del Proyecto de Github obtenida desde el menu “Insights-Pulse”
3.2 Informacion del Proyecto de Github obtenida desde el menu “Insights-CodeFrequency”.
3.3 Relacion de las PRQs realizadas Cerradas.

1. Guia Secuencia de Acciones.

Abre GitKraken y posiciónate en el commit desde donde quieres comenzar a trabajar dentro de la rama GO BEES. Cambia a la rama master y haz un fetch para traer los últimos cambios del repositorio remoto: en GitKraken, utiliza la opción Fetch all. Si hay actualizaciones en master, haz un pull para integrarlas en tu copia local. Crea una nueva rama en github a partir de master que corresponda al trabajo de la tarea: nómbrala igual que en GoBees.

Posiciónate en esta nueva rama en GitKraken de manera local para comenzar a trabajar. Añade los archivos modificados de la carpeta de GO BEES a la carpeta donde esté tu trabajo en local (En nuestro caso, P3). Añade todo, excluyendo el archivo .git. 

Vuelve a GitKraken, selecciona Stage all changes, y luego commit. Haz un fetch all para comprobar que todo está en orden. Haz un push para subir la rama al remoto: verifica en GitHub que la rama y los cambios se reflejen correctamente. Abre GitHub y ve a la pestaña de Pull Requests. Crea un nuevo PR desde el proyecto hacia el proyecto. Una vez aprobado el PR, haz el merge en GitHub.

 Regresa a GitKraken y sincroniza tu rama master local, haciendo un fetch all y luego un pull en la rama master y, por último, verifica que los cambios de tu tarea estén en la rama master.

1.1 Guia mediante capturas.
Una vez posicionados en el commit deseado procedemos:

Se realiza un reset de la rama para eliminar cualquier cambio que se haya llevado acabo antes.
![16e9d2a4-a63c-455b-9791-06c1127908f7](https://github.com/user-attachments/assets/4e9edeab-fbe5-4a4a-81bf-d95057892fcc)

Aqui se trata de estar al dia dentro del master y posicionarse en este.
![6ae4c645-9f6b-4086-81a7-127cdd718264](https://github.com/user-attachments/assets/7c1f0db4-361e-40a3-ae67-243109eafc37)

Aqui crearemos el Issue.
![87d3a8c9-7f0b-4648-b1a9-e3d742a43f2c](https://github.com/user-attachments/assets/64893d6a-457d-4ec6-9d77-b4b89e2019d1)
![180103e8-23d4-4022-8349-a032ab44994d](https://github.com/user-attachments/assets/2b757ce2-92a5-400b-8039-d8e1273e3cd4)

Una vez creado el Issue, se crea una rama nueva.
![c195fa9d-def8-4ad9-b4e4-c2d5083d505a](https://github.com/user-attachments/assets/0361a416-7f21-45fe-a37d-8ce1de1e33fc)
![8d4a789e-401a-4dfd-a202-1aa84fd25bd2](https://github.com/user-attachments/assets/569f8b30-ccd0-4d8a-9792-d906f152ae5e)

Una vez recien creada por defecto aparece dentro de REMOTE pero haciendo doble click automaticamente aparecera dentro de LOCAL
![3b99f9a1-b366-4ba9-8e6e-ec2416634ffb](https://github.com/user-attachments/assets/73ae960e-2978-4afb-8c3a-81ec966e72ca)
![55b2cddb-5253-4eec-8d33-88f5c6f75955](https://github.com/user-attachments/assets/38564b3e-4862-44b8-8219-12b2e4d2956e)
Aqui ya se puede apreciar que una vez hecho lo explicado en el punto anterior ya aparece dentro de LOCAL

Vamos a la carpeta donde se encuentre el repositorio de gobees y se debe copiar todos los archivos de la carpeta menos la carpeta .git.
![b103ebb0-5969-485e-a2a0-cc690431200e](https://github.com/user-attachments/assets/2edaeb7f-9efc-4cb6-9adc-6934403e948b)

Se deben transcribir los archivos copiados del repositoria de gobees a la carpeta donde se encuentre nuestro fork de nuestro repositorio.
![f0a7bf92-a672-4218-963a-eb248c98fe1c](https://github.com/user-attachments/assets/7ce3a3da-a220-4f1d-b184-ea4f36181c59)

Una vez realizado los cambios con las carpetas de los repositorios, GitKraken nos mostrara un mensaje con los nuevos cambios introducidos. Le damos al boton de View Changes y aparece esto:
![7c691761-8a64-4e0b-a333-55ab134b7dc7](https://github.com/user-attachments/assets/22a33424-0c54-458e-89a0-2844f4d97a01)

Presionamos el boton Stage All Changes y aparece esto:
![1aa8d6aa-d72e-4907-b9e4-b5a2c3a53d83](https://github.com/user-attachments/assets/e9424975-8361-46cc-8f02-7f50967297fc)

Y desde esta pestaña se confirmaran todos los cambios ya que se mueven desde Unstaged a Staged
![a17b1cda-27a4-413c-8090-36c68cec2e7b](https://github.com/user-attachments/assets/0571a74e-79f2-421b-aabc-e404b7c74009)

Desde GitHub vamos al apartado de Pull Request, y clicamos.
![0b427b51-22c9-4e76-b4b5-43c57390f36c](https://github.com/user-attachments/assets/04afc8b7-1ab4-49f3-ad5f-041a3326c634)

Vamos a seleccionar nuestro proyecto y una vez dentro:
![a6dcc3de-a60a-4f13-ab6c-ec2cc9c6f194](https://github.com/user-attachments/assets/b4cc48e3-32b6-4102-874a-170e0e0e8c2e)

Vamos a seleccionar la rama.
![08852f1d-694a-4ae5-880e-dcb5c17ce488](https://github.com/user-attachments/assets/a614023f-af52-4c8c-a04b-cd99d3fdea9d)

Una vez seleccionada la rama correspondiente se nos abrira esta pestaña, una vez dentro le daremos a Create Pull Request.
![315f17ba-fd57-490c-9097-41f00841ddc0](https://github.com/user-attachments/assets/f2b081da-f402-4068-882e-1f121c5efa01)

Le damos al boton de Create Pull Request.
![c01cf228-ce06-4a82-80e8-8b104c16d347](https://github.com/user-attachments/assets/69354f0b-fad8-49a2-9fab-128ca11f7736)

Nos sale un aviso que esta todo bien o no hay “conflictos” ( This branch has no conflicts with”...) y le damos a Merge Pull Request.
![eb171c25-c1f0-4b5e-8e1b-c2bf07d12e4f](https://github.com/user-attachments/assets/74e266b2-6c76-480e-8380-516d435059e2)

Le damos a Confirm Merge.
![f5298a08-e427-44ad-9fa2-995030f70845](https://github.com/user-attachments/assets/32fec627-c542-43c4-92ad-c5f6bf7d64a5)

Mensaje enviado por el sistema de que la “Pull Request” se ha creado correctamente.
![6fbdb621-bcbd-4cd7-8ba7-3b4bb001a51f](https://github.com/user-attachments/assets/3ce0b7f7-e3fe-4792-ad08-d31f1d18bf60)

Nos posicionamos en master dentro otra vezde GitKraken:
![34eb6771-4dd8-4098-b996-e5cca69dc0d2](https://github.com/user-attachments/assets/0e153a76-727c-4281-b22d-d7843c1cc63d)

Le damos a Pull
![ba0fe03d-f436-4da1-bf9c-b73d10b06eff](https://github.com/user-attachments/assets/b39de46b-9b7e-42da-9ecf-9f072dcadb06)

Y este seria el resultado final. En el cual se puede ver que todo el procedimiento explicado mediante las capturas y los comentarios debajo de cada foto han sido correctos.
![2f708162-e616-44f5-8a96-23e015794a49](https://github.com/user-attachments/assets/a9baf4b1-c4e3-486e-894f-0dca4f115b64)

--- La rama creada es a modo de prueba para poder realizar la explicación de la guia. ---

2.1
![877ab57c-0ab2-463b-9d15-7f6bf05db7f6](https://github.com/user-attachments/assets/5678320f-9092-49d2-83fc-6d2795225c71)

2.2
![8f789e81-157b-4200-b7f2-b8976680306b](https://github.com/user-attachments/assets/735b99c4-67ce-41e8-bc9f-ad61a823f03e)

2.3
![61bcdb2b-b30d-4dc6-b081-99cc5f7081ea](https://github.com/user-attachments/assets/7d05863d-6e90-4712-9974-d16c19d88086)

3.1
![c242b85a-506c-4bfe-98c1-22d7ca2beebc](https://github.com/user-attachments/assets/1a7737e2-1ce3-41f7-a1e9-5bd6da3249f2)

3.2
![b9322ba4-616c-4aa4-a340-7e202b3b8e3f](https://github.com/user-attachments/assets/3118cd59-74fc-4f3e-bb10-1399e5103993)

3.3
![98aad6e4-1f22-46dd-81d3-0263a4b5e006](https://github.com/user-attachments/assets/b86d2aa2-86a7-4e59-9e98-e585ec658756)

