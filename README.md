# Projeto de Refatoração de Código (Adopet)

Projeto do curso **Boas Práticas em Java** da Alura. Refatoração do console app **Adopet** — sistema de adoção de pets que consome uma API externa.

## O que faz

- Lista abrigos e pets disponíveis para adoção
- Permite adotar pets via linha de comando
- Aplica boas práticas de código: separação em camadas, services, testes e tratamento de erros
- Consome API HTTP de abrigos e pets

## Tecnologias

- Java 17+
- Maven
- JUnit (testes)
- HTTP Client (Java 11+)

## Estrutura

```text
src/main/java/br/com/alura/
├── domain/       # Entidades (Pet, Abrigo)
├── service/      # Regras de negócio
├── client/       # Cliente HTTP
└── principal/    # Console interativo
```

## Como rodar

```bash
git clone https://github.com/Agsterr/Projeto_de_refatoracao_de_codigo.git
cd Projeto_de_refatoracao_de_codigo
mvn compile exec:java -Dexec.mainClass="br.com.alura.AdopetConsoleApplication"
```

## Testes

```bash
mvn test
```

## Autor

**Agster Junior da Costa Santos** — projeto de estudo Alura
