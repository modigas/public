## foreach

### Instructions

Écrire une fonction `ForEach` qui, pour un tableau d'`int`, applique une fonction sur chaque éléments de ce tableau.

### Fonction attendue

```go
func ForEach(f func(int), arr []int) {

}
```

### Utilisation

Voici un éventuel programme pour tester votre fonction :

```go
package main

import piscine ".."

func main() {
	arr := []int{1, 2, 3, 4, 5, 6}
	piscine.ForEach(piscine.PutNbr, arr)
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
123456
student@ubuntu:~/[[ROOT]]/test$
```
