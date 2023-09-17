# Parte II do Projeto Integrador III (Desenvolvimento de Sistemas Orientado a Objetos)
## Demonstração
https://github.com/ProjetoIntegrador-Grupo12/pi-3/assets/144742247/84b8a35f-d0ec-4f47-a386-902432e1d28e

## Descrição
<p align="center">
<img style="text-align:center" src="https://github.com/ProjetoIntegrador-Grupo12/pi-3/assets/144742247/4e59c1ba-8d8e-4f49-a32c-660348e939fc" width="50%">
</p>

## Link Figma
https://www.figma.com/file/3auh7KTYoEk5SImvyosCgu/cadastro_jogador-(Copy)?type=design&node-id=0%3A1&mode=design&t=JcNULhrg08cqumVb-1

---

## Atributos e Métodos da Prototipação

### Classe: Pessoa

|Atributos|Métodos|
|---|---|
| E-mail  | Get/Set para E-mail  |
|   Senha | Get/Set para Senha   |
|   Telefone |  Get/Set para Telefone  |
|    Endereço (do tipo Endereço)|   Get/Set para Endereço|

### Classe: Pessoa Física (herda de Pessoa)

|Atributos|Métodos|
|---|---|
| Nome  |  Get/Set para Nome |
|  CPF | Get/Set para CPF |
| Data de Nascimento |  Get/Set para Data de Nascimento |
|Sexo|Get/Set para Sexo|

### Classe: Pessoa Jurídica (herda de Pessoa)

|Atributos|Métodos|
|---|---|
|  Razão Social  |   Get/Set para Razão Social |
|   CNPJ |  Get/Set para CNPJ  |

### Classe: Aluno (herda de Pessoa Física)

| Atributos  |  Métodos |
|---|---|
| Matrícula  |   Get/Set para Matrícula |
|  Curso |   Get/Set para Curso |
| Get/Set para Curso  |  Get/Set para Data de Matrícula |

### Classe: Professor (herda de Pessoa Física)

|Atributos|Métodos|
|---|---|
|  Registro  |   Get/Set para Registro	 |
| Disciplinas Lecionadas| Get/Set para Disciplinas Lecionadas  |

### Classe: Fornecedor (herda de Pessoa Jurídica)

|Atributos|Métodos|
|---|---|
|  Produtos Fornecidos |   Get/Set para Produtos Fornecidos	 |


### Classe: Administrador (herda de Pessoa Física)

|Métodos|
|---|
|Listar todos os professores|
|Listar todos os alunos|
|Listar todos os fornecedores|
|Listar um aluno específico|
|Listar um professor específico|
|Listar um fornecedor específico|
|Deletar um aluno específico|
|Deletar um professor específico|
|Deletar um fornecedor específico|
|Adicionar aluno|
|Adicionar professor|
|Adicionar fornecedor|

### Classe: Endereço

| Atributos  | Métodos  |
|---|---|
| Rua  | Get/Set para Rua  |
| Número  |  Get/Set para Número |
|  Complemento (opcional) | Get/Set para Complemento |
|  Bairro | Get/Set para Bairro  |
|  Cidade | Get/Set para Cidade  |
|  Estado  |Get/Set para Estado  |
|CEP| Get/Set para CEP|

## Integrantes do Grupo 12
- Flávio George da Silva Romeiro (flaviogsromeiro)
- Calyto Nichel Santos do Nascimento (calyto)
- João Vitor Monteiro de Oliveira (joao-vmoliveira26)
- Luan Silva Fulnazari de Souza (luanfulnazari)
- Lucas Ivan Cruger da Silva (CrugerL)
- Thaís Moreno Oliveira (Thais-Moreno)


