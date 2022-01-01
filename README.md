# Api simples com Java
Tecnologias usadas:
- Java
- Spring boot Framework
- H2 Database

Como rodar:
- Clone este repositório
- Abra com sua IDE Java
- Build & Run "USERDEPTAPPLICATION"

End-points:
GET
- /Users 
- /Users/1  (Podendo substituir "1" pelo Id)

POST
- /Users

TABLES
- td_user
- td_department

BODY
Department
- id
- name

User
- Long id
- String name
- String email
- Department department
