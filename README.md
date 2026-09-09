<div align="center">
  <h1>Lucas Marques</h1>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=0077B5&center=true&vCenter=true&width=600&lines=Desenvolvedor+Backend+Java+e+Spring+Boot;APIs+seguras%2C+test%C3%A1veis+e+eficientes;Foco+em+Solu%C3%A7%C3%B5es+Financeiras" alt="Typing Animation" />
  <br/>
  <p>
    <a href="https://www.linkedin.com/in/lucas-marques" target="_blank">
      <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:lucaamarques2406@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>
---
 
### 📌 Sobre Mim
 
Sou desenvolvedor backend Java e gosto do tipo de problema em que errar custa caro: dinheiro saindo de uma conta e não entrando na outra, mensagem que some no meio do caminho, requisição repetida que cobra duas vezes. É por isso que meu foco é o setor financeiro.
 
Meu critério de "pronto" não é o endpoint devolver 200 — é ter teste de integração passando, erro tratado de forma consistente e `docker compose up` funcionando na máquina de qualquer pessoa.
 
* **💼 Atuação:** Analista de Sistemas Jr — sistemas web com Java/Spring Boot, PostgreSQL e Docker
* **🎓 Acadêmico:** Bacharelando em Ciência da Computação — Universidade São Judas Tadeu
* **🎯 Foco atual:** Spring Security/JWT, mensageria com RabbitMQ (DLQ e retry) e testes com TestContainers
* **🏦 Interesse:** Open Finance, sistemas de pagamento e infraestrutura bancária
---
 
### 🚀 Projetos
 
| Projeto | O que resolve | Stack |
|---|---|---|
| [**transfer-api**](https://github.com/Lmsantoz/transfer-api) | Transferências bancárias com controle transacional e rollback em falha. Testes de concorrência com **TestContainers** contra PostgreSQL real, garantindo que transferências simultâneas não corrompem o saldo. | `Java 21` `Spring Boot` `PostgreSQL` `Flyway` `TestContainers` |
| [**auth-api**](https://github.com/Lmsantoz/auth-api) 🚧 | Autenticação **JWT** com roles e senhas em BCrypt. Publica eventos de domínio em *fanout exchange* no RabbitMQ, com **dead letter queue** e retry com backoff — mensagem defeituosa não trava a fila nem some em silêncio. | `Spring Security` `JWT` `RabbitMQ` `PostgreSQL` |
| [**client-api**](https://github.com/Lmsantoz/client-api) | CRUD com paginação, Bean Validation, tratamento centralizado de exceções via `@RestControllerAdvice` e documentação **Swagger/OpenAPI**. | `Spring Boot` `JPA/Hibernate` `Mockito` `SpringDoc` |
 
---
 
### 🛠️ Stack Tecnológica
 
**🟢 Core Backend & Persistência**
<br/>
<img src="https://skillicons.dev/icons?i=java,spring,postgres,hibernate&theme=dark" alt="Backend" />
<br/>
<sub>Java 21 · Spring Boot · Spring Security · JPA/Hibernate · Flyway · PostgreSQL</sub>
 
**🟡 Infraestrutura & Mensageria**
<br/>
<img src="https://skillicons.dev/icons?i=docker,linux,rabbitmq&theme=dark" alt="Infra" />
<br/>
<sub>Docker · Docker Compose · RabbitMQ (exchanges, DLQ, retry) · Linux</sub>
 
**🔵 Testes & Ferramentas**
<br/>
<img src="https://skillicons.dev/icons?i=git,maven,postman&theme=dark" alt="DevTools" />
<br/>
<sub>JUnit 5 · Mockito · TestContainers · Maven · Git · Postman</sub>
 
**📚 Estudando agora**
<br/>
<img src="https://skillicons.dev/icons?i=redis,aws,kubernetes&theme=dark" alt="Learning" />
 
---
### 🗺️ Próximos Passos
 
- [x] API transacional com testes de concorrência — `transfer-api`
- [ ] JWT + mensageria com DLQ e retry — `auth-api`
- [ ] Idempotência de requisições e cache com **Redis**
- [ ] Deploy em **AWS** com observabilidade (Prometheus + Grafana)
- [ ] Sistema distribuído de conciliação em **Kubernetes**
