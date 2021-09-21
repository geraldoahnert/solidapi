## Solid API

### About

> Solid API from RocketSeat YouTube content. [Reference.](https://youtu.be/vAV4Vy4jfkc)

On this app you can learn about S.O.L.I.D. principles.

- Single Responsibility Principle
- Liskov Substitution Principle
- Dependency Inversion Principle

Disconnection of the infra layer from the functional layer.

### Changes

- 'uuidv4' lib to 'uuid' because its deprecated.
- Using my credentials to send email test with Mailtrap.

### How can i use

```bash
$ git clone https://github.com/geraldoahnert/solidapi

$ cd solidapi && yarn install

# Create your .env with your mailtrap credentials.

$ yarn start
```

Send a **POST** request to _http://localhost:3333/users_.

```json
{
  "name": "Jhon",
  "email": "jhon@email.com",
  "password": "123456"
}
```
