# Laboratorio-3

## Sumário

### [Diagramas](#diagramas)
- [Caso de Uso](#diagrama-de-caso-de-uso)
- [Implementação](#diagrama-de-implementação)
- [Componentes](#diagrama-de-componentes)
- [Classes](#diagrama-de-classes)
### [Historia de Usuário](#historia-de-usuários-e-regras-de-negócio)

### [Tarefas](#tarefas)
---

# Diagramas

## Diagrama de Caso de Uso
![Diagrama de Caso de Uso](./docs/img/Caso%20de%20Uso.png)

## Diagrama de Implementação
![Diagrama de Implementação](./docs/img/Diagrama%20de%20Implementa%C3%A7%C3%A3o.png)

## Diagrama de Componentes
![Diagrama de Componentes](./docs/img/Diagrama%20de%20Componentes.png)

## Diagrama de Classes
![Diagrama de Classes](./docs/img/Diagrama%20de%20Classes.png)

# Historia de Usuários e Regras de Negócio
## Historia de Usuários
- I1 -> Eu como Intituição gostaria de exportar .csv para cadastro de professores.
- I2 -> Eu como Intituição gostaria de destivar uma conta professor.

- U1 -> Eu como usuário gostaria de fazer cadastro.
- U2 -> Eu como Usuário gostaria de fazer login.
- U3 -> eu como Usuário gostaria de ver a conta
- U4 -> Eu como Usuário gostaria de deletar a conta.
- U5 -> Eu como Usuário gostaria de editar as informações de conta.

- C1 -> Eu como Cliente gostaria de ver meu Saldo de moedas.
- C2 -> Eu como Cliente gostaria de ver meu historico e extrato.

- P1 -> Eu como Professor gostaria de fazer transferencias aos meus alunos.

- A1 -> Eu como Aluno gostaria de comprar Ofertas.
- A2 -> Eu como Aluno gostaria de ver Cupom.
- A3 -> Eu como Aluno gostaria de receber Cupom por email.

- Pa1 -> Eu como Parceiro gostaria de criar Oferta.
- Pa2 -> Eu como Parceiro gostaria tornar Cupom invalido.
## Regras de negocio
- R1 -> Todo login deve ser autentificado.
- R2 -> A cada semestre é adicionado 1000 moedas ao saldo dos professores. 
- R3 -> Ao gerar o Cupom ele deve ser enviado ao aluno por email.

# Tarefas

## Sprint 1
- [x] Fazer Diagrama de Caso de Uso.
- [x] Fazer Diagrama de Implementação.
- [x] Fazer Diagrama de Componentes.
- [x] Fazer Diagrama de Classes.

## Sprint 2
- [ ] Mapeamento do Diagrama de Classe para o Modelo ER.
- [ ] Diagramas de Sequências do Sistema para cada um dos casos de uso modelados na Sprint 01.

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