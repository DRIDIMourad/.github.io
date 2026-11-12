# TP1 : Premiers programmes

Un TP peut être un PDF ou, comme ici, une page web avec du code copiable.

## Exercice 1

Compilez et exécutez le programme suivant :

```c
#include <stdio.h>

int main(void) {
    printf("Bonjour !\n");
    return 0;
}
```

```bash
gcc -Wall hello.c -o hello && ./hello
```

??? success "Correction (cliquer pour afficher)"
    Le programme affiche `Bonjour !`.
