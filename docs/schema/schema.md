# Sample API JSON Schema

In this schema file, we represents the public interface of Sample API in JSON Hyper Schema draft v4.

## <a name="resource-dog">Pets API</a>


Pets API

### <a name="link-GET-dog-/api/v1/dogs">Pets API GET /api/v1/dogs</a>

get dog list

```
GET /api/v1/dogs
```


#### Curl Example

```bash
$ curl -n http://localhost:3000/api/v1/dogs
```


#### Response Example

```
HTTP/1.1 200 OK
```

```json
[
  {
    "id": 1,
    "name": "example_name",
    "contact_email": "example@example"
  }
]
```


## <a name="resource-pet">Pets API</a>


Pets API

### <a name="link-GET-pet-/pets">Pets API GET /pets</a>

get pet list

```
GET /pets
```


#### Curl Example

```bash
$ curl -n http://localhost:3000/pets
```


#### Response Example

```
HTTP/1.1 200 OK
```

```json
[
  {
    "id": 1,
    "name": "example_name",
    "contact_email": "example@example"
  }
]
```


