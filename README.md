# Laboratorio-3

## Sumário

### [Diagramas](#diagramas)
- [Caso de Uso](#diagrama-de-caso-de-uso)
- [Implementação](#diagrama-de-implementação)
- [Componentes](#diagrama-de-componentes)
- [Classes](#diagrama-de-classes)
- [Mapeamento Modelo relacional](./docs/Mapeamento%20Diagrama%20De%20Classe%20Modelo%20Relacional.md)
- [Seguencia](#diagramas-de-seguencia)
    - [Aluno](#aluno)
    - [Cliente](#cliente)
    - [Instituição](#instituição)
    - [Parceiro](#parceiro)
    - [Professor](#professor)
    - [Usuário](#usuário)
### [Historia de Usuário](#historia-de-usuários-e-regras-de-negócio)
### [Seminário](./seminario/seminario.md/#seminário-net)

---

# Diagramas

## Diagrama de Caso de Uso
![Diagrama de Caso de Uso](./docs/img/Caso%20de%20Uso.png)

#### [Back](#sumário)

## Diagrama de Implementação
![Diagrama de Implementação](./docs/img/Diagrama%20de%20Implementa%C3%A7%C3%A3o.png)

#### [Back](#sumário)

## Diagrama de Componentes
![Diagrama de Componentes](./docs/img/Diagrama%20de%20Componentes.png)

#### [Back](#sumário)

## Diagrama de Classes
![Diagrama de Classes](./docs/img/Diagrama%20de%20Classes.png)

#### [Back](#sumário)

## Diagramas de Seguencia
## Aluno
### A1, A2
![Diagrama de Seguencia - A1, A2](./docs/img/Diagramas%20de%20Seguencia/Aluno-A%23/A1_A2.png)
#### [Back](#sumário)
---
## Cliente
### C1, C2
![Diagrama de Seguencia - C1, C2](./docs/img/Diagramas%20de%20Seguencia/Cliente-C%23/C1_C2.png)
#### [Back](#sumário)
---
## Instituição
### I1
![Diagrama de Seguencia - I1](./docs/img/Diagramas%20de%20Seguencia/Institui%C3%A7%C3%A3o-I%23/I1.png)
#### [Back](#sumário)
### I2
![Diagrama de Seguencia - I2](./docs/img/Diagramas%20de%20Seguencia/Institui%C3%A7%C3%A3o-I%23/I2.png)
#### [Back](#sumário)
---
## Parceiro
### Pa1
![Diagrama de Seguencia - Pa1](./docs/img/Diagramas%20de%20Seguencia/Parceiro-Pa%23/Pa1.png)
#### [Back](#sumário)
### Pa2, Pa3
![Diagrama de Seguencia - Pa2, Pa3](./docs/img/Diagramas%20de%20Seguencia/Parceiro-Pa%23/Pa2_Pa3.png)
#### [Back](#sumário)
---
## Professor
### P1
![Diagrama de Seguencia - P1](./docs/img/Diagramas%20de%20Seguencia/Professor-P%23/P1.png)
#### [Back](#sumário)
---
## Usuário
### U1
![Diagrama de Seguencia - U1](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U1.png)
#### [Back](#sumário)
### U2
![Diagrama de Seguencia - U2](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U2.png)
#### [Back](#sumário)
### U3, U4, U5
![Diagrama de Seguencia - U3, U4, U5](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U3_U4_U5.png)
#### [Back](#sumário)
---

# Historia de Usuários e Regras de Negócio

## Historia de Usuários
- I1 -> Eu como Intituição gostaria de exportar .csv para cadastro de professores.
- I2 -> Eu como Intituição gostaria de destivar uma conta professor.

- U1 -> Eu como usuário gostaria de fazer cadastro.
- U2 -> Eu como Usuário gostaria de fazer login.
- U3 -> Eu como Usuário gostaria de ver a conta
- U4 -> Eu como Usuário gostaria de deletar a conta.
- U5 -> Eu como Usuário gostaria de editar as informações de conta.

- C1 -> Eu como Cliente gostaria de ver meu Saldo de moedas.
- C2 -> Eu como Cliente gostaria de ver meu historico e extrato.

- P1 -> Eu como Professor gostaria de fazer transferencias aos meus alunos.

- A1 -> Eu como Aluno gostaria de comprar Ofertas.
- A2 -> Eu como Aluno gostaria de ver Cupom.

- Pa1 -> Eu como Parceiro gostaria de criar Oferta.
- Pa2 -> Eu como Parceiro gostaria de verificar se um Cupom é válido.
- Pa3 -> Eu como Parceiro gostaria tornar Cupom invalido.

## Regras de negocio
- R1 -> Todo login deve ser autentificado.
- R2 -> A cada semestre é adicionado 1000 moedas ao saldo dos professores. 
- R3 -> Ao gerar o Cupom ele deve ser enviado ao aluno por email.

#### [Back](#sumário)