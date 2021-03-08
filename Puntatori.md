# Puntatori in C

# Cosa sono
Il puntatore é l'indirizzo *__Fisico__* della cella di memoria nella quale é situata la variabile che stiamo utilizzando

![alt text](http://www.itimarconi.ct.it/sezioni/didatticaonline/informatica/lezionidisistemi/immagini_terza/orgmemoria.gif)

## In che casi si usano i Puntatori

### 1. Variabili esterne alla funzione
*
void function(int\* a, int\* b){
  \*a = (\*a) \*2
  \*b = (\*b) \*2*
}

## uso dei puntatori nelle funzioni
*
>void function(int\* a, int\* b){*
>>si passa un puntatore ad una variabile int di nome *__a__*
*int\* a*-->

***

>Si lavora con il valore effettivo puntato dal puntatore *__a__*
*\*a = (\*a) \*2*

***

>*nel main{
  int a = 10;
  int b = 20;
  function(&a, &b);
*
>  
*}*
>>&a--> si passa il puntatore di a quindi l'indirizzo alla sua cella
function(&a, &b);

### caso d'uso con vettore

>*void function(int a[], int b[]){*

***

>*a = a;*

***

>*nel main{
  int a[10];
  int b[20];
  function(a, b);
*
>  
*}*