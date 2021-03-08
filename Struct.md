# Struct
## Cos'é la Struct

La **struct** é la *definizione* di un *__nuovo tipo di variabile derivato__*

### Cosa si intende per derivato
Per derivato si intende che ogni parte che lo costituisce é uno fra i tipi di variabili giá presenti in C

# sintassi Struct

**typedef struct **{
	char cognome[30];
	char nome[20];
	int voto;
}**alunno**;

*sei giá nel main{
**alunno** 3DSCA *[24]*;
...
return 0;
}*

> typedef--> * ti permette di rinominare la struct *
>> la *__Struct__* si definisce al di fuori del main
dopo aver chiamato le librerie *#include<stdio>*

# maneggiare la struct

la struct ha un comportamento simile a quello di un vettore
char v[5] = {'a', 'v', 'g', 'h', 'k'}

| a | v | g | h | k |
|---|---|---|---|---|
| 0 | 1 | 2 | 3 | 4 |

printf("V[0]: %c", V[0]);

***
*//char cognome[30];
	//char nome[20];
	//int voto;
*
**alunno** 3DSCA *[24]*;
printf("cognome: %s", 3DSCA[6].cognome);

>>
*terminale*
cognome: Ferri
*fine terminale*
