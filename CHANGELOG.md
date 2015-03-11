* Added the concept of backend parameters via `new PinejsClient(params, backendParams)` and `.clone(params, backendParams)`
* Added a `cache` backend parameter to the request backend, which is used to create a bluebird-lru-cache cache for GET request ETags.

v1.1.0

* Added a `compile` function that can be used to compile a request object to a url without sending off an actual request.
* Fixed the case of passing no params to the constructor/clone methods.

v1.0.0

* Initial release
