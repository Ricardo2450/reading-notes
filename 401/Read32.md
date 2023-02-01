# DRF Permissions

> ## [DRF Permissions](https://www.django-rest-framework.org/api-guide/permissions/)

* permissions determine whether a request should be granted or denied access.

* Permission checks will typically use the authentication information in the request.user and request.auth properties to determine if the incoming request should be permitted.

* Object level permissions are used to determine if a user should be allowed to act on a particular object

* Object level permissions are run by REST framework's generic views when .get_object() is called

* IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.

* IsAdminUser permission class will deny permission to any user, unless user.is_staff is True.

* IsAuthenticatedOrReadOnly will allow authenticated users to perform any request

* POST requests require the user to have the add permission on the model.

* PUT and PATCH requests require the user to have the change permission on the model.

* DELETE requests require the user to have the delete permission on the model.

* queryset/get_queryset(): Limits the general visibility of existing objects from the database. The queryset limits which objects will be listed and which objects can be modified or deleted. The get_queryset() method can apply different querysets based on the current action.

* permission_classes/get_permissions(): General permission checks based on the current action, request and targeted object. Object level permissions can only be applied to retrieve, modify and deletion actions. Permission checks for list and create will be applied to the entire object type. (In case of list: subject to restrictions in the queryset.)

* serializer_class/get_serializer(): Instance level restrictions that apply to all objects on input and output. The serializer may have access to the request context. The get_serializer() method can apply different serializers based on the current action.


> ## Other reads

* [Review SQL Prework](https://codefellows.github.io/common_curriculum/prework/SQL)

* [Classy Django REST](http://www.cdrf.co/)

* [DRF Generic Views](https://www.django-rest-framework.org/api-guide/generic-views/)

[Return Home](../README.md)
