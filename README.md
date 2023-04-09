# Login/registration complete backend using Spring Boot 🍃

---

## Diagram:

![Untitled](Login%20registration%20complete%20backend%20using%20Spring%20B%204bf9d0380508462381958e9dfe9f4c19/Untitled.png)

---

## Dependencies used:

- Spring Boot DevTools;
- Lombok;
- Spring Web (MVC);
- Spring Security;
- Spring Data JPA;
- PostgreSQL Driver;
- Java Mail Sender.

---

## How works:

It’s a complete REST API backend, that saves personal data, like email and password, and sends a confirmation email using a unique generated token, that expires in 15 minutes.

---

# How to use:

First, you do a registration using a normal request:

## Requesting

You can make a POST request using postman on the address:

 “[http://localhost:8080/api/v1/registration](http://localhost:8080/api/v1/registration)”.

### Example:

![Untitled](Login%20registration%20complete%20backend%20using%20Spring%20B%204bf9d0380508462381958e9dfe9f4c19/Untitled%201.png)

The POST request will return a unique generated token.

---

## Mail sending and Login interface

To use the mail sending you will have to install and run [MailDev](https://github.com/maildev/maildev):

```bash
$ npm install -g maildev
$ maildev
```

Then, open the MailDev address: “[http://0.0.0.0:1080/#/](http://0.0.0.0:1080/#/)"

A new confirmation email will be there:

![Untitled](Login%20registration%20complete%20backend%20using%20Spring%20B%204bf9d0380508462381958e9dfe9f4c19/Untitled%202.png)

Click on the link in less than 15 minutes and the account will be enabled.

After that, open the address: “[http://localhost:8080/login](http://localhost:8080/login)”

![Untitled](Login%20registration%20complete%20backend%20using%20Spring%20B%204bf9d0380508462381958e9dfe9f4c19/Untitled%203.png)

And sign in with the credencials used on the registration.

---

# Reference:

**Amigoscode - Java Tutorial - Complete User Login and Registration Backend + Email Verification**: [https://www.youtube.com/watch?v=QwQuro7ekvc](https://www.youtube.com/watch?v=QwQuro7ekvc)
