<h2>IMDB API Clone With DRF</h2>

<h3>Install all Packages</h3>

    pip3 install -r requirements.txt

<h3>Create model</h3>

    <li>python3 manage.py makemigrations</li>
    <li>python3 manage.py migrate</li>
    <li>python3 manage.py createsuperuser</li>

<h3>Run local server</h3>
    <li>python3 manage.py runserver 8080</li>

<h3>Admin login</h3>
    <li>http://localhost:8080/admin/</li>

<h3>API endpoints</h3>
    <li>http://localhost:8080/watch/<(chack urls.py and add endpoint to get movie list, detail, create, update, delete)></li>


<h3> Reference Reading Links (Arranged According To Lectures)</h3>
<br>

<b> Understanding REST API</b>
<ul>
    <li>https://towardsdatascience.com/introduction-to-rest-apis-90b5d9676004</li>
</ul>
<br>

<b> Basic Django Setup</b>
<ul>
    <li>https://www.djangoproject.com/</li>
    <li>https://code.visualstudio.com/download</li>
</ul>
<br>

<b> DRF Introduction</b>
<ul>
    <li>https://www.django-rest-framework.org/</li>
</ul>
<br>

<b> Postman</b>
<ul>
    <li>https://www.postman.com/</li>
    <li>https://www.postman.com/downloads/</li>
</ul>
<br>

<b> Basic Authentication</b>
<ul>
    <li>https://www.base64encode.org/</li>
</ul>
<br>

<b> JWT Authentication</b>
<ul>
<li>https://jwt.io/</li>
<li>https://medium.com/devgorilla/how-to-log-out-when-using-jwt-a8c7823e8a6</li>
<li>https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html</li>
<li>https://medium.com/django-rest/django-rest-framework-jwt-authentication-94bee36f2af8https://stackoverflow.com/questions/61547014/restful-uri-trailing-slash-or-no-trailing-slash</li>
</ul>
<br>

<b> Throttling Introduction</b>
<ul>
  <li>https://medium.com/analytics-vidhya/throttling-requests-with-django-rest-framework-for-different-http-methods-3ab0461044c</li>
</ul>
<br>

<b> Test Driven Development</b>
<ul>
  <li>https://medium.com/@ksarthak4ever/test-driven-development-tdd-in-django-and-django-rest-framework-drf-a889a8068cb7</li>
</ul>