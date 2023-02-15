Punto de partida

### Url githu   https://github.com/flaviovidalhuax/chatAPI-backend-NODE
### Url dbDiagram https://dbdiagram.io/d/63e5c3ed296d97641d7fe0a7

Cuando queremos recuperar una contraseña hago una peticion que me pide el email

/api/v1/auth/recovery-password
- post crear un nuevo recovery password
    - Llegar el correo electronico 
    - Link que te permite hacer una peticion para actualizar tus datos

/api/v1/auth/recovery-password/:id
- patch actualizar la contraseña validando el enlace del recovery password
    - cuando mandamos la nueva contraseña pasan 2 cosas
        - Se modifica la contraseña en el usuario
        - Se modifica el recoveryToken como ya usado, para que no se pueda volver a utilizar
- /api/v1/users
    - get('/')
    - post('/')
- /api/v1/users/me
    - get()
    - patch()
    - delete()
    - /api/v1/users/:id
    - get()
    - patch()
    - delete()

- /api/v1/auth
    - /login
    - /recovery-password

- /api/v1/conversations
    - get('/')
    - post('/')
