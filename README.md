# Junit-TDD

Exercícios de Desenvolvimento Orientado a Testes (TDD) em Java com JUnit 5 e Maven, aplicando o ciclo red-green-refactor.

## Conteúdo

### Atividade 1 (raiz do projeto)
- `ContaBancaria`: depósito, saque e transferência entre contas, com regras de negócio (sem valores negativos ou zero, sem saque acima do saldo).

### Atividade 2 (`Atividade_2_TDD`)
- `MathUtils`: soma, verificação de par e fatorial com proteção contra overflow.
- `StringUtils`: inverter texto, contar vogais e verificar palíndromo.
- `GradeUtils`: média de notas, conceito (A a D) e situação (Aprovado/Reprovado).

## Tecnologias

- Java
- JUnit 5
- Maven

## Como rodar os testes

Pré-requisitos: JDK e Maven instalados.

Atividade 1, na raiz do projeto:

```
mvn test
```

Atividade 2:

```
cd Atividade_2_TDD
mvn test
```

## Estrutura

```
Junit-TDD
├── src
│   ├── main/java/br/com/teste/modelo   (ContaBancaria)
│   └── test/java                       (ContaBancariaTest)
└── Atividade_2_TDD
    └── src
        ├── main/java/br/com/teste/modelo   (MathUtils, StringU
