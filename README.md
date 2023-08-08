
# 💻 Sobre o projeto

Um aplicativo de streaming de vídeo como o Youtube, obviamente, não é o clone completo do Youtube, mas apenas um conjunto mínimo de funcionalidades, o que é comum para aplicativos de streaming de vídeo como o Youtube.


![youtube_clone_Architecture.jpg](https://github.com/Andersonfreitas21/files/blob/main/youtube_clone_Architecture.jpg)


## 🛠 Tecnologias

- **[Java 17](https://www.oracle.com/java)**
- **[Spring Boot](https://spring.io/projects/spring-boot)**
- **[Maven](https://maven.apache.org)**
- **[MongoDB](https://www.mongodb.com/pt-br)**
- **[Hibernate](https://hibernate.org)**
- **[Lombok](https://projectlombok.org)**

## Referência

 - [Spring Boot Angular Project – Crie um Clone do Youtube – Parte 1](https://programmingtechie.com/2021/07/10/spring-boot-angular-project-build-a-youtube-clone-part-1/)


## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Autor

- [@andersonfreitas21](https://www.github.com/Andersonfreitas21)


## Licença

## 📝 Licença

Projeto desenvolvido por [SaiUpadhyayula](https://github.com/SaiUpadhyayula) e utilizado nos cursos de Spring Boot.

---
