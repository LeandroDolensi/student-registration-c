# Aplicação para Cadastro de Alunos :man_student: :woman_student:

<br/>



##### Uma aplicação para Cadastro de Alunos que armazena informações sobre:

* Alunos

<br/>

##### Estrutura de dados:

```c
#define TAMNOME 50
#define TAMSOBRENOME 50

typedef struct data {
    int dia;
    int mes;
    int ano;
}data;

typedef struct registro {
    char nome[TAMNOME];
    char sobrenome[TAMSOBRENOME];
    data data_de_nascimento;
    int prontuario;
    char curso[4];
}aluno;
```



<br/>

##### Interface gráfica:

1. Cadastrar Aluno
2. Listar Alunos
3. Busca Ordenada
4. Listagem Ordenada
5. Sair

<br/>

##### Cada Submenu oferece as opções: 

- Listar todos
- Listar um elemento específico
- Incluir 
- Alterar
- Excluir

<br/>

##### Algoritmos de ordenação implementado

- [x] Quick sort
- [x] Merge Sort
- [x] Insertion Sort
- [x] Selection Sort

---

<br/>

##### Algortimos de busca implementado

- [x] Busca binára

<br/>

>Projeto realizado no curso Programação Web I e entregue como trabalho final da matéria. 
