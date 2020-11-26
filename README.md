# Listar-Personagens-Marvel

Esse projeto é sobre como listar personagens da marvel consumindo a API da Marvel usando JavaScript.

Para consumir a API da Marvel é preciso ter uma chave pública e uma chave privada, que pode-se conseguir acessando o link abaixo e clicando na aba “Obtenha uma chave”.
https://developer.marvel.com/

Você pode encontrar detalhes de como consumir a API na documentação que se encontra no link abaixo:
https://developer.marvel.com/documentation/authorization

É preciso ter a hash md5. Para calcular a mesma é preciso concatenar o timeStamp, a privateKey e a publicKey. 
Para obter o timeStamp basta usar o seguinte comando no console do browser:
Math.floor(Date.now() / 1000) 

Pode-se calcular a hash md5 acessando o link abaixo.
https://www.md5hashgenerator.com/


