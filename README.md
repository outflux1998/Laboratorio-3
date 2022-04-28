# Laboratorio-3

## Sumário

### [Diagramas](#diagramas)
- [Caso de Uso](#diagrama-de-caso-de-uso)
- [Implementação](#diagrama-de-implementação)
- [Componentes](#diagrama-de-componentes)
- [Classes](#diagrama-de-classes)
- [Seguencia](#diagramas-de-seguencia)
    - [Aluno](#aluno)
    - [Cliente](#)
    - [Instituição](#)
    - [Parceiro](#)
    - [Professor](#)
    - [Usuário](#)
### [Historia de Usuário](#historia-de-usuários-e-regras-de-negócio)

### [Tarefas](#tarefas-1)
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
### A1
![Diagrama de Seguencia - A1](./docs/img/Diagramas%20de%20Seguencia/Aluno-A%23/A1.png)
#### [Back](#sumário)
### A2
![Diagrama de Seguencia - A2](./docs/img/Diagramas%20de%20Seguencia/Aluno-A%23/A2.png)
#### [Back](#sumário)

## Cliente
### C1
![Diagrama de Seguencia - C1](./docs/img/Diagramas%20de%20Seguencia/Cliente-C%23/C1.png)
#### [Back](#sumário)
### C2
![Diagrama de Seguencia - C2](./docs/img/Diagramas%20de%20Seguencia/Cliente-C%23/C2.png)
#### [Back](#sumário)

## Instituição
### I1
![Diagrama de Seguencia - I1](./docs/img/Diagramas%20de%20Seguencia/Institui%C3%A7%C3%A3o-I%23/I1.png)
#### [Back](#sumário)
### I2
![Diagrama de Seguencia - I2](./docs/img/Diagramas%20de%20Seguencia/Institui%C3%A7%C3%A3o-I%23/I2.png)
#### [Back](#sumário)

## Parceiro
### Pa1
![Diagrama de Seguencia - Pa1](./docs/img/Diagramas%20de%20Seguencia/Parceiro-Pa%23/Pa1.png)
#### [Back](#sumário)
### Pa2
![Diagrama de Seguencia - Pa2](./docs/img/Diagramas%20de%20Seguencia/Parceiro-Pa%23/Pa2.png)
#### [Back](#sumário)
### Pa3
![Diagrama de Seguencia - Pa3](./docs/img/Diagramas%20de%20Seguencia/Parceiro-Pa%23/Pa3.png)
#### [Back](#sumário)

## Professor
### P1
![Diagrama de Seguencia - P1](./docs/img/Diagramas%20de%20Seguencia/Professor-P%23/P1.png)
#### [Back](#sumário)

## Usuário
### U1
![Diagrama de Seguencia - U1](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U1.png)
#### [Back](#sumário)
### U2
![Diagrama de Seguencia - U2](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U2.png)
#### [Back](#sumário)
### U3
![Diagrama de Seguencia - U3](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U3.png)
#### [Back](#sumário)
### U4
![Diagrama de Seguencia - U4](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U4.png)
#### [Back](#sumário)
### U5
![Diagrama de Seguencia - U5](./docs/img/Diagramas%20de%20Seguencia/Usu%C3%A1rio-U%23/U5.png)
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
---

# Tarefas

## Sprint 1
- [x] Fazer Diagrama de Caso de Uso.
- [x] Fazer Diagrama de Implementação.
- [x] Fazer Diagrama de Componentes.
- [x] Fazer Diagrama de Classes.

#### [Back](#sumário)

## Sprint 2
- [ ] Mapeamento do Diagrama de Classe para o Modelo ER.
- [ ] Diagramas de Sequências do Sistema para cada um dos casos de uso modelados na Sprint 01.

#### [Back](#sumário)

## Sprint 3
- [ ] Diagrama de Sequências relativo aos CRUDs de aluno e empresa parceira. 
Observação: Referencie com códigos para as Histórias de Usuário (US1, US2, ...) relativas aos CRUDS. 
- É necessário manter consistência com os demais diagramas, principalmente o de classes (ou seja, a modelagem de interações ajuda a refinar o diagrama de classes).
- [ ] Seminário de Tecnologias
- [ ] CRUDs de aluno e empresa parceira
    - [ ] Criar LandingPage 
    - [ ] Criar Tela De Cadastro -> U1
        - [ ] Criar Cadastro de Parceiro -> U1
        - [ ] Salvar conta do Parceiro no Banco de dados. -> R1
        - [ ] Criar Cadastro de Aluno -> U1
        - [ ] Salvar conta do Aluno no Banco de dados. -> R1
    - [ ] Criar Tela de Login -> U2
        - [ ] Login de Parceiro -> U2
        - [ ] Login de Aluno -> U2
        - [ ] Autentifição de Login -> R1
    
    - [ ] Tela de Parceiro
        - [ ] Tela de Configurações de Conta Parceiro -> U3
            - [ ] Read conta de Parceiro. -> U3
            - [ ] Update informações de Parceiro. -> U5
            - [ ] Delete conta de Parceiro. -> U4

    - [ ] Tela de Aluno 
        - [ ] Tela de Configurações de Conta Aluno -> U3
            - [ ] Read conta de Aluno. -> U3
            - [ ] Update informações de Aluno. -> U5
            - [ ] Delete conta de Aluno. -> U4

#### [Back](#sumário)