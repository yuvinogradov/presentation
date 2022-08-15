# JSON Web Token

## Intro
### Theory
#### The old way
I will start from dinosaurs. 
(Picture with dinos in old-time server room) 
When projects were small and servers were big th
#### The problem
---
## Solution - JWT
RFC 7519
### How does it work

---
## JWT -> JSON Web Encryption Token (JWE) + JSON Web Encryption Token (JWS)
https://www.youtube.com/watch?v=5Er3vD7eEb4


---
## JWT problems
...
1. В чистом виде, когда мы используем два токена - использовать его плохо.
2. JWT превосходно подходит для сценариев, когда вам нужен одноразовый токен. Представим себе, что у вас есть некий удаленный сервер, который хранит кучу файлов. И некий распределительный сервер, который говорит: вот этот пользователь может скачать вот этот файл. Распределительный сервер может выписать токен
 