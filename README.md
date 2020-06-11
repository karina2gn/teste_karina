# teste_karina

O teste consiste em criar uma api utilizando python v3 (pode ser v3.5 ou maior)
O teste tem duração máxima de 24horas
A api deve ser feita utilizando Flask como biblioteca principal com uma única URL, utilizando a porta 8080
-> ou seja http://localhost:8080

A api deve receber os parâmetros de posição do centro de uma circunferência em um plano (ou seja x e y)
-> bem como o raio da circunferência (r) e retornar em formato json as informações fornecidas, a distância à origem e
-> a área da circunferência.

O código deve ser publicado em arquivo único (app.py) e postado na raiz deste repositório.
O repositório pode ser usado como bem entender, com quantos commits quiser

DICAS: 
-> na página do flask tem diversos exemplos de uma api básica
-> Qualquer ambiente pode ser usado pra programar em python inclusive um bloco de notas, recomendado o próprio 
-> IDLE que vem com a instalação do python
-> Para retornornar um json é só utilizar um dicionário em python e enviar pela função make_response

MODO DE USAR:
http://localhost:8080/X/Y/R
Sendo, X e Y, as coordenadas do centro da circunferência e R o raio.
