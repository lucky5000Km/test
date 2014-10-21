## App
FIXME

### Attributes
<table>
  <tr>
    <th>Name</th>
    <th>Type</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td><strong>created_at</strong></td>
    <td><em>date-time</em></td>
    <td>when app was created</td>
    <td><code>"2012-01-01T12:00:00Z"</code></td>
  </tr>
  <tr>
    <td><strong>id</strong></td>
    <td><em>uuid</em></td>
    <td>unique identifier of app</td>
    <td><code>"01234567-89ab-cdef-0123-456789abcdef"</code></td>
  </tr>
  <tr>
    <td><strong>updated_at</strong></td>
    <td><em>date-time</em></td>
    <td>when app was updated</td>
    <td><code>"2012-01-01T12:00:00Z"</code></td>
  </tr>
</table>

### App Create
Create a new app.

```
POST /apps
```


#### Curl Example
```bash
$ curl -n -X POST https://api.hello.com/apps
```


#### Response Example
```
HTTP/1.1 201 Created
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```

### App Delete
Delete an existing app.

```
DELETE /apps/{app_id}
```


#### Curl Example
```bash
$ curl -n -X DELETE https://api.hello.com/apps/$APP_ID
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```

### App Info
Info for existing app.

```
GET /apps/{app_id}
```


#### Curl Example
```bash
$ curl -n -X GET https://api.hello.com/apps/$APP_ID
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```

### App List
List existing apps.

```
GET /apps
```


#### Curl Example
```bash
$ curl -n -X GET https://api.hello.com/apps
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
[
  {
    "created_at": "2012-01-01T12:00:00Z",
    "id": "01234567-89ab-cdef-0123-456789abcdef",
    "updated_at": "2012-01-01T12:00:00Z"
  }
]
```

### App Update
Update an existing app.

```
PATCH /apps/{app_id}
```


#### Curl Example
```bash
$ curl -n -X PATCH https://api.hello.com/apps/$APP_ID
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```


## User
FIXME

### Attributes
<table>
  <tr>
    <th>Name</th>
    <th>Type</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td><strong>created_at</strong></td>
    <td><em>date-time</em></td>
    <td>when user was created</td>
    <td><code>"2012-01-01T12:00:00Z"</code></td>
  </tr>
  <tr>
    <td><strong>id</strong></td>
    <td><em>uuid</em></td>
    <td>unique identifier of user</td>
    <td><code>"01234567-89ab-cdef-0123-456789abcdef"</code></td>
  </tr>
  <tr>
    <td><strong>updated_at</strong></td>
    <td><em>date-time</em></td>
    <td>when user was updated</td>
    <td><code>"2012-01-01T12:00:00Z"</code></td>
  </tr>
</table>

### User Create
Create a new user.

```
POST /users
```


#### Curl Example
```bash
$ curl -n -X POST https://api.hello.com/users
```


#### Response Example
```
HTTP/1.1 201 Created
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```

### User Delete
Delete an existing user.

```
DELETE /users/{user_id}
```


#### Curl Example
```bash
$ curl -n -X DELETE https://api.hello.com/users/$USER_ID
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```

### User Info
Info for existing user.

```
GET /users/{user_id}
```


#### Curl Example
```bash
$ curl -n -X GET https://api.hello.com/users/$USER_ID
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```

### User List
List existing users.

```
GET /users
```


#### Curl Example
```bash
$ curl -n -X GET https://api.hello.com/users
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
[
  {
    "created_at": "2012-01-01T12:00:00Z",
    "id": "01234567-89ab-cdef-0123-456789abcdef",
    "updated_at": "2012-01-01T12:00:00Z"
  }
]
```

### User Update
Update an existing user.

```
PATCH /users/{user_id}
```


#### Curl Example
```bash
$ curl -n -X PATCH https://api.hello.com/users/$USER_ID
```


#### Response Example
```
HTTP/1.1 200 OK
```
```json
{
  "created_at": "2012-01-01T12:00:00Z",
  "id": "01234567-89ab-cdef-0123-456789abcdef",
  "updated_at": "2012-01-01T12:00:00Z"
}
```


