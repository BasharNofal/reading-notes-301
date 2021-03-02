## SENDING FORM DATA

* Using forms to send data is a way to use http to send data from user side to server side and then from the server to the user.
* This can be done by using the attributes **method** and **action**.
* In **method** you specify the operation which is usually **GET** and **POST**, where in **action** you specify the url where you want the user to be redirected after submitting the form.
* **GET** requests are sent in query sting in the url requests where you can specify of filter the data that you want using query params.
* **POST** requests are sent in the body where you can send more data because the data is limited in the query string.
* The data received on the server side is in key-value form.
