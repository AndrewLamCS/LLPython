# Github Linkedin Learning Django Project
This is a repository for a Linkedin Learning Django project.

Notes:
Building a system - Model + CRUD

CRUD operations:
Create - from django.views.generic import CreateView
Retrieve
Update
Delete

CSRF Token - cross site request forgery 
    -every time a browser requests a webpage that has a form, Django sends a unique token to that browser
    -token is securely kept and no other website can access it
    -when the user sends back a form, it also sends back the token allowing Django to know that the request is coming from a legit user
    -Django processes the request and returns the appropriate response (If a 3rd party tries to make the request from another browser, they wont have the token - does not process the request to prevent attack)

test1 - useruser1
django - useruser2