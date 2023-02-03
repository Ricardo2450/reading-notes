# Authentication & Production Server

> ## [JSON Web Tokens](https://jwt.io/introduction/)

* JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object

* JWTs can be signed using a secret or a public/private key pair using RSA or ECDSA.

* Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties

* JSON Web Tokens consist of three parts separated by dots:
  * Header
  * Payload
  * Signature

* header typically consists of two parts: the type of the token, which is JWT, and the signing algorithm being used

* payload, which contains the claims. Claims are statements about an entity (typically, the user) and additional data

* three types of claims: registered, public, and private claims.
  * Registered claims: These are a set of predefined claims which are not mandatory but recommended, to provide a set of useful, interoperable claims
  * Public claims: These can be defined at will by those using JWTs
  * Private claims: These are the custom claims created to share information between parties that agree on using them and are neither registered or public claims.

* signature is used to verify the message wasn't changed along the way, and, in the case of tokens signed with a private key, it can also verify that the sender of the JWT is who it says it is.

> ## [DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

* JWT is acquired by exchanging an username + password for an access token and an refresh token.
  * access token is usually short-lived. 5 mins
  * refresh token lives a little bit longer. 24 hr.

> ## [Django Runserver Is Not Your Production Server](https://build.vsupalov.com/django-runserver-in-production/)

* only use tech in production, which is reliable and well tested.

* application, which is great at serving static files from disk and handling multiple requests at once

* application server gets those fancy requests and uses them to construct Python objects which are usable by Django


> ## Other reads and videos

* [JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)

* [Gunicorn](https://gunicorn.org/)

* [Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)



[Return Home](../README.md)
