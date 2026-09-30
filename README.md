# Sistema de Controle de Estoque
## Objetivo

**Sistema desenvolvido em linguagem C para controle de estoque de produtos. O programa permite cadastrar até 5 produtos (código, nome, preço e quantidade), calcula o valor em estoque de cada um e exibe um relatório final com o valor total do estoque.**

## Tecnologia utilizada:

- **Linguagem: C**
- **Compiladores: GCC ou similar**
- **Bibliotecas: `<stdio.h>`**

## conceitos de estudo utilizados:
- **Variáveis**
- **Operadores aritméticos**
- **Entrada e saída de dados** 

## Como instalar 

### opção 1: Utilizando o Devc+++ (Recomendado para iniciantes)

**1.** no devc++ localize a executar na canto superior esquerdo.

**2.** na aba executar clique em compilar e executar.

### opção 2: utilizando o msys2 com gcc como compilador

**1.** Instale o MSYS2 no site:https://www.msys2.org/ e, através dele, o compilador GCC, utilizando o comando:

```
pacman -S mingw-w64-ucrt-x86_64-gcc
```
**2.** Abra o terminal através do programa MSYS2(UCRT64) e utilizando seu terminal navegue até a pasta do projeto.

utilize o comando cd:

exemplo:

```
 "cd C:\Users\SEUSUARIO\Desktop\PASTA DO PROGRAMA A SER EXECUTADO"
```

**3.** Salve o código em um arquivo, por exemplo `estoque.c`.

**4.** Compile o programa, utilizando o comando:
```
gcc estoque.c -o estoque.exe
```
**5.** Execute o programa com o comando:

```
./estoque.exe
```
## Demonstrativo
### demonstração com o item 1
```c
#include <stdio.h>

int main()
{
    	int codigo1;
    	int quantidade1;
		char nome1[50];
    	float preco1;
    	float estoque1;
    	float totalEstoque;

    	printf("====================================\n");
		printf("== SISTEMA DE CONTROLE DE ESTOQUE ==\n");
		printf("====================================\n");

    	printf("\nProduto 1\n");

    	printf("Codigo: ");
    	scanf("%d", &codigo1);
		
		totalEstoque = estoque1 

    	printf("\n====================================\n");
    	printf("          CONTROLE DE ESTOQUE\n");
    	printf("======================================\n");

    	printf("\nCodigo: %d\n", codigo1);
    	printf("Produto: %s\n", nome1);
    	printf("Valor em estoque: R$ %.2f\n", estoque1);

		printf("\n====================================\n");
    	printf("Valor total do estoque: R$ %.2f\n", totalEstoque);
    	printf("====================================\n");

    	return 0;
}
```
## Exemplo de uso ou demonstração

Ao executar o programa, o usuário informa os dados de 5 produtos (código, nome, preço e quantidade). Ao final, o sistema exibe um relatório com o valor em estoque de cada produto e o valor total:

```c
====================================
== SISTEMA DE CONTROLE DE ESTOQUE ==
====================================

Produto 1
Codigo: 101
Nome: Caneta
Preco: R$ 2.50
Quantidade: 100

====================================
          CONTROLE DE ESTOQUE
======================================

Codigo: 101
Produto: Caneta
Valor em estoque: R$ 250.00

====================================
Valor total do estoque: R$ 1250.00
====================================
```
# Autor e Contato
**Arthur lucas de souza**

[**Email**](mailto:arthur.l.souza23@gmail.com) 

[**gihub**](https://github.com/Arth84)

[**linkedin**](http://www.linkedin.com/in/arthur-lucas3222) 


