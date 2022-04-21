# Laboratorio-3

## Sumário

### [Diagramas](#diagramas)
- [Caso de Uso](#diagrama-de-caso-de-uso)
- [Implementação](#diagrama-de-implementação)
- [Componentes](#diagrama-de-componentes)
- [Classes](#diagrama-de-classes)
### [Historia de Usuário](#diagramas)

### [Tarefas](#tarefas)
---

# Diagramas

## Diagrama de Caso de Uso
![Diagrama de Caso de Uso](./docs/img/Caso%20de%20Uso.png)

## Diagrama de Implementação
![Diagrama de Implementação](./docs/img/Diagrama%20de%20Implementa%C3%A7%C3%A3o.png)

## Diagrama de Componentes
![Diagrama de Componentes]()

## Diagrama de Classes
![Diagrama de Classes]()

# Historia de Usuários e Regras de Negócio
## Historia de Usuários
- I1 -> Eu como Intituição gostaria de exportar .csv para cadastro de professores.
- Pa1 -> Eu como Parceiro gostaria de criar Ofertas (nome, descrição, foto do produto, instituição para qual forneceu oferta).
- Pa2 -> Eu como Parceiro gostaria de invalidar códigos gastos após a utilização do aluno.
- Pr1 -> Eu como Professor gostaria de ver meu saldo.
- Pr2 -> Eu como Professor gostaria de ver meu extrato (historico de transições).
- Pr3 -> Eu como Professor gostaria de destribuir moedas aos alunos.
- A1 -> Eu como Aluno gostaria de ver meu saldo.
- A2 -> Eu como Aluno gostaria de ver meu extrato (historico de transições).
- A3 -> Eu como Aluno gostaria de ver ofertas.
- A4 -> Eu como Aluno gostaria de comprar ofertas.
- A5 -> Eu como Aluno gostaria de receber email com código e expecificações de como resgatalo.
## Regras de negocio
- R1 -> Todos os Usuários devem ter uma conta e conseguir fazer cadastro.
- R2 -> Todos os Usuários devem ter uma conta e conseguir fazer login.
- R3 -> Todos os Logins devem ser autenticados.
- R4 -> Professores recebem 1000 moedas por simestre (Valor Acomulavel).
- R5 -> Para enviar moedas, o professor deve possuir saldo suficiente, indicando qual aluno deverá receber o montante, bem como o motivo pelo qual ele está sendo reconhecido (uma mensagem aberta, obrigatória).

# Tarefas
## Sprint 1
- [x] Fazer Diagrama de Caso de Uso.
- [x] Fazer Diagrama de Implementação.
- [ ] Fazer Diagrama de Componentes.
- [ ] Fazer Diagrama de Classes.
- [ ] Definir Tecnologias.
- [ ] Ajustes Finais.
- [ ] Listar tarefas de Sprint 2.

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
    - [ ] Criar Tela De Cadastro
        - [ ] Criar Cadastro de Parceiro -> R1
        - [ ] Salvar conta do Parceiro no Banco de dados.
        - [ ] Criar Cadastro de Aluno -> R1
        - [ ] Salvar conta do Aluno no Banco de dados.
    - [ ] Criar Tela de Login -> R1
        - [ ] Login de Parceiro -> R1
        - [ ] Login de Aluno -> R1
        - [ ] Autentifição de Login -> R3
    
    - [ ] Tela de Parceiro
        - [ ] Tela de Configurações de Conta Parceiro
            - [ ] Read conta de Parceiro.
            - [ ] Update informações de Parceiro.
            - [ ] Delete conta de Parceiro.

    - [ ] Tela de Aluno 
        - [ ] Tela de Configurações de Conta Aluno
            - [ ] Read conta de Aluno.
            - [ ] Update informações de Aluno.
            - [ ] Delete conta de Aluno.