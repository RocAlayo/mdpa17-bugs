Rellenar el error con los siguientes parámetros:

# Endpoint

POST /profile

# Request Body

```javascript
{
	"firstName": "Kvothe"
}
```

# Response Body

```javascript
{
	"code": 400,
	"message": "There is like a lot of attributes missing"
}
```

# Description

La documentación dice que solo es necessario el `firstName` pero no funciona.
