# Contador de acessos - JWT

.NET 6 + ASP.NET Core + JWT + Swagger: implementando a utilização de tokens

````
docker build -t starsolution/contator:latest .
docker run -d -it --name contator -p 80:80 starsolution/contator
````

Link da API: http://localhost/swagger/index.html

### Testes via Swagger dependerão das credenciais:
````
{
    "userID": "usr01_apis",
    "password": "Usr01ApiValido01!"
}
````
Este token deverá ser informado no campo **Value** 
na tela que aparecerá ao acionar o botão **Authorize**, 
sendo precedido pela palavra **Bearer** e um caracter de espaço

