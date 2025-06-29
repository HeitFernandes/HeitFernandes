# Heitor Fernandes - Backend Engineer

```java
/**
 * Estudante FATEC DSM 1º Semestre | Backend Engineer
 * Transformando café em sistemas escaláveis ☕
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
