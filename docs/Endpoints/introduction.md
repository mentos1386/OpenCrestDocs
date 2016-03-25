Documentation on how to use endpoints, what they return, and if they are implemented.

If there is `AUTH` in the title, that means that OAuth token is required to use the Endpoint.

You can use endpoints with:

 - `OpenCrest::[EndpointName]->get();` which gets list of items
 - `OpenCrest::[EndpointName]->show([ID]);` which returns specific item.
 - POST/PUT/DELETE Aren't implemented in library yet

Relations can be loaded after getting object with (`get()` used with relationships returns specific or list of items, depending on relationship, not to be confused with `Endpoint()->get()`):
```php
$characterCorporation = OpenCrest::Characters()->show(ID)->corporation->get();
```