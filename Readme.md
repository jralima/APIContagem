# Contador de acessos - JWT

.NET 6 + ASP.NET Core + JWT + Swagger: implementando a utilização de tokens

Utilizando o Dockerfile:
 - Para rodar o container manualmente, basta executar os seguintes passos:
 
```console
docker build -t starsolution/contator:latest .
docker run -d -it --name contator -p 80:80 starsolution/contator
```

Para acessar o swagger acesse:

```console
http://localhost/swagger/index.html
```

### Testes via Swagger dependerão das credenciais:
```console
{
    "userID": "usr01_apis",
    "password": "Usr01ApiValido01!"
}
```
Este token deverá ser informado no campo **Value** 
na tela que aparecerá ao acionar o botão **Authorize**, 
sendo precedido pela palavra **Bearer** e um caracter de espaço

