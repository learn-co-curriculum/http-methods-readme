# HTTP Methods

HTTP methods consist of four methods: `GET`, `POST`, `PUT`, and `DELETE`.

### GET

The HTTP `GET` method retrieves a resource. Provided that there is no error in retrieving the resource, the `GET` request will return the resource in either a XML or JSON format, along with an HTTP status code of 200. If there is an error, the request will typically return either a 404 (not found) or 400 (bad request)  status code.

### Put

The HTTP `PUT` method updates a resource. Once the resource is updated successfully on the server, then a 200 status code is returned. If there is an error, the request will typically return either a 404 (not found) or 400 (bad request)  status code.

### Post

The HTTP `POST` method creates a new resource. Once the new resource has been created successfully on the server, a 201 status code is returned in addition to a location header with a link to the new resource. If the new resource can't be created, typically a 400 status code is returned.

### Delete

The HTTP `DELETE` method deletes an existing resource. If the resource has been successfully deleted, either a 200 status code or a 204 status code (no content) will be returned. If the resource can't be deleted, either a 400 or 404 status code will be returned.

### Resources
- [HTTP Methods Tutorial](http://www.restapitutorial.com/lessons/httpmethods.html)
- [Offical HTTP Documentation](http://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html)
