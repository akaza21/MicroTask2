

# Second Microtask
## It is a microservice which accumulates three different microservice APIs : ErrorHandler,Authentication and Visitor counter


## Installation

```bash
    git clone https://github.com/akaza21/MicroTask2

```
### `Navigation`
```bash
    cd Microtask2
```
```bash
    cd AuthAPI or cd ErrorHandler or cd ViewCounter
```
### `Installation`



```bash
  npm i
```



### `Runserver`

```bash
  npm start
```


## API Reference
### ErrorHandler

#### Get a random error message which is handled by a dummy ErrorHandler middleware

```http
  GET http://localhost:3000/api/error
```



### Authentication

#### Sign-up(Returns token )

```http
  POST http://localhost:3000/api/sign-up
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | **Required**|
| `body` | `password` | **Required**|


#### Log In(Returns token)

```http
  GET http://localhost:3000/api/sign-in
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | **Required**|
| `body` | `password` | **Required**|

#### Restricted route

```http
  GET http://localhost:3000/api/sign-in
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `header` | `token` | **Required**|



### Visitor counter


```http
  POST http://localhost:3000/api/get-views
```



![App Screenshot](https://i.imgur.com/Q9WAUn5.png)

![App Screenshot](https://i.imgur.com/Hx1IMYD.png)
![App Screenshot](https://i.imgur.com/S1PqbnD.png)
## Author

- [@akaza21](https://www.github.com/akaza21)







