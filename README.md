# Checkout GitLab

Actions para facilitar el checkout a un repositorio GitLab.

## ¿Que es Checkout-GitLab?

Checkout-GitLab es un action que permite el clonado de un repositorio GitLab solo requiere 3 parametros de entrada.

	Usuario del repositorio.
	Contraseña del repositorio.
	URL del repositorio. IMPORTANTE no debes colocar el "https://".

## Instrucciones

1. Copiar el llamado del action en el maketplace de GitHub. Recomendamos usar siempre la ultima versión.

Ejemplo:

<p align="center">
  <img width="671" height="61" alt="action" src="public/img/action.PNG">
</p>

2. Pega en tu workflow y añade la etiqueta with: añadiendo los parametros: user_repo:, pass_repo: y  url_repo:.

Ejemplo:

<p align="center">
  <img width="667" height="149" alt="action_with" src="public/img/action_with.PNG">
</p>

Se debe indicar el valores que corresponden. Nota: se puedes colocar los valores directos otra forma de trabajar es variabilizar los valores.

Ejemplo 2:

<p align="center">
  <img width="654" height="150" alt="action_with_variables" src="public/img/action_with_variables.PNG">
</p>

## Limitaciones

De momento solo se realizaron pruebas con repositorios GitLab. No se descarta su compatibiliad con otras compañias.