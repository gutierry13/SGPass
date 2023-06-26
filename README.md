# App

Gympass style app

## RFs (Requisitos funcionais)
 - [  ] Deve ser possível se cadastrar  
 - [  ] Deve ser possível se autenticar
 - [  ] Deve ser possível obter o perfil de um usuário logado
 - [   ] Deve ser possível obter o número de check-in realizados pelo usuário logado
 - [   ] Deve ser possível o usuário   obter seu histórico de check-in
 - [   ] Deve ser possível o usuário buscar academias próximas  
 - [   ] Deve ser possível o usuário buscar academias pelo nome
 - [   ] Deve ser possível o usuário realizar check-in em uma academia
 - [   ] Deve ser possível validar o check-in de um usuário
 - [   ] Deve ser possível cadastrar uma academia
## RNs (Regras de negócio)
 - [   ] O usuário não pode se cadastrar com um email duplicado
 - [   ] O usuário não pode fazer 2 check-ins no mesmo dia
 - [   ] O usuário não pode fazer check-in se não estiver perto (100m) da academia
 - [   ] O check-in só pode ser validade até 20 minutos após criado
 - [   ] O check-in só pode ser validado por administradores 
 - [   ] A academia só pode ser cadastrada por administradores
## RNFs (Requisitos não funcionais)
- [   ] A senha do usuário precisa estar criptografada
- [   ] Oss dados da aplicação precisam estar persistidos em um banco PostgresSql
- [   ] Todas listas de dados precisam estar paginadas com 20 items por pagina
- [   ] O usuário deve ser identificado por um JWT (JSON Web Token)



