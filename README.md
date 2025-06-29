# Heitor Fernandes - Backend Java Engineer

<div align="center">
<a href="https://github.com/HeitFernandes">
<img loading="lazy" height="150em" style="margin-right: 50px;" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HeitFernandes&layout=compact&langs_count=7&theme=dracula"/>
<img loading="lazy" height="150em" src="https://github-readme-stats.vercel.app/api?username=HeitFernandes&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</a>
</div>

```java
/**
 * Estudante FATEC DSM 1º Semestre | Backend Engineer
 * 
 * Neste perfil compartilho:
 * - Projetos acadêmicos e experimentos em Java
 * - Estudos de Spring Boot e arquitetura de software
 * - Resoluções de desafios algorítmicos
 * - Evolução do meu roadmap de desenvolvimento
 */
@SpringBootApplication
public class HeitProfile {
    public static void main(String[] args) {
        SpringApplication.run(HeitProfile.class, args);
    }

    @Bean
    public Stack techStack() {
        return Stack.builder()
            .language("Java 17")
            .frameworks("Spring Boot 3, Hibernate")
            .databases("PostgreSQL, MongoDB")
            .architecture("Microservices")
            .build();
    }
}

@Data
@Builder
class Stack {
    private String language;
    private String frameworks;
    private String databases;
    private String architecture;
}

