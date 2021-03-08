# appunti

## Sintassi della funzione

>(obbligatorio)
>[opzionale]

# dizionario/prototipo della funzione

(tipoFunzione) (nomeFunzione) ([]);

## Tipo della funzione
1. Int-->numero intero
1. float-->numero con la virgola
1. double-->numero con la virgola a piú decimali
1. char-->carattere *ASCII*
1. void-->nessuna tipologia

>>*__VOID__* é l'unica tipologia che non ha un return


# sintassi funzione

(tipoFunzione) (nomeFunzione) ([]){

  **return;**
  >Se tipoFunzione == void (non si inserisci il return)

}

# sintassi main
*__
int main(void) {
  >*Io scrivo qui*

  return 0;
}
__*

# richiamare la funzione nel  *__main__*

int main(void) {
  
  > 
  1. NON VOID 
  >tipoVar nomeVar = nomeFunzione([]);//restituisce il return di nomeFunzione
  1. VOID
  >nomeFunzione([]);
  

  return 0;
}

# extra
## printf e scanf 
# %:
1. **d** digit-->int
1. **u** double-->double
1. **f** float-->float
1. **s** string-->char[]